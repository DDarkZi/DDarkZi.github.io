# ddarkzi.github.io

GitHub 사용자 사이트예요. 하는 일은 두 가지예요.

- `index.html`: `https://ddarkzi.github.io/`로 들어오면 게임(`/jjak-relay-defense/`)으로 보내 줘요.
- `.well-known/assetlinks.json`: 구글 플레이 앱(TWA)이 이 사이트의 주인이 맞는지 확인하는 파일이에요. 앱 위쪽 주소창을 숨기는 데 필요해요.
  - 지금은 비어 있어요(`[]`). PWABuilder에서 받은 `assetlinks.json` 내용과, 플레이 콘솔 **설정 → 앱 무결성**의 **앱 서명 키 SHA-256** 지문을 넣어야 해요.
- `.nojekyll`: 점(.)으로 시작하는 폴더(`.well-known`)도 사이트에 올라가게 해 줘요.

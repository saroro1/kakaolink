# kakaolink
## how to use?
```javascript
const { KakaoLinkClient } = require('kakaolink');
const Kakao = new KakaoLinkClient("apiKey", "url")

Kakao.login("email", "password");

Kakao.sendLink('roomName', {
    template_id: 00000,
    template_args: {

    }
}, 'custom') // or 'default' for not use custom template
```

사용법은 [여기](https://github.com/archethic/kakaolink/wiki/1.-모듈-적용법)를 참고해주세요.

## download
[github release](https://github.com/archethic/kakaolink/releases)

[Developer Server](https://arthic.dev/kakaolink.zip)

## error
[error.md](https://github.com/archethic/kakaolink/blob/main/doc/user/error.md)를 참고해주세요

## migration
[migration.md](https://github.com/archethic/kakaolink/blob/main/doc/user/migration.md)를 참고해주세요
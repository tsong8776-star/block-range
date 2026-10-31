# 블록 사격장

여러 명이 로그인 없이 링크만으로 함께 접속하는 3D 사격장 게임입니다.

## 파일 구성

| 파일 | 하는 일 |
|---|---|
| `index.html` | 게임 화면(3D 사격장, 캐릭터, 점수판) |
| `server.js` | 게임 서버. 게임 화면을 보내 주고, 접속한 사람들끼리 위치와 사격을 주고받게 해 줍니다 |
| `package.json` | 서버를 실행하는 데 필요한 정보 |

## Render에 올리는 설정값

| 항목 | 값 |
|---|---|
| Language (Runtime) | Node |
| Build Command | `npm install` |
| Start Command | `npm start` |
| Instance Type | Free |
| Region | Singapore (한국에서 가장 가까움) |

## 내 컴퓨터에서 실행해 보기 (선택)

Node.js를 설치한 뒤, 이 폴더에서 아래를 실행하고 브라우저에서 http://localhost:3000 을 엽니다.

```bash
npm install
```

```bash
npm start
```

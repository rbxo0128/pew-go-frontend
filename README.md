# Pew & Go 웹사이트

Pew & Go(Little Ruckus Games) 공식 사이트. 정적 HTML/CSS라 빌드 과정이 없습니다.

| 경로 | 내용 |
| --- | --- |
| `/` | 게임 소개 (영어, 기본) — Pew & Go |
| `/ko/` | 게임 소개 (한국어) — 빵야 퀘스트 |
| `/privacy/` | 개인정보처리방침 (영어, 아래 `#ko`에 한국어) |
| `/support/` | 고객지원 (영어, 아래 `#ko`에 한국어) |

## 로컬 미리보기

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

## 배포

`index.html`, `privacy/`, `support/`, `assets/`를 정적 호스팅 루트에 그대로 올리고 `pewandgo.mogako.xyz`에 연결합니다.
Play Console의 개인정보처리방침 URL에는 `https://pewandgo.mogako.xyz/privacy/`를 입력합니다.

글꼴(Barlow) 라이선스: `assets/fonts/OFL-Barlow.txt`

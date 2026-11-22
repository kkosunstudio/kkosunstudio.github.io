# kkosunstudio.github.io

꼬순 스튜디오(Kkosun Studio) 사이트. GitHub Pages로 `main` 브랜치를 그대로 배포한다.

## 구조

| 경로 | 내용 |
|---|---|
| `/` (`index.html`) | 첫 화면, 앱 목록 |
| `/assets/site.css` | 모든 페이지 공통 스타일 |
| `/img/<앱>.webp` | 앱 아이콘(256px) |
| `/<앱>/` | 앱 소개 |
| `/<앱>/privacy/` | 앱 개인정보 처리방침 — **스토어에 넣는 주소** |
| `/app-ads.txt` | AdMob 판매자 인증(계정 하나라 모든 앱 공용, 앱이 늘어도 그대로) |
| `/privacy/` | 예전 주소 → `/puppy-merge/privacy/`로 이동 |

## 새 앱 추가

1. `puppy-merge/` 폴더를 복사해 새 이름으로(예: `cat-merge/`)
2. `<앱>/index.html` 소개 글, `<앱>/privacy/index.html`의 앱 이름·처리하는 정보·시행일 고치기
3. 아이콘을 `img/<앱>.webp`(256px)로 넣기
4. 첫 화면 `index.html`의 앱 카드를 복사해 추가
5. 푸시하면 1~2분 뒤 반영. 스토어 처리방침 URL: `https://kkosunstudio.github.io/<앱>/privacy/`

같은 AdMob 계정이면 `app-ads.txt`는 고치지 않는다.

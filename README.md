# 기후 책임 증거카드

중학교 2학년 도덕 「자연과의 관계」 단원(기후정의 · 환경정의) 수업에서 쓰는 증거카드 8장 웹앱입니다.
학생은 태블릿으로 카드를 읽고, 활동지 Step 3에 유형 · 책임져야 할 주체 · 한 줄을 기록합니다.

## GitHub Pages로 배포하기

1. GitHub에서 새 저장소를 만듭니다. (예: `evidence-cards`, Public)
2. 이 폴더의 파일(`index.html`, `.nojekyll`, `README.md`)을 저장소 맨 위에 올립니다.
   - 웹에서 올릴 때 : **Add file → Upload files** 로 끌어다 놓고 **Commit changes**
3. 저장소의 **Settings → Pages** 로 갑니다.
4. **Build and deployment → Source** 를 `Deploy from a branch` 로, Branch 를 `main` / `/(root)` 로 정하고 **Save**.
5. 1~2분 뒤 `https://<내 아이디>.github.io/evidence-cards/` 주소가 생깁니다.
6. 이 주소를 QR 코드로 만들어 PPT나 활동지에 넣습니다.

## 알아 둘 점

- 별도 서버나 설치가 필요 없는 HTML 한 장입니다. 글꼴(IBM Plex Sans KR, Black Han Sans)만 Google Fonts에서 불러옵니다.
- 학생이 고른 카드와 읽음 표시는 각 기기의 브라우저에만 저장되며, 어디로도 전송되지 않습니다.
- 학생용 페이지에는 예시 답이 들어 있지 않습니다. 교사용 페이지는 저장소에 올리지 마세요.
  (GitHub Pages는 공개 사이트라 주소를 아는 누구나 볼 수 있습니다.)
- 카드 내용을 고치려면 `index.html` 안의 `const CARDS = [` 부분의 글을 바꾸면 됩니다.

## 출처

- ① 광고 속 ‘친환경’ : 수업용 가상 사례
- ② 헌법재판소 2024. 8. 29. 결정, 2026. 8. 탄소중립기본법 개정
- ⑤ 교과서 214쪽, ⑥ 교과서 216쪽

# 기타큐슈 3박 4일 여행 웹사이트

2026년 10월 8일 ~ 10월 11일 여행 일정을 친구와 공유하기 위한 정적 웹사이트입니다.

## GitHub Pages로 공개하기

1. GitHub에서 새 저장소를 만듭니다.
   - 추천 이름: `kitakyushu-2026`
   - Public 저장소가 가장 간단합니다.

2. 이 폴더 안의 파일을 저장소 최상단에 업로드합니다.
   - `index.html`
   - `favicon.svg`
   - `site.webmanifest`
   - `.nojekyll`
   - `README.md`

3. GitHub 저장소에서:
   - `Settings`
   - `Pages`
   - `Build and deployment`
   - `Source: Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
   - `Save`

4. 잠시 후 아래 형태의 주소가 생성됩니다.

   `https://YOUR_GITHUB_ID.github.io/kitakyushu-2026/`

이 주소를 친구에게 보내면 됩니다.

## 로컬에서 확인하기

`index.html`을 브라우저에서 바로 열면 됩니다.

별도 서버, Node.js, Python, Supabase는 필요하지 않습니다.

## Supabase는 언제 필요한가?

현재 사이트는 일정 보기만 하는 정적 사이트라 필요하지 않습니다.

추후 아래 기능을 추가할 때 Supabase를 붙이면 좋습니다.

- 친구와 일정 공동 수정
- 체크리스트 동기화
- 여행 경비 입력
- 식당 후보 저장
- 로그인
- 사진 업로드
- 실시간 메모

## 포함 기능

- 모바일 반응형
- 날짜별 일정 타임라인
- Touch Kyushu 사용 구간 표시
- Google Maps 길찾기 버튼
- 여행 준비 체크리스트
- 홈 화면 추가용 manifest

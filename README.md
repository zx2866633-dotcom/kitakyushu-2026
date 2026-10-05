# 기타큐슈 3박 4일 최종 플래너

GitHub Pages용 정적 웹사이트입니다.

## 업데이트 방법
기존 저장소 최상단(root)에 아래 파일을 업로드/교체하세요.

- index.html
- favicon.svg
- README.md
- sw.js — 이전 버전 캐시 정리용
- .nojekyll

GitHub Pages가 이미 활성화돼 있다면 commit 후 수십 초~수분 내 기존 주소에 반영됩니다.

## 주요 기능
- 오송스테이 반영
- 친구용 Visit Japan Web / Touch Kyushu / eSIM 체크
- 짐 체크박스
- 현재 날씨와 일정 교차검토
- 일정별 삭제 버튼 + 일일 예상지출 자동 재계산
- Pass Case 사용 구간
- THE OUTLETS KITAKYUSHU 몽벨 쇼핑
- 일본 Tax-Free / 한국 귀국 면세 기준
- 국내 네이버지도, 일본 Google Maps 링크

체크 상태와 삭제 상태는 각 브라우저 localStorage에 저장되며 서로 동기화되지 않습니다.

기존 저장소에 예전 `sw.js`가 있었다면 이번 `sw.js`로 반드시 교체하세요. 이전 웹사이트 캐시가 남는 것을 방지합니다.
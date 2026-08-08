LOTTO_GITHUB_WEB
================

목적
----
이 웹페이지는 Excel의 FINAL_자동발급 시트에서 "순번=1"인 6개 번호만 읽어서 보여줍니다.
웹페이지 자체에서 로또 번호를 계산/예측하지 않습니다.

GitHub Pages 배포 방법
----------------------
1. GitHub.com에 로그인합니다.
2. New repository를 만듭니다. 예: lotto-web
3. 이 폴더의 파일 전체를 repository에 업로드합니다.
   - index.html
   - data/원본엑셀.xlsx
4. GitHub repository에서 Settings → Pages로 이동합니다.
5. Build and deployment에서:
   Source = Deploy from a branch
   Branch = main / (root)
6. Save를 누릅니다.
7. 잠시 후 GitHub가 표시하는 Pages 주소로 접속합니다.

매주 업데이트
--------------
1. 최신 당첨번호를 기존 Excel에 반영합니다.
2. Excel의 FINAL_자동발급이 새 회차 기준으로 갱신되었는지 확인합니다.
3. GitHub repository의 data/원본엑셀.xlsx를 새 파일로 교체합니다.
4. GitHub Pages가 자동으로 다시 배포합니다.

중요
----
- 화면에는 FINAL_자동발급의 1순위 6개만 표시합니다.
- 30개 조합, 점수표, 통계표, Monte Carlo 등은 표시하지 않습니다.
- 최신 회차는 로또데이터 시트에서 자동으로 찾아 +1 합니다.
- 1순위 조합이 없거나 검증에 실패하면 임의 번호를 만들지 않고 오류를 표시합니다.
- GitHub Pages에서는 브라우저가 Excel을 읽을 수 있도록 SheetJS CDN을 사용합니다.
  따라서 사용자가 접속할 때 인터넷 연결이 필요합니다.

현재 제공된 Excel 기준 확인값
----------------------------
최신 회차: 1236
다음 회차: 1237
FINAL_자동발급 1순위: 10 · 27 · 31 · 33 · 37 · 42

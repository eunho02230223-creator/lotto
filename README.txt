GitHub Pages용 LOTTO FINAL PICK

중요: Python은 사용자 PC에 설치할 필요가 없습니다.
GitHub Actions가 data/원본엑셀.xlsx를 읽어 data/result.json을 자동 생성합니다.

업로드할 때는 이 폴더 안의 파일 전체를 repository 최상위에 올리세요.
최종 구조:
index.html
build_data.py
README.txt
data/원본엑셀.xlsx
data/result.json
.github/workflows/update-lotto.yml

매주:
1) data/원본엑셀.xlsx 교체
2) GitHub에 commit
3) Actions가 자동으로 Excel을 분석하여 result.json 갱신
4) Pages가 새 결과를 표시

현재 확인값: 1237회 / 10 27 31 33 37 42

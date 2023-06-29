# 민족, 국민, 국가: 시계열 워드 임베딩을 활용한 조선일보 기사의 민족 담론 의미 변동 추적 (1920~40) 부록

이 Github 페이지는 "민족, 국민, 국가: 시계열 워드 임베딩을 활용한 조선일보 기사의 민족 담론 의미 변동 추적 (1920~40)"에서 제시된 데이터 전처리 및 분석 과정을 설명하는 메뉴얼이자 부록이다. 지면의 한계와 디지털인문학 연구의 특성상 연구 전과정을 논문 형태로는 공개하기 어렵기 때문에 이 페이지를 통해 부족한 내용을 채워 연구 재현성을 제고하고자 한다.

### 1. 데이터 안내
data 폴더에 분석에 필요한 파일 저장. 용량 문제로 조선일보 데이터(텍스트, 모델)는 구글 드라이브 [링크](https://drive.google.com/file/d/1NQuHfDw4_L0_9qpFDYw4YO3jxcr5vWyY/view?usp=share_link)에서 다운 가능. 조선일보 기사 전체 파일은 저작권 문제로 공개가 어렵기 때문에 주요 품사 토크나이징 완료 데이터를 공유함.

### 2. 코드 안내
* DBE.ipynb : 데이터 전처리 과정 및 시계열 워드 임베딩 학습 python 코드
* DBE_Analysis.ipynb : 시계열 워드 임베딩 학습 결과 기반 분석 python 코드. 분석 결과는 results 폴더에 있음.
* trend_test.qmd(html) : 추세 검정 R 코드

### 3. 시계열 워드 임베딩 결과
[연도별 민족, 국민, 국가 유사어](https://docs.google.com/spreadsheets/d/1kG-WOK1Wy7gPL-VERNrIctCk28DwFTQ1qIeet_U21tk/edit?usp=sharing)

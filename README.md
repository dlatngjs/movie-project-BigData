🎬 AI 기반 영화 줄거리 요약 & 추천 시스템

📌 TMDB API로 영화 데이터를 수집하고, WordCloud·Top10 시각화·요약/추천 기능을 구현한 데이터 분석 프로젝트입니다.

📁 프로젝트 소개

TMDB API에서 실시간 영화 데이터를 불러오고
전처리 및 텍스트 분석을 거쳐 영화 줄거리를 요약하고 추천하는 시스템입니다.
장르 기반 인기 영화 Top10 분석, WordCloud 시각화, 요약 기능까지 포함합니다.

🛠 사용 기술(Tech Stack)
분야	기술
언어	Python
데이터 처리	Pandas, Numpy
데이터 시각화	Matplotlib, WordCloud
자연어 처리	NLTK Summarization
API	TMDB API 사용
📂 프로젝트 구성
📁 movie-project-BigData
├── Project.ipynb         # 분석/시각화/요약/추천 전체 코드
├── project.py            # 실행용 코드
├── README.md             # 프로젝트 설명 파일
└── (향후 WordCloud 이미지/그래프 이미지 추가 가능)

🔍 주요 기능
기능	설명
📌 TMDB API로 데이터 수집	영화 제목/개봉일/평점/장르 등 정보 저장
📌 전처리 진행	토큰화·불용어 제거·형태소 추출
📌 WordCloud 시각화	Overview 텍스트 기반 핵심 단어 분석
📌 Top10 영화 분석 그래프	평점 기반 인기 영화 순위 시각화
📌 AI 줄거리 요약	긴 overview에서 핵심 내용만 2~3줄 요약
📌 추천 기능	장르 입력 시 추천 영화 Top5 제공

📌 결론

TMDB API 기반 데이터 분석 및 시각화 성공

WordCloud로 핵심 키워드 파악

NLTK Summarization으로 영화 줄거리 자동 요약 확인

확장성 → GPT/KoBART 연결, 사용자 평점 기반 추천 모델 고도화 가능

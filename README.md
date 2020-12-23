1. korean_data.ipynb

- CNN을 사용해 긍, 부정 분석
- colab에서 코드 진행
- TRAIN_DIR, TEST_DIR에 각각 ratings_train, ratings_test 파일 위치를 입력해 훈련 진행
( colab 환경에서는 google drive에 파일을 업로드 한 후 실행 파일을 불러옴)
- ko에 분석할 데이터 파일(ko_data.csv) 위치를 입력해 최종 결과물 산출


2. english_data.ipynb

- BERT를 사용해 감정 분석
- colab에서 코드 진행
- GPU 사용이 가능한 환경에서 구동해야 함

- txt2, txt3, txt4에 각각 frineds_train, frineds_test, friends_dev 파일 위치를 입력해 훈련 진행
( colab 환경에서는 google drive에 파일을 업로드 한 후 실행 파일을 불러옴)
- eng에 분석할 데이터 파일(en_data.csv) 위치를 입력해 최종 결과물 산출

참고코드:
https://github.com/cjmp1/nlp-sentiment-analysis/blob/master/ENG/BERT.py

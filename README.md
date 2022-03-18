## Text-Sentiment-Analysis-ML

### 1. Overview
- 머신러닝을 활용한 텍스트 감성 분석(분류) 모델 
- 나이브 베이지 정리 (Naïve Bayes Classification) 모델 활용
- 머신러닝 모델을 만들어 소비자의 리뷰를 ‘기쁨’, ’기대’, ’놀람’, ’공포’, ’분노’, ’슬픔’으로 분류 
- 소비자 리뷰를 통한 인사이트 탐구 필요


### 2. Research Process
#### 1) 데이터 수집 & 전처리
- 크롤링한 데이터를 전처리 및 6가지 감성 라벨링 (맞춤법 검사, 불용어 처리)

#### 2) 트레이닝/ 테스트 데이터셋 생성
- 데이터로 트레이닝/테스트셋 생성 후 학습 
- 텍스트 데이터는 벡터화 후 수치화하여 훈련

#### 3) 분류 시스템 설계 (6가지 감성분류)
- 나이브베이즈 분류 모델 사용 
- 기쁨, 기대, 놀람, 공포, 분노, 슬픔 : 감정 분류

#### 4) 정확도 평가
- 테스트셋으로 정확도 평가 
- 직접 입력한 텍스트으로도 모델 성능 검사


### 3. Model Accuracy & Result
- Accuracy : 71%

![모델링 정확도](https://user-images.githubusercontent.com/40832965/154876416-4b75a56f-2d3b-4de3-8239-ca382d9f0bca.png)

- Classification Result

![직접 입력한 데이터 예측 결과](https://user-images.githubusercontent.com/40832965/154876435-159bb934-48a9-4edd-8d81-34438b4c392f.png)

### 4. Requirements
- Google Colab / Jupyter
- Python 3.x

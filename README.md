# Kaggle-ML
kaggle ML 

이 링크에서 발췌했습니다.
https://www.kaggle.com/daehungwak/guide-kor-

Contents 
  1. 데이터 분석 시작하기 앞서서
  데이터가 어떻게 구성되어 있는지 확인합니다.
  대부분의 캐글 데이터들은 잘 정제되어 있습니다.
  하지만 가끔 null data가 존재합니다. 이를 확인하고, 향후 수정합니다.
  2. 데이터 셋 확인
  여러 feature 들을 개별적으로 분석하고, feature 들 간의 상관관계를 확인합니다.
  여러 시각화 툴을 사용하여 insight를 얻습니다.
  3. 탐색적 데이터 분석 (EDA, Exploratory Data Analysis)
  모델을 세우기에 앞서, 모델의 성능을 높일 수 있도록 feature 들을 engineering 합니다.
  one-hot encoding, class로 나누기, 구간으로 나누기, 텍스트 데이터 처리 등을 합니다.
  4. 특성 공학 (Feature Engineering)
  sklearn, keras 을 사용해 모델을 만듭니다. 파이썬에서 머신러닝을 할 때는 sklearn 을
  사용하면 수많은 알고리즘을 일관된 문법으로 사용할 수 있습니다. 또 keras는 딥러닝 개발
  할 때 모델에 집중할 수 있도록 해줍니다. 물론 딥러닝을 위해 tensorflow, pytorch 등을
  사용할 수 도 있습니다. 그리고 학습된 모델이 어떤 것을 학습하였는 지 확인해봅니다
  5. 모델 개발 및 학습
  Train set 을 가지고 모델을 학습시킨 후, Test set 을 가지고 prediction 합니다.
  그리고 예측 성능이 원하는 수준인지 판단합니다.
  풀려는 문제에 따라 모델을 평가하는 방식도 달라집니다.
    A. scikit-learn을 사용한 RandomForest모델 개발
    B. keras를 사용한 NN 모델 개발 (미완)
  6. 모델 예측 및 평가
    A. RandomForest 예측 및 평가
    B. NN 예측 및 평가 (미완)
  7. 결론
  8. 어떻게 공부하는게 좋을까요?

https://www.kaggle.com/raasik/heart-disease-beginner-eda-and-machine-learning
여기 참조하면서 https://www.kaggle.com/ronitf/heart-disease-uci 이 의료 데이터 분석 하기

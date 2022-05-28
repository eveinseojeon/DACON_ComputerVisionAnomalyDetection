## [Computer Vision 이상치 탐지(Anomaly Detection) 알고리즘 경진대회](https://dacon.io/competitions/official/235894/overview/description)



### 주제

사물의 종류와 상태를 분류하는 컴퓨터 비전 알고리즘 개발



### 데이터

MVtec AD Dataset에는 15 종류의 사물이 존재하며, 사물의 상태(정상 vs 비정상)에 따라 이미지가 분류되어 있다.



### 수행 방법

1. Model Ensemble을 이용하여 사물의 종류와 상태가 88개를 분류하는 모델을 만들 예정이다.
2. Train 이상치 사진 개수가 적으므로 오버샘플링을 해준다.
3. EfficientNet과 ResNet-50, VGG19, DenseNet121 4개의 모델을 각각 학습시킨 뒤 앙상블한다.
4. 결과값을 확인하며 미흡한 점을 수정해 나간다.



### 참여 기간

2022/05/03 - 2022/05/17



### 구성원

전인서, [김원빈](https://github.com/BaeJjangE), [박형준](https://github.com/PHJoon), [형한결](https://github.com/hankaul)

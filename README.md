## [Computer Vision 이상치 탐지(Anomaly Detection) 알고리즘 경진대회](https://dacon.io/competitions/official/235894/overview/description)

### ✔ 주제

: 사물의 종류와 상태를 분류하는 컴퓨터 비전 알고리즘 개발

### ✔ 데이터

: MVtec AD Dataset에는 15 종류의 사물이 존재하며, 사물의 상태(정상 vs 비정상)에 따라 이미지가 분류되어 있어 총 88개 라벨이 존재한다.

### ✔ 수행 방법

1. Train 데이터를 확인했을 때 정상에 비하여 이상치가 현저히 적으므로 이상치를 오버샘플링해준다.
2. Test 데이터를 잘 맞추기 위해 rotation, zoom, flip 등의 augmentation 작업을 해준다. 
3. 사물의 종류와 상태에 따라 88개 라벨로 분류하는 모델 4개(EfficientNetB3, ResNet50V2, VGG19, DenseNet121)를 각각 학습시킨 뒤 앙상블한다.
4. 결과값을 확인하며 미흡한 점을 수정해 나간다.

### ✔ 사용 라이브러리

: Os, Shutil, Time, Pandas, Numpy, Tensorflow, Keras

### ✔ 참여 기간

: 2022.05.02 - 2022.05.17

### ✔ 멤버

: 전인서, [김원빈](https://github.com/BaeJjangE), [박형준](https://github.com/PHJoon), [형한결](https://github.com/hankaul)


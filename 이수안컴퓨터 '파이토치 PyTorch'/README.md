기간: 2023.02.14 ~ 2023.03.09

> [!IMPORTANT]
> Open MCT is now running, and can be accessed by pointing a web browser at [http://localhost:8080/](http://localhost:8080/)

## 1. Pytorch basic
- **노트북 파일:** [pytorch_basic.ipynb](https://github.com/ksouth0413/dltutorial/blob/main/%EC%9D%B4%EC%88%98%EC%95%88%EC%BB%B4%ED%93%A8%ED%84%B0%20'%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20PyTorch'/pytorch_basic.ipynb)
- **사용 데이터셋:**
  1. `y = x + 3 * N(0,1)` (간단한 데이터 생성)
  2. FashionMNIST (의류 이미지 데이터셋)
- **모델 구조:**
  1. **Linear 모델:** `y = xw + b` (회귀)
  2. **간단한 CNN 모델:** 기본적인 합성곱 신경망 구조 (분류)
- **특이사항:** 
  - `torchvision.datasets`을 사용하여 데이터셋을 다운로드 및 전처리


## 2.1. CNN basic 1
- **노트북 파일:** [cnn_basic(1).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/%EC%9D%B4%EC%88%98%EC%95%88%EC%BB%B4%ED%93%A8%ED%84%B0%20'%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20PyTorch'/cnn_basic(1).ipynb)
- **사용 데이터셋:** FashionMNIST (흑백 이미지 데이터셋)
- **모델 구조:**
  - **모델 1:** 10개의 Conv2D + 2개의 FC 레이어
  - **모델 2:** 2개의 Conv2D + 5개의 FC 레이어
- **특이사항:**
  - 모델1,2에 따라 `batch_size`로 128과 64을 비교


## 2.2. CNN basic 2
- **노트북 파일:** [cnn_basic(2).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/%EC%9D%B4%EC%88%98%EC%95%88%EC%BB%B4%ED%93%A8%ED%84%B0%20'%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20PyTorch'/cnn_basic(2).ipynb)
- **사용 데이터셋:** CIFAR10 (컬러 이미지 데이터셋)
- **모델 구조:** 간단한 CNN 모델
- **특이사항:**
  - CNN 내부 layer를 어떻게 바꿔야 성능이 좋을지 고민
  - 향후 다른 CNN모델의 시작점(UNet,VGGNet,ResNet)


## 3.1. CNN advanced 1
- **노트북 파일:** [cnn_advanced(1).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/%EC%9D%B4%EC%88%98%EC%95%88%EC%BB%B4%ED%93%A8%ED%84%B0%20'%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20PyTorch'/cnn_advanced(1).ipynb)
- **사용 데이터셋:** tire.zip, ants.zip, bees.zip
- **모델 구조:** 전이학습 모델 (ResNet18)
- **특이사항:**
  - 전이학습을 다룸
  - PIL 라이브러리와 data augmentation으로 데이터 전처리를 다룸
  - Pytorch에서 제공하지 않는 Dataset을 사용 (ImageFolder, Custom Dataset Class 활용)


## 3.2. CNN advanced 2
- **노트북 파일:** [cnn_advanced(2).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/%EC%9D%B4%EC%88%98%EC%95%88%EC%BB%B4%ED%93%A8%ED%84%B0%20'%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20PyTorch'/cnn_advanced(2).ipynb)
- **사용 데이터셋:** animals10.zip, soccer.zip
- **모델 구조:** 
  - 상세 정보 없음
- **특이사항:** 
  - 추가 정보 없음


## 4. RNN
- **노트북 파일:** [cnn_advanced(2).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/%EC%9D%B4%EC%88%98%EC%95%88%EC%BB%B4%ED%93%A8%ED%84%B0%20'%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20PyTorch'/cnn_advanced(2).ipynb)
- **사용 데이터셋:** animals10.zip, soccer.zip
- **모델 구조:** 
  - 상세 정보 없음
- **특이사항:** 
  - 추가 정보 없음

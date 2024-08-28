# 딥러닝 튜터리얼

## 1. 이수안컴퓨터 파이토치 PyTorch
> [!NOTE]
> These codes are modified from 이수안컴퓨터(youtube)<br>
> Please visit his [Official Site]((https://youtube.com/playlist?list=PL7ZVZgsnLwEEIC4-KQIchiPda_EjxX61r&si=_j5ENGvInnXsA7Ik))(https://nasa.github.io/openmct/getting-started/)
> 
기간 : 2023.02.14 ~ 2023.03.09
[pytorch_basic.ipynb]() : 
데이터 : 1. y=x+3*N(0,1) 2. FashionMNIST
모델 : 1. linear모델(y=xw+b) 2. 간단한cnn모델
특이사항 : torchvision.datasets을 통해 데이터 다운로드



|23.02.16|[cnn_basic(1).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/cnn_basic(1).ipynb)|FashionMNIST(흑백)|두가지간단한cnn모델|1. 10개의Conv2d+2개의fc & 2개의Conv2d+5개의fc<br>2. batch_size128,64|[이수안컴퓨터](https://youtu.be/IwLOWwrz26w?list=PL7ZVZgsnLwEEIC4-KQIchiPda_EjxX61r)|pytorch|
|23.02.16|[cnn_basic(2).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/cnn_basic(2).ipynb)|CIFAR10(컬러)|간단한cnn모델||[이수안컴퓨터](https://youtu.be/E-LodDU6pIA?list=PL7ZVZgsnLwEEIC4-KQIchiPda_EjxX61r)|pytorch|
|23.02.16|[cnn_advanced(1).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/cnn_advanced(1).ipynb)|tire.zip,ants.zip,bees.zip|전이학습(resnet18)|Pytorch에서 제공하지 않는 Dataset을 사용(ImageFolder, Custom Dataset Class)|[이수안컴퓨터](https://youtu.be/szfjmRYPX-4?list=PL7ZVZgsnLwEEIC4-KQIchiPda_EjxX61r)|pytorch|
|23.02.16|[cnn_advanced(2).ipynb](https://github.com/ksouth0413/dltutorial/blob/main/cnn_advanced(2).ipynb)|animals10.zip,soccer.zip||||pytorch|

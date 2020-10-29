# reinforcement-learning-Study
파이썬과 케라스로 배우는 강화학습

### 환경설정 방법

#### 1) VSCode 파이썬 인터프리터 설정
> * Command Palette에서 "python : select interpreter" 를 입력해서 파이썬 인터프리터를 설정하는 화면으로 이동합니다.
> * 화면에서 여러 python 인터프리터가 나올 수 있는데 그 중에서 위에서 설치한 아나콘다의 파이썬 인터프리터를 선택합니다.

#### 2) 아나콘다 파이썬 환경 생성

> * conda create -n rlenv python=3.6
> * conda activate rlenv (가상환경 실행)

#### 3) 텐서플로우 2.0 설치

> ###### pip 로 설치하는 방법
> * TensorFlow 2 패키지에는 pip 버전 >19.0이 필요합니다.
> * pip install tensorflow <br>
> ###### conda로 설치하는 방법
> * conda install tensorflow
> ###### tensorflow 설치확인
> * conda list

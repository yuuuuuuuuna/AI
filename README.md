# 인공지능(artificial intelligence, AI)
컴퓨터 시스템이 인간의 지능적인 작업을 모방하거나 수행할 수 있는 능력   
간단하게 말하면, 인간처럼 사고하고 행동하는 컴퓨터를 만드는 것   
<br/>

* 자동화
* 정확/신속
* 연구/개발 가속화
  <br/><br/><br/>

  <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/eff66b4e-510b-4d0c-aa6e-057b6e5fd039" width="600px" height="400px" title="px(픽셀) 크기 설정" alt=""></img><br/><br/><br/>
  

      
## 머신러닝(Machine Learning)   
컴퓨터가 데이터 속에서 다양한 것들을 학습하고 예측할 수 있도록 하는 인공지능의 한 형태   
데이터와 정답을 입력하면 스스로 그 안의 규칙을 찾아내어 정답을 도출   
<br/>

- **지도학습(Supervised learning)**   
인간인 관여자가 문제에 대한 답을 알고 있고, 인공지능(AI)이 그것을 알아낼 수 있도록 훈련시키고자 할 때 사용
지도 학습 알고리즘의 목표는 새롭게 투입된 입력 데이터에 적합한 레이블을 예측하여 제대로 분류하고 이해하는 것<br/><br/>
  - **분류 기법(Classification techniques)** : 입력 데이터를 특정 클래스 또는 그룹의 구성원으로 식별하기 위해 알고리즘에 이산 값을 예측하도록 요청한다. 패턴 인식에 매우 뛰어나 이미지 인식과 같은 용도에 이상적
  - **선형 회귀 (Linear regression)** : 선형 회귀분석은 연속 데이터를 사용
 <br/>
 
  > *추천엔진*, *이미지 인식*, *목적지 도착 시간 계산*    
     지도 학습은 일련의 활용 가능한 참조 포인트(즉, 훈련 데이터) 또는 부정할 수 없는 진실(바나나의 모양)이 있어서 알고리즘을 훈련하는 데 사용할 수 있을 때 가장 적합

  <br/>
  <br/>

- **비지도 학습(Unsupervised learning)**   
  학습 알고리즘에 결과물이라고 할 수 있는 출력을 미리 제공하지 않고 인공지능(AI)이 입력 세트에서 패턴과 상관관계를 찾아내야 하는 머신러닝 알고리즘
  데이터 자체가 부족하거나 훈련 데이터를 수집하기에는 비용이 너무 높은 등의 이유로 출력에 대해 알 수 없거나 활용할 수 없을 때 주로 사용   <br/><br/>
  *AI를 어린 아이라고 가정할 때, 지도 학습은 색깔, 숫자 또는 어휘와 같이 인간이 이미 알고 있는 것을 아이에게 가르치는 것과 같다. 비지도 학습은 아이가 스스로 문제를 풀고 추론할 수 있도록 내버려두는 방식이라고 할 수 있다.*   <br/><br/>
    - **클러스터링 알고리즘(Clustering algorithms)** : 군집화 알고리즘은 분류되지 않은 데이터에서 구조나 패턴을 찾는 데 도움을 줌 하지만 그룹 간의 유사성을 과대평가할 수 있고 각 데이터 포인트를 개별적으로 다루지 못함
    - **차원 축소(Dimentionality reduction)** : 데이터 세트에서 그 특징의 수를 줄이거나 데이터 세트를 여러 구성요소로 분할함으로써 데이터를 단순화시키는 데 기여
<br/><br/><br/>

지도 학습은 각 이미지에 대한 정확한 명칭(dog, cat)이라는 정답을 맞히는 것이 목표이지만, 비지도 학습은 개, 고양이, 기린 등의 이미지에 대한 정답(명칭) 대신, 구성을 알아내 군집시킨다.
<br/><br/>
- **강화학습(Reinforcement learning)** : 보상을 최대화하는 행동 혹은 순서를 선택하는 방법   
 <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/8e145422-3fd1-4d49-a191-53b64ce1411a" width="300px" height="300px" title="px(픽셀) 크기 설정" alt=""></img><br/>
 *구글 딥마인드가 개발하 인공지능 바둑 프로그램인 알파고는 바둑(환경)을 두는 방법(행위)을 학습하기 위해서 대량의 바둑기사들의 대국을 모방학습(예비학습) 그 후, 독립적으로 자기 자시의 인스턴스를 상대로 수많은 바둑을 두며 시행착오를 거쳐 경기력을 개선하는 '강화학습'을 함. 보상을 극대화 하기위한 수를 정함*
 
<br/><br/>

<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/423c1557-d793-469c-9279-5ae07a404c64" width="500px" height="300px" title="px(픽셀) 크기 설정" alt=""></img><br/><br/><br/>
## 딥러닝(Deep Learning)
신경망(Artificial Neural Network) 구조를 취하는 머신 러닝 알고리즘
- 퍼셉트론(Perceptron)   
물학적인 신경계(Neual Network)의 기본 단위인 신경세포(=뉴런)의 동작 과정을 통계학적으로 모델링한 알고리즘
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/14f12b3e-1083-44ea-840c-7cfd38ae4ddf" width="400px" height="300px" title="px(픽셀) 크기 설정" alt=""></img>
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/559b74c2-2791-4b6b-8ea0-f30af13a1ed8" width="400px" height="300px" title="px(픽셀) 크기 설정" alt=""></img><br/>


- 단층 퍼셉트론(single-layer perceptron)   
  신경망(딥러닝)에 기원이 되는 알고리즘, 퍼셉트론은 다수의 신호를 입력으로 받아 하나의 신호를 출력하고 퍼셉트론은 이 신호를 입력으로 받아 '흐른다/안 흐른다'(1 또는 0)이라는 정보를 앞으로 전달   
  <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/fb904c06-5573-439f-94cb-81ec4cfd2a31" width="500px" height="400px" title="px(픽셀) 크기 설정" alt=""></img><br/><br/>
  논리연산의 AND, OR, NAND는 선형으로 해결 가능하지만 반면에 XOR연산의 경우에는 선형으로 분류가 불가능
  <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/0b370ac6-ea2d-4e8d-8064-c615b41b2a92" width="300px" height="150px" title="px(픽셀) 크기 설정" alt=""></img>
  <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/28fbddb2-6e11-4566-8cd4-90bda29eb9ae" width="150px" height="150px" title="px(픽셀) 크기 설정" alt=""></img><br/>
- 다층 퍼셉트론(multi layer perceptron)   
 <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/6d93b0e2-6d72-4c1d-ac85-cd8dd93bcfd2" width="500px" height="300px" title="px(픽셀) 크기 설정" alt=""></img><br/>
  다층 퍼셉트론은 단층 퍼셉트론과 달리 비선형으로 분포하는 데이터들에 대해 학습이 가능
  입력층(input layer), 은닉층(hidden layer), 출력층(output layer)
   은닉층이 1개만 있는 다층 퍼셉트론의 경우 얕은 신경망(shallow neural network), 은닉층이 2개 이상인 경우 깊은 신경망(deep neural network), 그리고 이 깊은 신경망을 학습시키는 것을 딥러닝(deep learning)이라고 한다.
    - 활성화 함수(activation function)
      데이터들은 아무리 층을 통과하여도 선형이라는 성질을 잃지 않기 때문에 층과 층 사이를 통과할때 선형 데이터를 비선형으로 바꿔주기 위해서 활성화 함수를 사용   <br/>





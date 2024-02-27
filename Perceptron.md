## 인공신경망과 퍼셉트론(Perceptron)

인공신경망은 사람의 뇌를 모방하여 인공지능을 구현하려는 컴퓨터 프로그램   </br></br>


<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/14f12b3e-1083-44ea-840c-7cfd38ae4ddf" width="600px" height="300px" title="px(픽셀) 크기 설정" alt=""></img></br>
뉴런 : 수상돌기(입력), 세포체(계산), 축삭돌기(출력), 세포체에 들어온 정보가 특정기준을 넘어서면 시냅스로 전달   </br></br>

<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/756bcb5b-344b-42af-b05e-910c73190f7f" width="300px" height="300px" title="px(픽셀) 크기 설정" alt=""></img></br>
인공신경세포 작동원리 또한 입력, 강도, 출력으로 구성되고, 임계치에따라 출력값 전송   
활성화 함수(activation function) : 입력 신호의 총합을 출력 신호로 변환하는 함수   
-> **퍼셉트론(perceptron)**

<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/a94d9517-d5b3-4ae1-8c4e-582eb8563d0c" width="400px" height="300px" title="px(픽셀) 크기 설정" alt=""></img></br>
활성화 함수로 계단함수 사용   


이러한 과정을 수식으로 나타내면   
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/eddbeb2d-1128-4383-8b3d-f3e6d72d6ba6" width="300px" height="200px" title="px(픽셀) 크기 설정" alt=""></img></br></br>


## 퍼셉트론 학습 알고리즘
인공신경망을 학습시켜 원하는값을 얻고자 함, 최적의 연결 가중치를 찾는 과정
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/773ec43d-50e7-4c6e-b1ac-0d483d8739b5" width="500px" height="300px" title="px(픽셀) 크기 설정" alt=""></img></br></br>

실제값과 예측값의 차이를 오차, 오차가 작아지도록 연결강도를 조절하는것을 학습   
새연결강도=현연결강도+현입력값×오차×학습률   
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/f73aea79-414c-4f43-b634-704ff290918a" width="500px" height="300px" title="px(픽셀) 크기 설정" alt=""></img></br>
</br>

## 퍼셉트론의한계
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/9cc8a802-0d4f-46db-9c83-e509a3097e9f" width="300px" height="200px" title="px(픽셀) 크기 설정" alt=""></img>
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/65968e2d-8bcc-4cf6-8df7-1a99e911a9c6" width="300px" height="200px" title="px(픽셀) 크기 설정" alt=""></img></br>
퍼셉트론은 선형분류기로써, 선형으로 분리되는 데이터를 잘 분리할 수 있다. XOR 해결 불가능 

## 다층신경망 등장
다층 퍼셉트론은 단층 퍼셉트론과 달리 비선형으로 분포하는 데이터들에 대해 학습이 가능 입력층(input layer), 은닉층(hidden layer), 출력층(output layer) 은닉층이 1개만 있는 다층 퍼셉트론의 경우 얕은 신경망(shallow neural network), 은닉층이 2개 이상인 경우 깊은 신경망(deep neural network), 그리고 이 깊은 신경망을 학습시키는 것을 **딥러닝(deep learning)** 이라고 한다.
<img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/6d93b0e2-6d72-4c1d-ac85-cd8dd93bcfd2" width="500px" height="300px" title="px(픽셀) 크기 설정" alt=""></img><br/><br/>
- 활성화함수 : 시그모이드함수   
  <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/9b07b97d-a333-4022-bab3-d7a3c1630d4c" width="300px" height="200px" title="px(픽셀) 크기 설정" alt=""></img><br/><br/>
- 오차 줄이기 위한 경사하강법   
  <img src="https://github.com/yuuuuuuuuna/AI/assets/87286063/4b1ae40e-e6f3-4bd0-94d7-3f0af4c691b5" width="300px" height="200px" title="px(픽셀) 크기 설정" alt=""></img><br/><br/>
- 역전파 알고리즘

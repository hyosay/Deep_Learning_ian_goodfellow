# ✍️Deep_Learning_ian_goodfellow 정리 및 공유
> 주석은 역자생각 또는 추가설명이다.

## Chapter 3
### 확률론과 정보 이론(probability theory)
##### 불확실성을 발생할 수 있는 세 가지 원천
1. 모형화할 시스템에 내재한 확률성
2. 불완전한 관측 가능성(observability)
3. 불완전한 모형화

복잡하지만 확실한 규칙보다는 간단하지만 불확실한 규칙을 사용하는것이 좀 더 실용적이다.
> 대부분의 새는 하늘을 난다. o     
> 새는 하늘은 난다. 단 다음은 예외이다. 아직 비행 방법을 배우지 못한 어린새나, 화식조나 타조 ,,, 등의 새 x

포커에서 발생할 확률 p는 **빈도론자 확률(frequentist probability; 또는 빈도주의 확률)** 이라고 부르며,    
환자를 진단하는 의사의 경우 확률은 사건의 비율이 아니라 **믿음의 정도**(degree of belief), 줄여서 **확신도**를 나타낸다.    
즉 확실성의 수준을 수치화하는 데 관련된 확률을 흔히 **베이즈 이론(Bayesian probability)** 이라고 한다.


확률론은 다른 명제들의 가능도 <sup>있을 수 있는일</sup>(likelihood)가 주어졌을 떄 어떤 명제가 참일 가능도를 결정하는 일단의 형식적인 규칙들을 제공한다.

#### 3.2 확률변수
확률변수는 이산(discrete)일 수도 있고 연속(continuous)일 수도 있다. 

어떤 함수 _p_가 확률변수 x에 대한 하나의 확률질량함수가 되려면 반드시 다음 성질들을 충족해야 한다.

<img width="274" alt="스크린샷 2021-09-15 오후 6 54 43" src="https://user-images.githubusercontent.com/46950334/133412607-58dd6835-30e4-407a-8bcb-48c22843428d.png">   

이 성질을 충족하게 만드는 것을 **정규화(normalization)** 라고 한다.
> 소프트맥스함수(softmax function)가 정규화를 하는 과정이라고 생각한다.
> 주사위 1번 던졌을떄 1 ~ 6까지 나올 확률이 각 `1/6`이다. 즉 확률의 합이 1이다.


# Chapter 4

#### 최소화 또는 최대화할 함수를 _objective function_(목적함수) 또는 _criterion_(판정기준, 표준) 이라고 부른다.
#### 최소화 경우에 _cost function_, _loss function_, _error function_ 이라고 한다.


#### _argmax_, _argmin_ 은 _function_ 이 최대 ,최소가 되게 해주는 x의 값을 나타내는 _function_ 이다.


교차검증(cross-validation)

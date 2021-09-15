# Deep_Learning_ian_goodfellow 정리 및 공유


# Chapter 3
## 확률론과 정보 이론(probability theory)
### 불확실성을 발생할 수 있는 세 가지 원천
1. 모형화할 시스템에 내재한 확률성
2. 불완전한 관측 가능성(observability)
3. 불완전한 모형화

복잡하지만 확실한 규칙보다는 간단하지만 불확실한 규칙을 사용하는것이 좀 더 실용적이다.
> 대부분의 새는 하늘을 난다. o     
> 새는 하늘은 난다. 단 다음은 예외이다. 아직 비행 방법을 배우지 못한 어린새나, 화식조나 타조 ,,, 등의 새 x

포커에서 발생할 확률 p는 **빈도론자 확률(frequentist probability; 또는 빈도주의 확률)** 이라고 부르며, 환자를 진단하는 의사의 경우 확률은 사건의 비율이 아니라 **믿음의 정도**(degree of belief), 줄여서 **확신도**를 나타낸다,즉 확실성의 수준을 수치화하는 데 관련된 확률을 흔히 **베이즈 이론(Bayesian probability)** 이라고 한다.

# Chapter 4

#### 최소화 또는 최대화할 함수를 _objective function_(목적함수) 또는 _criterion_(판정기준, 표준) 이라고 부른다.
#### 최소화 경우에 _cost function_, _loss function_, _error function_ 이라고 한다.


#### _argmax_, _argmin_ 은 _function_ 이 최대 ,최소가 되게 해주는 x의 값을 나타내는 _function_ 이다.


교차검증(cross-validation)

### 1. 머신러닝의 이해
#### 머신러닝의 3가지 형태
- Supervised Learning (지도학습) : label이 있는 형태로 학습하기
  - label = target
  - feature : 입력 변수, 특징을 가지는 변수
  - classification problem : discrete(non-continuous) label
  - regression problem : continuous label
- Unsupervised Learning (비지도학습) : label을 고려하지 않은 학습
  - D = {(x)} 의 형태
  - 차원 축소(dimension reduction), 군집화(clustering)
- Reinforcement Learning (강화학습)
  - 시스템의 동작의 적절성 (right/wrong)에 대한 피드백이 있는 학습

#### Scikit-learn 소개
- numpy, Scipy가 포함되어 있음. 머신 러닝용 라이브러리
- 아래와 같은 기능을 포함함
  - Data 예제
  - 데이터 전처리 관련 함수(preprocessing)
  - 지도/비지도학습
  - 모형 평가 및 선택 (evaluation and selection)

- Scikit-learn이 제공하는 알고리즘
![](.\ml_map.svg)


---

### 2. Data Load

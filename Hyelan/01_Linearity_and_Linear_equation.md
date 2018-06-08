## 01강. 선형성 정의 및 1차 연립방정식 의미

### 00. Linearity 선형성

- Linearity 행렬로 표현되는 것이 기본적으로 선형성을 만족해야 함
    - $$f(x), x라는 변수에 대해서 function/operation 을 가지느냐 $$
    
- 조건 2가지를 만족할 때 Linearity 성립
    - 1. Superposition(중첩의 원리) : $$f(x_{1}+x_{2}) = f(x_{1}) + f(x_{2})$$
    - 2. Homogeniety $f(ax) = af(x)$ , a는 constant 
    - $f(a_{1}x_{1}+a_{2}x_{2})=a_{1}f(x_{1})+a_{2}f(x_{2})$ : 이 조건을 만족할 때 선형성이 있다고 함, 이런 것들 선형대수에서 다룬다.

- $ y = mx = f(x) $ : 위 두 조건을 만족하며 linear 하다
- $ y = mx + n $ : 원점을 지나지 않는 직선은 x와 y사이에 linearity 가 존재하지 않음, linear equation이라고 다 linearity를 가지는 것은 아니다. 하지만 변화량에는 선형성이 존재

- operation의 linearity : differentiation, integration
    - $x_{1}(t) x_{2}(t) 에 대한 diff, inte 알아보자 : \frac{d}{dt}(a_{1}x_{1}(t)+a_{2}x_{2}(t)) = a_{1}frac{d}{dt}x_{1}(t)+a_{2}frac{d}{dt}x_{2}(t)$
    - integration 해도 마찬가지로 만족된다.
    - 미분 적분 linearity 가지기 때문에 매트릭스 폼으로 바꿔서 연산 수행 가능

- matrix의 linearity : 행렬 A에 벡터 x_{1}, x_{2}을 곱할 때 새로운 형태의 벡터 y가 나오는데
    - A(a_{1}x_{1}+a_{2}x_{2}) = a_{1}Ax_{1} + a_{2}Ax_{2}


### Before getting started : Basic Notations of Matrix

Vector v = (a, b, c) 

\begin{align}
    v &= \begin{bmatrix}
           a \\
           b\\
           c
         \end{bmatrix}
  \end{align}
    
    
    
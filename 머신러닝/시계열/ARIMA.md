# ARIMA(Autoregressive Integrated Moving average Model)

## 1. AR(AutoRegressive) model
- 자기 회귀 모형
- 과거 시점의 자기 자신의 data가 현 시점의 자기 자신에게 영향을 미치는 모형
- AR(p) : p는 차수로 현재 시점부터 과거 p개 이전 시점까지의 데이터 영향도를 봄
- $X(t) = w \times X(t-1) + u \times e(t)$
- 현재 시점 t에 대한 data는 이전 시점의 자기 data에 가중치 w를 곱하고 상수 b를 더하는 회귀식과 오류항인 e(t)에 가중치 u를 곱한 것을 더해서 표현
- e(t) : white-noise. 일반적인 정규분포에 도출된 random noise
- 정상성 조건을 위해 일종의 whitening
- 추세가 변하는 상황에서는 적합하지 않음
-  

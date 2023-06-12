# Regression-Bland-Altman-Plot

### Bland-Altman Plot 
true 값과 predict 값의 관계 시각화
regression model이 예측한 값이 일관성 있는지 시각적으로 평가

x축(mean) : mean(true, pred)
y축(difference) : true - pred
계산된 값에 대한 선형회귀선과 95% 신뢰구간 (confidence interval)

high negative diff : over-estimating
high positive diff : under-estimating


### Reference
- Deep Learning Algorithms for Predicting Breslow Thickness from Dermoscopic Images of Acral Lentiginous Melanomas (https://doi.org/10.1016/j.jid.2021.12.033)
- figure 1d

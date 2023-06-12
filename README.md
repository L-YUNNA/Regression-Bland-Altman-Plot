# Regression-Bland-Altman-Plot

![image](https://github.com/L-YUNNA/Regression-Bland-Altman-Plot/assets/129636660/fce3c964-f32c-47db-bd91-9e1e8ab2f8f6)

## Bland-Altman Plot
- true 값과 predict 값의 관계 시각화
- regression model이 예측한 값이 일관성 있는지 시각적으로 평가


x축(mean) : mean(true, pred)<br>
y축(difference) : true - pred<br>
계산된 값에 대한 선형회귀선과 95% 신뢰구간 (confidence interval)<br>

**high negative diff : over-estimating<br>
**high positive diff : under-estimating<br>



## Reference
- [Deep Learning Algorithms for Predicting Breslow Thickness from Dermoscopic Images of Acral Lentiginous Melanomas](https://doi.org/10.1016/j.jid.2021.12.033)

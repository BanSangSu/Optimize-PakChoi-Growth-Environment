# Optimize-PakChoi-Growth-Environment
## Optimize Growth Environment Competition at KIST강릉분원

<2022.04.18 ~ 2022.05.20 16:59>
https://dacon.io/competitions/official/235897/overview/description

청경채의 성장도를 예측.

110th 😜
***
## Summary
1. Regnet을 사용하였지만 data의 특성을 파악하지 못하여 그에 알맞게 값을 제공하지 않아 원하는 성능을 발휘하지 못했다.
2. Lamb, AdamW, AdamP optimizer를 사용했다. 그 중 AdamP가 제일 안정적인 성능을 보였다.


## Feature
1. 8개의 model씩 ensemble하여 결과로 사용했다.
2. Regression보다 recognition에 특화된 model.

## To do
1. EDA를 통하여 data의 특징 파악하기.
2. Preprocessing을 통하여 EDA에서 나온 결과에 맞게 모델 변형(Regression에 맞게)시키기.

## P.S.
- Data in drive: 3526
- Data CASE59는 중복 및 오류를 가지고 있다(제거하고 사용하기).
- Pretrained models: 3526
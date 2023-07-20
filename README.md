# Optimize Growth Environment Competition

- **Organiser**: KIST(Korea Institute of Science and Technology) Gangneung
- **Period**: 18th Apr - 20th May, 2022

https://dacon.io/competitions/official/235897/overview/description

## Subject
### Leaf area prediction algorithm using pak choi pictures and environmental data.  
(청경채 사진과 환경 데이터를 활용한 잎면적 예측 알고리즘 개발)  

110th 😜

## Summary
1. **Regnet** was used, but it did not identify features of the data, so that did not provide correct output. Consequently, we did not achieve the desired performance. 
2. We used Lamb, AdamW, and AdamP optimisers, of which AdamP had the most stable performance.


## Feature
1. We **ensembled** 8 models and used them as results.
2. This model specialises in recognition rather than regression

## To do
1. Identify the features of pak choi pictures and environmental data with EDA.
2. Make our model suitable for regression (not recognition) based on the EDA results.  
   (The best model in this competition was **Polynomial regression**)

## P.S.
- Data CASE59 has duplicates and errors (remove and used the dataset).
- Data in drive: 3526
- Pretrained models: 3526

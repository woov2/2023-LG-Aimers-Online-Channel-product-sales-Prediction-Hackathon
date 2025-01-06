# LG Aimers 온라인 채널 제품 판매량 예측 AI 온라인 해커톤
2023-LG-Aimers-Online-Channel-product-sales-Prediction-Hackathon

<br/>

## 1. 배경 & 목적

- 현대 디지털 시대에 들어, 온라인 판매는 상품과 서비스를 전달하는 핵심 채널로 자리매김.
- 이러한 변화와 함께, 온라인 판매 채널에서 수집되는 대규모 데이터는 더 이상 그저 정보의 한 형태가 아닌, 온라인 판매 환경에서 귀중한 통찰력을 얻는데 있어 중요한 자산임.
- 이런 데이터를 활용해 빠르고 정확한 판매 예측을 수행하는 것은, 기업들이 효율적인 재고 관리를 하고, 타겟 마케팅 전략을 세우는데 필수적.
- 온라인 채널 제품 판매량 예측 AI 모델 개발.
- 평가 지표: SFA

<br/>

## 2. 주최/주관 & 참가 대상 & 성과

- 주최/주관: LG AI Research / DACON
- 후원: 한경닷컴
- 참가 대상: LG Aimers 교육생이라면 누구나
- 성과: 상위 1%

<br/>

## 3. 대회 기간

- 제출마감: 2023년 08월 28일
- 코드 평가 마감 및 최종순위 발표: 2023년 09월 08일

<br/>

## 4. 내용
- 온라인 채널 별 판매량의 추이가 서로 상이함.
- 0값이 매우 많은 sparse한 데이터 특성을 지님.
- Data Structure 변형을 통한 ML Modeling.
- Prophet / nhits 시계열 모델을 활용한 Modeling.
- Post Processing

<br/>

## 5. Process

### ch.1 Feature Engineering

- EDA

---

### ch.2 Preprocessing

- Item Category based 0 values Imputation
- Channel Transition based values Combination 

---

### ch.3 Modeling

- LGBM
- Prophet
- LSTM
- nhits

---

### ch.4 Ensemble

- loss function
- Weighted Ensemble(ML 0.3 / DL 0.7)

<br/>

## 6. 참고자료

[LG Aimers 온라인 채널 제품 판매량 예측 AI 해커톤 사이트](https://dacon.io/competitions/official/236129/overview/description)

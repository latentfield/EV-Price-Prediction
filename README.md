# EV Price Prediction Project

### Project Overview
- **목표**: 중고 전기차의 제원 데이터를 바탕으로 합리적인 중고 가격을 예측하는 모델 개발
- **Goal**: Develop a model to predict used EV prices based on vehicle specification data.

### Tech Stack
- **Language**: Python
- **Libraries**: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn

### Key Contributions
1. **Critical Data Analysis**: 배터리 용량 등 핵심 변수의 결측치를 분석하고 데이터 간의 상관관계 파악
   - Analyzed missing values in key variables (e.g., battery capacity) and identified correlations.
2. **Modeling**: RandomForestRegressor를 활용하여 비선형적인 가격 데이터 학습
   - Trained a RandomForestRegressor to capture non-linear relationships in price data.
3. **Evaluation**: RMSE 지표를 활용하여 모델의 예측 오차 최적화
   - Optimized prediction errors using the RMSE metric.

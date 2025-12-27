# Exam Score Prediction 🐟

**Author:** mathefishian  
**Dataset:** [Exam Score Prediction Dataset](https://www.kaggle.com/datasets/kundanbedmutha/exam-score-prediction-dataset) (Kaggle) – synthetic data (AI-generated)

### Project Overview
This project demonstrates a complete end-to-end machine learning pipeline for predicting student exam scores based on study habits, attendance, sleep, and other factors.

Key steps:
- **Exploratory Data Analysis (EDA)** – visualizations, correlations, insights.
- **Data Preprocessing** – handling categorical features (One-Hot Encoding), scaling numerical features.
- **Modeling** – baseline Linear Regression vs Random Forest Regressor.
- **Evaluation** – RMSE, MAE, R² metrics + prediction visualizations.
- **Simple baseline** – single-feature model (study_hours only) for interpretability.

### Key Findings
- `study_hours` is the strongest predictor (correlation 0.72 with exam_score).
- Even a simple Linear Regression using only study_hours achieved R² = 0.525.
- Full Linear Regression model achieved the best performance (R² ≈ 0.733).
- Random Forest slightly underperformed – likely due to the synthetic and mostly linear nature of the data.

### Notes
The dataset is synthetic (perfect distributions, no outliers, no missing values), making it great for learning ML techniques but less representative of real-world messiness.

### Tech Stack
- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn (pipelines, preprocessing, models)

Feel free to star ⭐ or fork – feedback welcome!  
Swim through the integrals with me 🐟

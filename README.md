# Insurance Premium Prediction using Regression Models
## Overview
This project aims to predict **insurance premium amounts** using machine learning regression
techniques.
It leverages advanced models to accurately estimate premiums from various customer and policy
attributes.
The notebook explores multiple regression models, ultimately selecting **XGBoost Regressor** for its
superior performance and robustness on large, skewed datasets.
## Project Highlights
- **Goal:** Predict the insurance premium amount.
- **Dataset:** Kaggle Insurance Premium Dataset.
- **Dataset Link:** [Insurance Premium Forecasting
Challenge](https://www.kaggle.com/competitions/insurance-premium-forecasting-challenge/overview)
- **Best Model:** XGBoost Regressor.
- **Evaluation Metric:** Root Mean Squared Logarithmic Error (RMSLE).
- **Final Score:** **1.05 RMSLE**.
## Workflow
1. **Data Exploration & Cleaning**
- Handled missing values and outliers.
- Performed exploratory data analysis (EDA) to understand feature relationships.
2. **Feature Engineering**
- Encoded categorical features.
- Applied log transformation to the target variable to handle skewness.
3. **Model Training**
- Compared multiple regression models.
- Fine-tuned hyperparameters for optimal results.
- Chose XGBoost for its speed and accuracy.
4. **Evaluation**
- Used RMSLE to measure relative prediction accuracy.
- Ensured model generalization through validation.
## Technologies Used
- **Python**
- **NumPy**, **Pandas** — Data handling
- **Matplotlib**, **Seaborn** — Visualization
- **Scikit-learn** — Preprocessing & metrics
- **XGBoost** — Model training
- **Kaggle Notebooks** — Development environment
## How to Run
1. Clone this repository:
git clone https://github.com//insurance-premium-prediction.git
cd insurance-premium-prediction
2. Install dependencies:
pip install -r requirements.txt
3. Open the Jupyter notebook:
jupyter notebook 60017230100-jagdishchoudhary.ipynb
4. Run all cells to reproduce results.
## Results
| Model | Metric | Score |
|--------|---------|--------|
| XGBoost Regressor | RMSLE | **1.05** |
## Future Improvements
- Experiment with ensemble and stacking techniques.
- Use deep learning-based regression (e.g., FusionNet).
- Apply feature selection or SHAP for interpretability.
## Acknowledgments
- **Dataset Source:** [Kaggle - Insurance Premium Forecasting
Challenge](https://www.kaggle.com/competitions/insurance-premium-forecasting-challenge/overview)
- Special thanks to Kaggle community for resources and inspiration.
## Author
**Jagdish Choudhary**
Machine Learning & Data Science Enthusiast

# Kaggle--Getting-Started-Prediction-Competition-House-Prices---Advanced-Regression-Techniques
I'm just making a simple record of my first competing on Kaggle
# Kaggle House Prices Prediction - Top 10% Solution (Rank 445)

![Python](https://img.shields.io/badge/Python-3.12-blue.svg)
![Kaggle](https://img.shields.io/badge/Kaggle-Top%2010%25-orange.svg)

📌 Project Summary
This repository contains my solution for the Kaggle House Prices competition. 
Achieved a final RMSE of **0.12218**, ranking **445/5000+** (Top 9%).

## 🛠️ Key Engineering Features
- **Robust Pipeline**: Automated numeric/categorical type enforcement to prevent data drift errors.
- **Advanced FE**: Box-Cox transformation for skewed features and domain-specific feature construction.
- **Ensemble Architecture**: A weighted blend of LightGBM (Native Categorical support), CatBoost, and Lasso Regression.

## 📈 Evolution Path
| Version | Strategy | CV Score | Rank |
| :--- | :--- | :--- | :--- |
| v1 | Baseline Linear | 0.132 | 1900+ |
| v2 | FE + Outlier Removal | 0.123 | 675 |
| v3 | **LGBM + Ensemble Blend** | **0.119** | **445** |

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `House_Price_Prediction.ipynb`

# Home Credit Default Risk - Loan Repayment Prediction

This project predicts the likelihood of a client defaulting on a loan using real-world financial data from Home Credit. It involves data preprocessing, model training, benchmarking, and explainability using SHAP.

## Project Highlights

- Data from multiple sources (`application_train`, `bureau`, `previous_application`, etc.)
- Extensive preprocessing and feature engineering
- Model: CatBoost Classifier (Gradient Boosting)
- Baseline comparison with Logistic Regression(up c)
- Model interpretability using SHAP (SHapley Additive Explanations)(UP C)
- Evaluation metric: AUC-ROC

## Dataset

> The dataset used in this project is part of a Kaggle competition and may require you to accept terms of use before accessing.

🔗 [Kaggle Competition: Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/data)

## Files in this Repo

- `home_credit_default_notebook.ipynb` – End-to-end notebook with all analysis, model building, and SHAP explainability
- `README.md` – This file

## Tools Used

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, CatBoost, SHAP
- Jupyter Notebook

## Key Takeaways

- Benchmarked CatBoost model significantly outperformed Logistic Regression
- SHAP analysis revealed features like `EXT_SOURCE`, `DAYS_BIRTH`, and `CREDIT_TERM` as major contributors
- Interpretable models are crucial in financial decision-making environments

---

Feel free to fork, star, or use this as a reference for your own modeling projects!

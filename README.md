# Credit-Risk-Strategy-Amex-Data-

💳 Credit Risk Modeling with XGBoost
This repository contains the complete workflow for a Credit Risk Modeling project using real-world inspired data, performed as part of an advanced machine learning case study. The goal is to predict customer default likelihood using historical transaction and behavior data.

📁 Project Files
CREDIT RISK STRATEGY - AMEX.ipynb
→ A Jupyter Notebook that includes the full data pipeline:

Data loading in chunks

Feature engineering and one-hot encoding

Aggregation at customer level

Model training using XGBoost

Evaluation via AUC on Train and Test sets

Hyperparameter tuning with Grid Search

Credit Risk Strategy- Amex.pptx
→ A visually engaging presentation summarizing the project:

Business motivation

Data and feature explanation

Modeling results

Comparison of XGBoost and Neural Network models

Final recommendation and strategic use cases

🧠 Key Techniques Used
Pandas chunked data processing for large datasets

One-hot encoding of categorical features

Aggregation by customer ID

Model selection based on average AUC and variance

SHAP values for feature importance interpretation

Grid search with cross-validation for hyperparameter tuning

✅ Outcomes
XGBoost outperformed Neural Network models in AUC across training and test samples.

Grid search helped in balancing performance and overfitting.

The model can support both conservative and aggressive credit approval strategies based on default probability thresholds.

📌 How to Use
Run the Jupyter Notebook: CREDIT RISK STRATEGY - AMEX.ipynb
Ensure required libraries like xgboost, pandas, and sklearn are installed.

View the summary presentation: Credit Risk Strategy- Amex.pptx
Ideal for showcasing to stakeholders or including in a project report.

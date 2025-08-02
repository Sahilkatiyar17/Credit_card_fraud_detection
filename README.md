### 📦 Dataset

The dataset `creditcard.csv` is not included in this repository due to size limitations.

You can download it from [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
After downloading, place the file in the `data/` directory.

🧠 Credit Card Fraud Detection – Machine Learning Project
This project focuses on detecting fraudulent transactions using machine learning models. The dataset used is a publicly available credit card fraud dataset from Kaggle, which contains anonymized features (V1–V28) due to confidentiality.

🔍 Project Highlights:
Goal: Build a binary classifier to accurately identify fraudulent credit card transactions.

Dataset: Highly imbalanced (fraudulent cases make up ~0.17% of the total). Includes anonymized PCA-transformed features, Time, Amount, and Class (target).

Tools Used:

Python (Google Colab)

Scikit-learn

XGBoost

Random Forest

Optuna (for hyperparameter tuning)

Matplotlib, Seaborn (for EDA and visualization)

⚙️ Workflow:
Data Loading & Exploration: Loaded the dataset, analyzed class imbalance, feature distribution, and data quality.

Preprocessing: Scaled features and prepared them for modeling.

Model Training: Trained initial models using RandomForest and XGBoost.

Model Evaluation: Observed underperformance in initial results (accuracy & F1 score).

Hyperparameter Tuning: Used Optuna to fine-tune XGBoost and RandomForest models to improve precision, recall, and F1 score.

Evaluation Metrics: Accuracy, Confusion Matrix, Precision, Recall, and F1 Score were used to assess model performance.

You can also add the following optional sections based on how complete your project is:

📌 Key Learnings (optional):
Importance of handling class imbalance in fraud detection.

Understanding how XGBoost’s learning rate controls each tree’s contribution instead of convergence speed.

Realized the risk of data leakage when performing PCA or scaling before train/test split.

Learned how hyperparameter tuning with Optuna can significantly improve performance.

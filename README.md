# AI/ML Learning Repository

Welcome to my AI/ML learning journey repository. This will be a collection of practical, hands-on notebooks covering major topics in AI, ML, and MLOps — one topic at a time.

---

## ✅ Topic 1: Hyperparameter Tuning with GridSearchCV + MLflow  
**Notebook:** `1_gridsearch.ipynb`

In this notebook, I demonstrate how to use **GridSearchCV** for hyperparameter tuning on the Iris classification problem using a `LogisticRegression` model. The entire training process is integrated with **MLflow**, enabling experiment tracking and model versioning.

### 🔍 Key Highlights:
- Logistic Regression on the Iris dataset
- GridSearchCV for hyperparameter optimization
- MLflow tracking for:
  - Parameters and metrics
  - Model and model signature
  - Reproducibility and version control
- Loading and using the best model from MLflow

### 📦 Tools Used:
- Python
- Scikit-learn
- Pandas
- MLflow

---

## ✅ Topic 2: House Price Prediction with MLflow & Hyperparameter Tuning
In this notebook (**2_house_price_predict.ipynb**), we built a regression model to predict house prices using Random Forest Regressor and logged the entire ML pipeline using MLflow.

### Key Highlights:

- Used train_test_split to split the dataset into train and test sets.
- Applied GridSearchCV for hyperparameter tuning with a custom parameter grid.
- Tracked model experiments, hyperparameters, and metrics (like MSE) with MLflow.
- Leveraged infer_signature() to capture input-output schema of the model.
- Conditionally registered the trained model based on the tracking store type.

### ✅ MLflow Features Used:
- mlflow.log_param
- mlflow.log_metric
- mlflow.sklearn.log_model
- mlflow.set_tracking_uri
- infer_signature.

---

This is just the beginning. More topics will be added soon, covering everything from model deployment to MLOps pipelines.

Stay tuned!

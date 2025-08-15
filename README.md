# KNN Regression on California Housing Dataset

## 📌 Overview
This project demonstrates the implementation of the **K-Nearest Neighbors (KNN) Regression** algorithm on the California Housing dataset to predict median house values. It includes data preprocessing, hyperparameter tuning using GridSearchCV, and evaluation with RMSE and R² score.

## 📂 Dataset
- **Source**: `sklearn.datasets.fetch_california_housing()`
- **Samples**: ~20,640
- **Features**: 8 numeric features (e.g., median income, average rooms, population, etc.)
- **Target**: Median house value (in $100,000s)

## 🛠 Steps Performed
1. **Import Libraries**
2. **Load Dataset**
3. **Split Data** into train and test sets
4. **Feature Scaling** using StandardScaler
5. **Model Training** with `KNeighborsRegressor`
6. **Hyperparameter Tuning** using GridSearchCV:
   - Tested different `n_neighbors`, `weights`, and `metric`
7. **Model Evaluation**:
   - Root Mean Squared Error (RMSE)
   - R² Score

## 📊 Evaluation Results
- **Best Parameters**:  
  ```python
  {'metric': 'manhattan', 'n_neighbors': 9, 'weights': 'distance'}

RMSE: 0.6016

R² Score: 0.7238

🚀 How to Run

Clone the repository:

git clone https://github.com/ishanegi5/knn_regression_california_housing.git
cd knn_regression_california_housing

Install dependencies:
pip install scikit-learn pandas numpy

Run the notebook or script:
jupyter notebook

or

python knn_regression.py


📌 Dependencies

Python 3.x

scikit-learn

pandas

numpy

📜 License

This project is open-source and available under the MIT License.

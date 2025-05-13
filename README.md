# Superconductivity Prediction with Machine Learning and PySpark

This project focuses on predicting the critical temperature of superconductors using traditional machine learning and distributed big data approaches.

## Project Tasks

### Task 1: Scikit-learn Pipeline
- Built models using Linear Regression, Polynomial Regression, and Random Forest in Scikit-learn.
- Implemented custom feature engineering with interaction and quadratic terms.
- Applied stratified sampling and log transformation for balanced training.
- Used GridSearchCV and RandomizedSearchCV for hyperparameter tuning.
- Evaluated models using RMSE and R² metrics.

### Task 2: PySpark Pipeline
- Processed the same dataset using PySpark for scalable distributed training.
- Handled missing values, feature engineering, and scaling using Spark ML.
- Trained Linear, Polynomial (with expansion), and Random Forest models using PySpark MLlib.
- Performed cross-validation with ParamGridBuilder for hyperparameter tuning.
- Visualized and compared model performance before and after tuning.

## Results
- Random Forest outperformed all other models in both Scikit-learn and PySpark environments.
- Polynomial Regression showed the most improvement after tuning.
- Linear Regression had stable but lower performance compared to ensemble methods.

## Technologies Used
- Python, Scikit-learn, PySpark, Pandas, NumPy, Matplotlib, Seaborn

## How to Run
For Task 1:
```
pip install -r requirements.txt
Open BigDataMining_Task1.ipynb and run all cells in Jupyter.
```

For Task 2:
```
pip install pyspark
Open BigDataMining_Task2.ipynb in Google Colab (GPU not required) or your PySpark environment.
```

---

## Author

**Shin Than Thar Aung**

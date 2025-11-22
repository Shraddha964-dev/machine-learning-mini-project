# 🏠 House Price Prediction

This project demonstrates a complete machine learning pipeline to predict Boston house prices using popular ML algorithms such as Linear Regression and XGBoost. The project includes data loading, preprocessing, model training, evaluation, and prediction.

---

## 📂 Project Structure
project/
│
├── notebooks/
│ └── Project_4_House_Price_Prediction.ipynb
│
├── src/
│ ├── data_preparation.py
│ ├── model_training.py
│ └── evaluation.py
│
├── data/
│ ├── raw/
│ └── processed/
│
├── results/
│ ├── plots/
│ └── models/
│
├── requirements.txt
└── README.md

---

## 📘 Dataset

This project uses the **Boston House Price dataset** from `sklearn.datasets`.

Features include:
- CRIM
- ZN  
- INDUS  
- RM  
- AGE  
- DIS  
- TAX  
- PTRATIO  
- etc.

Target variable:
- **MEDV (Median House Value)**

---

## 🚀 Steps Performed

### **1. Importing Dependencies**
- numpy  
- pandas  
- matplotlib  
- seaborn  
- sklearn  
- xgboost  

### **2. Loading Dataset**
```python
from sklearn.datasets import load_boston
```

3. DataFrame Creation

Converted dataset into a pandas DataFrame and added price as the target column.

4. Data Analysis

head(), shape(), describe()

null value checks

correlation matrix

distribution plots

5. Train-Test Split

from sklearn.model_selection import train_test_split

6. Model Training

Linear Regression

XGBoost Regressor

7. Evaluation

Metrics used:

MAE

MSE

RMSE

R² Score

8. Prediction

Predicting house price from user input feature values.

📦 Installation

pip install -r requirements.txt


Run the notebook:

jupyter notebook

🧠 Requirements
numpy
pandas
scikit-learn
matplotlib
seaborn
xgboost

📊 Results

The XGBoost model performed better than Linear Regression based on MAE, RMSE, and R² score.

🤝 Contributing

Feel free to fork the repo and submit pull requests.

📄 License

This project is open-source and free to use.


---

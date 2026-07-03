# Customer Churn Prediction

## About the Project

This project predicts whether a telecom customer is likely to leave the company or continue using its services.

I built this project to understand the complete machine learning workflow, starting from data cleaning to making predictions using different machine learning models.

---

## Dataset

- Dataset: Telco Customer Churn Dataset
- Total Records: 7043
- Total Features: 21
- Target Column: Churn

The dataset contains customer details like gender, tenure, internet service, contract type, monthly charges, payment method and whether the customer has churned or not.

---

## What I Did

- Cleaned the dataset
- Handled missing values
- Explored the data using a few visualizations
- Converted categorical data into numerical values
- Split the dataset into training and testing data
- Trained multiple machine learning models
- Compared the model performance
- Used the best model to predict customer churn

---

## Machine Learning Models

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

Among these models, **Random Forest** gave the best result on this dataset.

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Project Structure

```text
Customer-Churn-Predictor/

├── 01_Data_Cleaning.ipynb
├── 02_EDA.ipynb
├── 03_Preprocessing.ipynb
├── 04_Model_Building.ipynb
├── 05_Model_Evaluation.ipynb
├── 06_Prediction.ipynb

├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── cleaned_customer_churn.csv

├── X_train.npy
├── X_test.npy
├── y_train.npy
├── y_test.npy

├── scaler.pkl
├── logistic_regression.pkl
├── decision_tree.pkl
├── random_forest.pkl
├── knn.pkl

├── requirements.txt
├── README.md
└── .gitignore
```

---

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Customer-Churn-Predictor.git
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter Notebook or VS Code.

4. Run the notebooks in this order:

- 01_Data_Cleaning.ipynb
- 02_EDA.ipynb
- 03_Preprocessing.ipynb
- 04_Model_Building.ipynb
- 05_Model_Evaluation.ipynb
- 06_Prediction.ipynb

---

## Future Improvements

- Try more machine learning models.
- Improve accuracy by tuning model parameters.
- Deploy the project using Streamlit or Flask.

---

## Author

**Y. Phani Sravan**

B.Tech (CSE - AI & ML)

Sasi Institute of Technology and Engineering
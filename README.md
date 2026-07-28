# Employee Attrition Prediction Using Machine Learning

## 📌 Project Overview

Employee Attrition Prediction is a Machine Learning project that predicts whether an employee is likely to leave a company based on various factors such as salary, overtime, job satisfaction, work-life balance, and years at the company.

This project uses the IBM HR Analytics Employee Attrition Dataset and a Random Forest Classifier to identify employees who may be at risk of leaving the organization.

---

## 🎯 Objectives

- Analyze employee data and identify factors affecting attrition.
- Build a Machine Learning model to predict employee attrition.
- Visualize important employee trends using data analysis.
- Deploy the model using Streamlit for real-time predictions.

---

## 📊 Dataset

Dataset: IBM HR Analytics Employee Attrition & Performance Dataset

Number of Records: 1470

Number of Features: 35

Target Variable:
- Attrition (Yes / No)

Important Features Used:
- Age
- DistanceFromHome
- JobSatisfaction
- MonthlyIncome
- OverTime
- YearsAtCompany
- YearsSinceLastPromotion
- WorkLifeBalance

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Streamlit
- Git & GitHub

---

## 🤖 Machine Learning Model

Algorithm Used:

- Random Forest Classifier

Why Random Forest?

- High accuracy
- Handles non-linear relationships
- Reduces overfitting
- Provides feature importance

---

## 📈 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Data Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Saving
10. Streamlit Deployment

---

## 📊 Model Evaluation

Evaluation Metrics:

- Accuracy Score
- Confusion Matrix
- Classification Report

Expected Accuracy:

85% – 92%

---

## 📂 Project Structure

Employee-Attrition-Prediction/

├── app.py

├── employee_attrition_model.pkl

├── label_encoder.pkl

├── employee_attrition_cleaned.csv

├── WA_Fn-UseC_-HR-Employee-Attrition.csv

├── requirements.txt

├── README.md

└── screenshots/

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/Employee-Attrition-Prediction.git
```

### Move to Project Folder

```bash
cd Employee-Attrition-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Streamlit Application

```bash
streamlit run app.py
```

---

## 🖥 Streamlit Features

- User-friendly interface
- Employee attrition prediction
- Real-time input handling
- Instant prediction results

---

## 📌 Sample Prediction Inputs

| Feature | Example |
|----------|----------|
| Age | 28 |
| DistanceFromHome | 15 |
| JobSatisfaction | 2 |
| MonthlyIncome | 3500 |
| OverTime | Yes |
| YearsAtCompany | 2 |
| YearsSinceLastPromotion | 0 |
| WorkLifeBalance | 2 |

Output:

Employee likely to leave the company

or

Employee likely to stay in the company

---

## 📚 Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- Power BI dashboard integration
- Cloud deployment
- Real-time HR analytics

---

## 👨‍💻 Author

Lovely Jerry

B.E. Electronics and Communication Engineering (ECE)

Machine Learning & Data Analytics Enthusiast

---

## ⭐ Acknowledgements

IBM HR Analytics Employee Attrition Dataset

Scikit-Learn Documentation

Streamlit Documentation

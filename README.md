````markdown
# Employee Attrition Prediction using Machine Learning

## 📌 Project Overview

Employee attrition is one of the biggest challenges faced by organizations, leading to increased recruitment costs, training expenses, and reduced productivity.

This project aims to build a **Machine Learning model** that predicts whether an employee is likely to leave the company based on factors such as:

- Job Satisfaction
- Monthly Salary
- Work-Life Balance
- Years at Company
- Overtime
- Job Role
- Department
- Other HR-related attributes

The project uses the **IBM HR Analytics Employee Attrition & Performance Dataset** and applies data preprocessing, exploratory data analysis (EDA), multiple machine learning models, and model evaluation to identify the key drivers of employee attrition.

The insights generated can help HR teams implement proactive employee retention strategies.

---

# 🎯 Objectives

- Load and explore the HR Analytics dataset.
- Clean and preprocess the data.
- Perform Exploratory Data Analysis (EDA).
- Train and compare multiple Machine Learning models.
- Evaluate models using different performance metrics.
- Identify the most important factors affecting employee attrition.
- Provide actionable HR recommendations.

---

# 📂 Dataset

**Dataset Name:** IBM HR Analytics Employee Attrition & Performance

- Total Records: **1470**
- Features: **35**
- Target Variable: **Attrition (Yes/No)**

**Dataset Link**

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

# 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📊 Project Workflow

## 1️⃣ Data Loading & Exploration

- Loaded dataset using Pandas
- Explored dataset shape and structure
- Identified numerical and categorical features
- Calculated attrition rate
- Checked duplicate records
- Checked missing values

---

## 2️⃣ Data Preprocessing

- Removed unnecessary columns
- Converted target variable into binary format
- Applied One-Hot Encoding
- Standardized numerical features using StandardScaler

---

## 3️⃣ Exploratory Data Analysis (EDA)

- Attrition by Department
- Attrition by Job Role
- Monthly Income vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition
- Correlation Analysis
- Overtime Analysis

---

## 4️⃣ Machine Learning Models

The following classification models were trained:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 5️⃣ Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

---

# 📈 Visualizations

The project includes:

- 📊 Attrition Rate by Department
- 📊 Attrition Rate by Job Role
- 📊 Monthly Income vs Attrition (Box Plot)
- 📊 Confusion Matrix
- 📊 Top 10 Feature Importances
- 📊 ROC Curve Comparison

---

# 💡 Key Business Insights

- Approximately **16%** of employees left the company.
- The **Sales Department** had the highest attrition rate.
- **Sales Representatives** and **Laboratory Technicians** experienced the highest turnover.
- Employees working **overtime** were significantly more likely to leave.
- Lower monthly income was associated with higher attrition.
- Most employees resigned within their first few years at the company.

---

# 📌 HR Recommendations

- Improve employee engagement during the first three years.
- Reduce excessive overtime.
- Prioritize retention efforts for high-risk departments.
- Review compensation and employee recognition programs.
- Use predictive analytics to identify at-risk employees.

---

# 📁 Project Structure

```text
employee-attrition-prediction-ml/
│
├── analysis.ipynb
├── HR_Attrition.csv
├── summary.pdf
├── README.md
└── charts/
    ├── chart1_department_attrition.png
    ├── chart2_jobrole_attrition.png
    ├── chart3_income_boxplot.png
    ├── chart4_confusion_matrix.png
    ├── chart5_feature_importance.png
    └── chart6_roc_curve.png
````

---

# 🚀 How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/employee-attrition-prediction-ml.git
```

### Navigate to the project directory

```bash
cd employee-attrition-prediction-ml
```

### Install the required libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **analysis.ipynb** and run all the cells.

---

# 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 🎓 Learning Outcomes

This project demonstrates practical experience in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning
* Model Evaluation
* Data Visualization
* HR Analytics
* Business Insight Generation

---

# 👩‍💻 Author

**Anushka**

B.Tech Computer Science Engineering (Artificial Intelligence)

**Interests**

* Data Analytics
* Machine Learning
* Artificial Intelligence
* Business Intelligence

---

# ⭐ Acknowledgements

* IBM HR Analytics Dataset
* Kaggle
* Scikit-learn Documentation
* Pandas Documentation
* Matplotlib Documentation
* Seaborn Documentation

---

## ⭐ If you found this project useful, consider giving it a Star!

```
```

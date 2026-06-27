Employee Attrition Prediction using Machine Learning
📌 Project Overview

Employee attrition is one of the biggest challenges faced by organizations, leading to increased recruitment costs, training expenses, and reduced productivity. This project aims to build a Machine Learning model that predicts whether an employee is likely to leave the company based on factors such as job satisfaction, salary, work-life balance, years at the company, overtime, and other HR-related attributes.

The project uses the IBM HR Analytics Employee Attrition & Performance dataset and applies data preprocessing, exploratory data analysis (EDA), multiple classification algorithms, and model evaluation to identify the key drivers of employee attrition. The insights generated can help HR teams implement proactive employee retention strategies.

🎯 Objectives
Load and explore the HR analytics dataset.
Clean and preprocess the data for machine learning.
Perform Exploratory Data Analysis (EDA) to identify attrition patterns.
Train and compare multiple classification models.
Evaluate models using standard performance metrics.
Identify the most important factors influencing employee attrition.
Provide actionable HR recommendations based on the analysis.
📂 Dataset

Dataset: IBM HR Analytics Employee Attrition & Performance

Total Records: 1,470
Features: 35
Target Variable: Attrition (Yes/No)

You can download the dataset from Kaggle:

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

🛠️ Technologies Used
Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
📊 Project Workflow
1. Data Loading & Exploration
Loaded the dataset using Pandas
Examined dataset shape and structure
Identified numerical and categorical features
Calculated overall attrition rate
Checked for duplicate and missing values
2. Data Preprocessing
Removed irrelevant columns
Converted the target variable into binary format
Applied One-Hot Encoding to categorical variables
Standardized numerical features using StandardScaler
3. Exploratory Data Analysis (EDA)
Attrition by Department
Attrition by Job Role
Monthly Income vs Attrition
Work-Life Balance vs Attrition
Years at Company vs Attrition
Correlation analysis
Overtime analysis
4. Machine Learning Models

The following classification models were trained and compared:

Logistic Regression
Random Forest Classifier
Gradient Boosting Classifier
5. Model Evaluation

The models were evaluated using:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
Confusion Matrix
ROC Curve
📈 Visualizations

The project includes the following visualizations:

Attrition Rate by Department
Attrition Rate by Job Role
Monthly Income vs Attrition (Box Plot)
Confusion Matrix
Top 10 Feature Importances
ROC Curve Comparison
💡 Key Business Insights
Approximately 16% of employees in the dataset left the company.
The Sales Department showed the highest attrition rate.
Sales Representatives and Laboratory Technicians experienced the highest employee turnover.
Employees working overtime were significantly more likely to leave.
Lower monthly income was associated with higher attrition, but salary alone was not the primary reason for employees leaving.
Most employees who resigned did so within their first few years at the company.
📌 HR Recommendations
Improve employee engagement during the first three years of employment.
Reduce excessive overtime to improve work-life balance.
Prioritize retention efforts for high-risk departments and job roles.
Review compensation and employee recognition programs regularly.
Use predictive analytics to identify employees at risk and provide timely support.


📁 Project Structure
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
🚀 How to Run the Project
Clone the repository:
git clone https://github.com/your-username/employee-attrition-prediction-ml.git
Navigate to the project directory:
cd employee-attrition-prediction-ml
Install the required libraries:
pip install -r requirements.txt
Launch Jupyter Notebook:
jupyter notebook
Open analysis.ipynb and run all cells.
📦 Required Python Libraries
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
🎓 Learning Outcomes

This project demonstrates practical experience in:

Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Classification Algorithms
Model Evaluation
Data Visualization
HR Analytics
Business Insight Generation
👩‍💻 Author

Anushka

B.Tech Computer Science Engineering (Artificial Intelligence)

Interested in Data Analytics, Machine Learning, and AI-driven Business Solutions.

⭐ Acknowledgements
IBM HR Analytics Dataset
Kaggle
Scikit-learn Documentation
Pandas Documentation
Matplotlib & Seaborn Documentation
📌 If you found this project useful, consider giving it a ⭐ on GitHub!

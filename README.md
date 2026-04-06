Employee Attrition Analysis & Prediction

Project Overview
This project focuses on analyzing employee attrition data to identify the key factors influencing employee turnover and to build a predictive model for attrition.
The goal is to help organizations understand why employees leave and take actions to improve retention.

Dataset
Dataset used: IBM HR Analytics Employee Attrition Dataset  

The dataset contains information about:
- Employee demographics
- Job roles and departments
- Salary and compensation
- Work conditions (overtime, travel, etc.)

Key Steps Performed

1. Data Cleaning
       Checked missing values
       Verified data consistency
       Removed unnecessary columns
2. Exploratory Data Analysis (EDA)
       Calculated total employees and attrition rate
- Analyzed:
        Salary vs Attrition
        Overtime vs Attrition
        Department vs Attrition
        Age distribution
3. Data Preprocessing
        Converted categorical variables into numerical format (encoding)
        Prepared dataset for machine learnin.
4. Model Building
        Used Logistic Regression model
        Split data into train and test sets
5. Handling Imbalanced Data
        Observed class imbalance (low attrition cases)


Applied:
  - `class_weight = "balanced"`

6. Model Evaluation
       Accuracy Score
       Confusion Matrix
       Precision, Recall, F1-score
Key Insights
- Employees with lower salary are more likely to leave
- Employees working overtime have higher attrition
- Frequent business travel increases attrition risk
- Certain departments (like Sales) show higher attrition

Dashboard
A Power BI dashboard was created to visualize:
- Attrition rate
- Salary impact
- Overtime effect
- Department-wise attrition

---

## 🎯 Conclusion
The analysis shows that employee attrition is mainly influenced by:
- Salary
- Workload (overtime)
- Travel frequency

Organizations can reduce attrition by improving compensation and work-life balance.

Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Power BI
- Data Visualization


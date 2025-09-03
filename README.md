
# Employee Turnover Prediction

## 📌 Project Overview
This project predicts whether an employee will leave an organization (employee turnover) using Machine Learning models. It is useful for HR departments to reduce attrition, improve employee satisfaction, and make better workforce planning decisions.

---

## 📊 Dataset
The dataset used is **employee_data.csv** which contains employee records with the following features:

- `satisfaction_level` → Employee satisfaction (0–1 scale)
- `last_evaluation` → Last performance evaluation (0–1 scale)
- `number_project` → Number of projects assigned
- `average_montly_hours` → Monthly average working hours
- `time_spend_company` → Years spent in the company
- `Work_accident` → Whether the employee had a work accident (0/1)
- `promotion_last_5years` → Promotion in the last 5 years (0/1)
- `department` → Employee’s department
- `salary` → Salary level (low, medium, high)
- `left` → Target variable (1 = left company, 0 = stayed)

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🔑 Steps Performed
1. **Data Preprocessing**
   - Cleaned and renamed columns
   - Converted categorical variables (department, salary) to dummy variables
   - Handled feature selection using RFE

2. **Model Training**
   - Logistic Regression
   - Random Forest Classifier

3. **Evaluation**
   - Accuracy score
   - Confusion matrix
   - Classification report
   - ROC-AUC curve

---

## 📈 Results
- Logistic Regression Accuracy: ~77%
- Random Forest Accuracy: ~97%
- Random Forest proved to be the most accurate and reliable model.

### 🔍 Feature Importance (Random Forest)
- **Satisfaction Level** (50% importance)
- **Time Spent in Company**
- **Last Evaluation**
- Salary and promotions had smaller impacts.

---

## 🏆 Conclusion
- Employees with **low satisfaction**, **longer company stay**, and **extreme work hours** are more likely to leave.
- Random Forest provides a strong predictive model that HR teams can use for employee retention strategies.

---

## 🚀 How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/employee-turnover-prediction.git
   ```
2. Install requirements  
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook and run:  
   ```bash
   jupyter notebook "Employee Turnover Prediction.ipynb"
   ```

---

## 📂 Repository Structure
```
📁 Employee-Turnover-Prediction
 ┣ 📄 Employee Turnover Prediction.ipynb
 ┣ 📄 HR.csv
 ┣ 📄 README.md
 ┣ 📄 requirements.txt
```

---

## 👤 Author
Developed by **Your Name**  
📧 your.email@example.com  
🌐 [LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

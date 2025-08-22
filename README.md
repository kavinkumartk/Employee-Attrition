# 🏢 Employee Attrition Prediction

This project predicts which employees are likely to leave the company using **Machine Learning (Logistic Regression)**.  
The goal is to help HR identify at-risk employees and take proactive steps to improve retention.

---

## 📂 Dataset
The dataset used is **employee_attrition.csv**, which contains employee details such as:
- Age  
- Years at Company  
- Job Level  
- Salary  
- Number of Projects  
- Target: `left_company` (1 = Employee left, 0 = Employee stayed)

---

## ⚙️ Project Workflow
1. **Data Preprocessing**
   - Load CSV data using Pandas
   - Select relevant features
   - Encode categorical variables (if any)
   - Train/Test split (70/30)
   - Standardize features with `StandardScaler`

2. **Model Training**
   - Logistic Regression is trained on the scaled data.

3. **Evaluation**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score, Accuracy)
   - ROC Curve and AUC score

4. **Visualization**
   - ROC Curve to show model performance

---

## 📊 Example ROC Curve

![ROC Curve](images/roc_curve.png)

*(Add your ROC curve plot in an `images/` folder and update the path above.)*

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/kavinkumartk/Employee-Attrition.git
   cd Employee-Attrition

---
AUTHOR:KAVINKUMAR T
GITHUB:https://github.com/kavinkumartk

---
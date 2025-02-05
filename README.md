---

# **📊 Credit Risk Analysis: Predicting Loan Defaults**  

## 🚀 **Project Overview**  
This project analyzes **loan applicant data** to predict **default risk** using **two classification models**:  
1. **Logistic Regression**  
2. **Decision Tree**  

By leveraging **financial history, demographic features, and past repayments**, we can help financial institutions **identify high-risk borrowers** and make informed lending decisions.

📌 **Key Highlights**
- 🏦 **Business Problem:** Improve loan approval strategies by identifying risky applicants.
- 🔍 **Feature Engineering:** Data cleaning, handling missing values, and variable transformation.
- 🏆 **Modeling Approach:** Logistic Regression & Decision Tree.
- 📊 **Evaluation Metrics:** Accuracy, Precision, Recall, AUC (ROC Curve), True Positive Rate.

---

## **📂 Project Structure**
```
📂 credit-risk-analysis/
 ├── 📂 data/ (Datasets)
 │   ├── loan_data.csv *(Raw data file)*
 │   ├── processed_loan_data.csv *(Cleaned dataset)*
 │  
 ├── 📂 notebooks/ *(Jupyter Notebooks & R scripts for model building)*
 │   ├── credit_risk_analysis.ipynb *(Exploratory Data Analysis & Model Training)*
 │   ├── model_evaluation.ipynb *(Confusion Matrix, ROC Curve, AUC computation)*
 │  
 ├── 📂 images/ *(Screenshots & visualizations for better insights)*
 │   ├── Modelflow.png *(KNIME Workflow Overview)*
 │   ├── Decision Model Metrics.png *(Decision Tree Model Performance)*
 │   ├── Logit model-metrics.png *(Logistic Regression Model Performance)*
 │   ├── Decision Tree ROC Curve.png *(ROC Curve for Decision Tree)*
 │   ├── Logit ROC Curve.png *(ROC Curve for Logistic Regression)*
 │   ├── Admission by rank.png *(Admission Rate by School Rank)*
 │   ├── Distribution of GRE.png *(GRE Score Distribution)*
 │   ├── GPA Distribution.png *(GPA Score Distribution)*
 │  
 ├── 📂 models/ *(Stored trained models if applicable)*
 │   ├── decision_tree_model.pkl *(Trained Decision Tree Model)*
 │   ├── logistic_regression_model.pkl *(Trained Logistic Model)*
 │  
 ├── 📜 README.md *(Project documentation and guide)*
 ├── 📜 requirements.txt *(Python dependencies)*
```

---

## **📌 Workflow Overview**
This **KNIME Workflow** outlines the complete **data preprocessing, model training, and evaluation process**.

![Workflow](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/Modelflow.png)

---

## **📈 Results & Visualizations**
### **1️⃣ Model Performance Metrics**
#### **🔹 Decision Tree Model Performance**
The **Decision Tree Model** had a **True Positive Rate of 37.5%**, meaning it identified **more actual defaults** compared to Logistic Regression.

📌 **Confusion Matrix & Metrics**:  
![Decision Tree Metrics](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/Decision%20Model%20Metrics.png)

---

#### **🔹 Logistic Regression Model Performance**
The **Logistic Regression Model** had a **True Positive Rate of only 18.8%**, meaning it struggled to correctly classify actual defaults.

📌 **Confusion Matrix & Metrics**:  
![Logistic Regression Metrics](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/Logit%20model-metrics.png)

---

### **2️⃣ ROC Curve Analysis**
#### **🔹 Decision Tree ROC Curve**
The **Decision Tree Model achieved an AUC score of 0.592**, showing moderate predictive power.

![Decision Tree ROC](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/Decision%20Tree%20ROC%20Curve.png)

#### **🔹 Logistic Regression ROC Curve**
The **Logistic Regression Model had an AUC score of 0.665**, performing slightly better at differentiating defaults.

![Logistic Regression ROC](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/Logit%20ROC%20Curve.png)

---

### **3️⃣ Admission Insights**
The **bar chart below shows admission rates by school rank**. **Higher-ranked schools (Rank 1) have a significantly higher admission rate (54.1%)** compared to lower-ranked schools (17.9% for Rank 4).

📌 **Admission Rate by School Rank**:  
![Admission by Rank](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/Admission%20by%20rank.png)

---

### **4️⃣ Feature Distributions**
#### **🔹 GRE Score Distribution**
This histogram shows the distribution of **GRE scores** in the dataset. It appears **slightly right-skewed**, indicating more high GRE scores.

![GRE Distribution](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/Distribution%20of%20GRE.png)

#### **🔹 GPA Score Distribution**
The **GPA scores** are also **right-skewed**, with a concentration of students having high GPAs.

![GPA Distribution](https://raw.githubusercontent.com/EvidenceM290/credit-risk-analysis/main/images/GPA%20Distribution.png)

---

## **🔹 Key Takeaways**
✔ **Decision Tree Model** is **better at predicting actual defaults (37.5% True Positive Rate) than Logistic Regression (18.8%)**.  
✔ **Logistic Regression** has **higher AUC (0.665) than Decision Tree (0.592)**, meaning it’s slightly better at ranking high-risk applicants.  
✔ **Admission rates drop significantly for lower-ranked schools**, impacting acceptance chances.  
✔ **GRE and GPA distributions are skewed**, indicating high competition among applicants.  

---

---

## **📬 Connect With Me**
📧 **Email:** emadhume@smu.edu  
🔗 **LinkedIn:** [Your Profile](your-linkedin-url)  
📂 **GitHub Portfolio:** [Your GitHub](your-github-url)

---



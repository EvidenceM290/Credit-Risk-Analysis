---

# **🎓 Graduate Admissions Prediction Model**
## **📊 Logistic Regression & Decision Tree (CART) Analysis**
This project analyzes **graduate school admissions** based on **GRE scores, GPA, and school ranking** using two classification models:
1. **Logistic Regression**
2. **Decision Tree (CART)**  

The goal is to predict whether an applicant **will be admitted (1) or not admitted (0)** based on their academic profile.

📌 **Key Highlights**
- 🏫 **Business Problem:** Identify key factors influencing graduate school admissions.
- 🔍 **Feature Engineering:** Data cleaning, outlier detection, and statistical transformations.
- 🏆 **Modeling Approach:** Logistic Regression & Decision Tree.
- 📊 **Evaluation Metrics:** Accuracy, Precision, Recall, ROC Curve (AUC), True Positive Rate.

---

## **📂 Project Structure**
```
📂 Graduate-Admissions-Prediction-Model/
 ├── 📂 data/ (Datasets)
 │   ├── admission.csv *(Raw data file)*
 │   ├── cleaned_admission.csv *(Processed dataset)*
 │  
 ├── 📂 notebooks/ *(Knime, Jupyter Notebooks & R scripts for model building)*
 │   ├── admission_prediction.knwf *(Exploratory Data Analysis & Model Training)*
 │   ├──dmission_prediction.knwf(model_evaluation) *(Confusion Matrix, ROC Curve, AUC computation)*
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
This **KNIME Workflow** outlines the full **data preprocessing, model training, and evaluation process**.

![Workflow](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/Modelflow.png)

---

## **📈 Results & Visualizations**
### **1️⃣ Model Performance Metrics**
#### **🔹 Decision Tree Model Performance**
The **Decision Tree Model** achieved a **True Positive Rate (TPR) of 37.5%**, meaning it correctly predicted **more actual admissions** compared to Logistic Regression.

📌 **Confusion Matrix & Metrics**:  
![Decision Tree Metrics](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/Decision%20Model%20Metrics.png)

---

#### **🔹 Logistic Regression Model Performance**
The **Logistic Regression Model** had a **True Positive Rate of only 18.8%**, meaning it struggled to correctly classify admitted students.

📌 **Confusion Matrix & Metrics**:  
![Logistic Regression Metrics](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/Logit%20model-metrics.png)

---

### **2️⃣ ROC Curve Analysis**
#### **🔹 Decision Tree ROC Curve**
The **Decision Tree Model achieved an AUC score of 0.592**, indicating moderate predictive power.

![Decision Tree ROC](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/Decision%20Tree%20ROC%20Curve.png)

#### **🔹 Logistic Regression ROC Curve**
The **Logistic Regression Model had an AUC score of 0.665**, showing slightly better performance at ranking high-potential applicants.

![Logistic Regression ROC](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/Logit%20ROC%20Curve.png)

---

### **3️⃣ Admission Insights**
The **bar chart below shows admission rates by school rank**. **Higher-ranked schools (Rank 1) have a significantly higher admission rate (54.1%)** compared to lower-ranked schools (17.9% for Rank 4).

📌 **Admission Rate by School Rank**:  
![Admission by Rank](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/Admission%20by%20rank.png)

---

### **4️⃣ Feature Distributions**
#### **🔹 GRE Score Distribution**
This histogram shows the distribution of **GRE scores** in the dataset. The scores are **slightly right-skewed**, indicating a concentration of high scores.

![GRE Distribution](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/Distribution%20of%20GRE.png)

#### **🔹 GPA Score Distribution**
The **GPA scores** are also **right-skewed**, with many applicants having **higher GPAs**.

![GPA Distribution](https://github.com/EvidenceM290/Graduate-Admissions-Prediction-Model/blob/main/images/GPA%20Distribution.png)

---

## **🔹 Key Takeaways**
✔ **Decision Tree Model** is **better at predicting actual admissions (37.5% TPR) than Logistic Regression (18.8%)**.  
✔ **Logistic Regression has a higher AUC (0.665), indicating slightly better ranking ability**.  
✔ **Higher-ranked schools have significantly higher admission rates** (54.1% for Rank 1 vs. 17.9% for Rank 4).  
✔ **GRE and GPA distributions suggest competitive applicants tend to have high scores**.  

---

---

## **📬 Connect With Me**
📧 **Email:** emadhume@smu.edu  
🔗 **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/evidence-madhume-874540204/)  
📂 **GitHub Portfolio:** [MyGitHub](https://github.com/EvidenceM290/EvidenceM290/)

---


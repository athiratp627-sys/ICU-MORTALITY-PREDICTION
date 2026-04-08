# 🏥 ICU Mortality Prediction System

## 📄 Project Documentation

---

## 🔹 1. Project Idea

The objective of this project is to develop a **machine learning-based system** to predict whether a patient admitted to the Intensive Care Unit (ICU) is likely to survive or not.

Early prediction of patient mortality can assist healthcare professionals in:
- Prioritizing critical cases  
- Improving treatment decisions  
- Optimizing hospital resources  

The system uses clinical and monitoring data to make accurate predictions.

---

## 🔹 2. Problem Statement

In ICU environments, patient conditions can change rapidly. Traditional methods rely heavily on manual assessment, which may:
- Be time-consuming  
- Lack consistency  
- Miss early warning signs  

This project aims to provide a **data-driven predictive model** to support clinical decision-making.

---

## 🔹 3. Approach

The project follows a **machine learning pipeline approach**:

- Data Collection  
- Data Preprocessing  
- Feature Selection  
- Model Training  
- Model Evaluation  
- Prediction & Confidence Analysis  

---

## 🔹 4. Methodology

### ✅ Data Preprocessing
- Handled missing values using median imputation  
- Removed irrelevant columns (e.g., Patient ID)  
- Converted categorical data if required  
- Scaled numerical features using StandardScaler  

### ✅ Model Building
- Algorithm used: **Random Forest Classifier**

**Reason:**
- Handles large datasets efficiently  
- Works well with medical data  
- Provides feature importance  

### ✅ Handling Imbalance
- Used:
  - `class_weight='balanced'`  
  - (Optional) SMOTE for oversampling  

---

## 🔹 5. Solution

A predictive model was developed that:
- Takes patient clinical data as input  
- Outputs:
  - `0 → Survival`  
  - `1 → Mortality`  
- Provides **prediction confidence score**

---

## 🔹 6. Python Modules Used

- **pandas** → Data handling  
- **numpy** → Numerical operations  
- **matplotlib & seaborn** → Data visualization  
- **scikit-learn** → Machine learning models & evaluation  
- **joblib** → Model saving  
- **imblearn (optional)** → Handling imbalanced data  

---

## 🔹 7. Evaluation Metrics

The model was evaluated using multiple metrics:

- **Accuracy** → Overall correctness  
- **Precision** → Correct positive predictions  
- **Recall (Sensitivity)** → Detecting high-risk patients  
- **F1 Score** → Balance between precision & recall  
- **ROC-AUC Score** → Overall model performance  
- **Confusion Matrix** → Prediction breakdown  

> ⚠️ Special focus was given to **Recall**, as missing a critical patient is highly risky in healthcare.

---

## 🔹 8. Results

- The model successfully predicts ICU mortality  
- Achieved good performance based on:
  - Accuracy  
  - ROC-AUC score  
- Feature importance analysis identified key clinical indicators influencing outcomes  

---

## 🔹 9. Conclusion

This project demonstrates that machine learning can be effectively used to predict ICU patient mortality.

### ✅ Key Outcomes:
- Developed a reliable prediction model  
- Improved understanding of important clinical features  
- Provided a foundation for real-time hospital decision support systems  

---

## 🔹 10. Future Enhancements

- Deploy as a **web application (Streamlit)**  
- Use advanced models like **XGBoost / Deep Learning**  
- Integrate with real-time hospital databases  
- Improve accuracy with larger datasets  

---

## 🔹 11. Final Statement

This system has the potential to assist healthcare professionals in making faster and more accurate decisions, ultimately improving patient outcomes in critical care environments.

---

## 🚀 Project Status

✅ Completed  
📊 Model Trained & Evaluated  
💾 Model Saved for Deployment  

---

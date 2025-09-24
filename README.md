# Telco Customer Churn Prediction 🚀  

Predicting customer churn for a telecommunications company using machine learning.  
This project walks through the full end-to-end data science workflow: data exploration, preprocessing, model training, experiment tracking, and deployment.

---

## 📌 Project Overview  
Customer churn is a critical KPI for subscription-based businesses.  
This project uses the IBM Telco Customer Churn dataset to build a machine learning model that predicts whether a customer is likely to churn.  

**Business Objective:**  
Help the company proactively identify customers at risk of leaving and reduce churn through targeted retention campaigns.

---

## 🗂️ Repository Structure  


---

## 📝 Steps Performed  

1. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions of key features.  
   - Checked missing values and outliers.  
   - Examined churn vs. contract types, payment methods, tenure.  

2. **Preprocessing Pipeline**  
   - Encoded categorical features (OneHot/Label).  
   - Scaled numerical features.  
   - Split into train/test sets.  

3. **Modeling**  
   - Trained a RandomForestClassifier with hyperparameter tuning.  
   - Achieved high accuracy and AUC on test data.  

4. **Experiment Tracking (MLflow)**  
   - Logged parameters, metrics, and models locally.  
   - (Optional) Integrated with remote MLflow server.  

5. **Deployment**  
   - Packaged model as `model.tar.gz`.  
   - Created `inference.py` (SageMaker entry script).  
   - Uploaded to S3 (or alternative) for deployment.  

---

## 🛠️ Tech Stack  
- **Python 3.9+**  
- **Libraries:** pandas, numpy, scikit-learn, joblib, mlflow, boto3  
- **Cloud/Deployment:** AWS SageMaker (or MinIO / GCS alternatives)  
- **Tracking:** MLflow  

---

## 📂 Dataset  
IBM Telco Customer Churn (public dataset)  
[Kaggle Link](https://www.kaggle.com/blastchar/telco-customer-churn)  

> ⚠️ Large files (datasets/models) are not included in this repo.  
> Use the link above or specify your own data path.

---

## 🚀 Getting Started  

### 1. Clone Repository  
```bash
git clone https://github.com/<yourusername>/Telco-Churn-Prediction.git
cd Telco-Churn-Prediction

---

### ✅ Next Steps for You  
1. Create a new file called `README.md` in your project root (C:\Users\Rebecca\Desktop\TELCO PROJECT\Telco-Churn-Prediction\README.md).  
2. Paste the above Markdown.  
3. Commit and push to GitHub:  
```bash
git add README.md
git commit -m "Add professional README for Telco Churn Project"
git push origin main

# 📉 Customer Churn Prediction App

An **AI-powered web application** built with **Streamlit** that predicts whether a telecom customer will **churn** (leave the company) or **stay**, based on their profile and service usage details.

---

## 🚀 Demo
🔗 customer-churn-rate-prediction-k8esatqjcpju9ey3bdvnjw.streamlit.app


## 🚀 Short Video Demo
[https://github.com/user-attachments/assets/889f0cba-29fe-4238-8ef6-60762f2dfda0](https://github.com/user-attachments/assets/889f0cba-29fe-4238-8ef6-60762f2dfda0)

---

## 📌 Features
- Predicts **Customer Churn Risk** using a trained ML model.  
- Two modes:  
  - 🧑 **Single Customer Prediction**  
  - 📄 **Batch Prediction (CSV upload)**  
- Probability-based predictions with clear visualization.  
- User-friendly **Streamlit interface** with modern sidebar design.  
- Supports both **categorical** and **numerical** features.  

---

## 🔍 Usage
1. Open the app in your browser.  
2. Choose between **Single Customer** or **Batch Prediction (CSV)**.  
3. For single prediction: Fill in customer details and click **Predict Churn**.  
   - ⚠️ **Yes** → Customer WILL churn.  
   - ✅ **No** → Customer will NOT churn.  
4. For batch prediction: Upload a CSV file with customer data and view predictions.  

---

## 📊 Dataset
The app is trained using the **Telco Customer Churn Dataset** from [IBM Sample Data](https://www.kaggle.com/blastchar/telco-customer-churn).

- **Target Classes**:  
  - `Yes` → Customer will churn  
  - `No` → Customer will stay  

- **Features**:  
  - Demographics (Gender, SeniorCitizen, Partner, Dependents)  
  - Account Info (Tenure, Contract, Payment Method, Paperless Billing)  
  - Services (Phone, Internet, Online Security, Streaming, Tech Support, etc.)  
  - Charges (MonthlyCharges, TotalCharges)  

---

## ⚙️ Tech Stack
- **Python 3.9+**  
- **Streamlit** (Frontend Web App)  
- **Pandas & NumPy** (Data Processing)  
- **Matplotlib & Seaborn** (EDA & Visualization)  
- **Scikit-learn** (Label Encoding, Model Training, Evaluation)  
- **XGBoost & Random Forest** (Machine Learning Models)  
- **SMOTE (imblearn)** (Handling Class Imbalance)  
- **Pickle** (Model & Encoder Serialization)  

---

## 📸 Screenshots
### 🏠 Home Page
<img width="1910" height="860" alt="image" src="https://github.com/user-attachments/assets/934fea71-f947-409c-9d23-2dc4f0f91315" />


### 🧑 Single Customer Prediction
<img width="1910" height="860" alt="image" src="https://github.com/user-attachments/assets/3eab121a-b7fb-4a18-9f7e-6f6335bdca59" />


### 📄 Batch CSV Prediction
<img width="1910" height="860" alt="image" src="https://github.com/user-attachments/assets/cfd84d2c-3826-4eb4-bdf8-99929a1ac1db" />


---

## 👨‍💻 Author
**Mirza Yasir Abdullah Baig**  

- 🌐 [Kaggle](https://www.kaggle.com/mirzayasirabdullah07)  
- 💼 [LinkedIn](https://www.linkedin.com/in/mirza-yasir-abdullah-baig/)  
- 💻 [GitHub](https://github.com/mirzayasirabdullahbaig07)  

---

## ❤️ Acknowledgements
- [Telco Customer Churn Dataset (IBM)](https://www.kaggle.com/blastchar/telco-customer-churn)  
- [Streamlit Documentation](https://docs.streamlit.io/)  
- [Scikit-learn](https://scikit-learn.org/stable/)  
- [XGBoost](https://xgboost.readthedocs.io/)  

---

## ⚠️ Disclaimer
This project is for **educational purposes only** and should **NOT** be used for real-world business decisions without further validation.  

---


# 📉 Customer Churn Prediction Application

An **AI-powered web application** built with **Streamlit** that predicts whether a telecom customer will **churn** (leave the company) or **stay**, based on their profile and service usage details.

---

## 🚀 Demo
🔗 [customer-churn-rate-prediction-k8esatqjcpju9ey3bdvnjw.streamlit.app](https://customer-churn-rate-prediction-k8esatqjcpju9ey3bdvnjw.streamlit.app/)


## 🚀 Short Video Demo
[Screencast from 2026-07-14 05-30-40.webm](https://github.com/user-attachments/assets/6efc0502-c856-415b-9efa-a3f2ebd36f5d)


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
**Nadeem Gohar**  

- 💼 [LinkedIn](www.linkedin.com/in/nadeem-gohar-0708382b0)  
- 💻 [GitHub](https://github.com/Nadeemgohar)  



## ⚠️ Disclaimer
This project is for **educational purposes only** and should **NOT** be used for real-world business decisions without further validation.  

---


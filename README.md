# 📊 Customer 360 Analytics & Churn Prediction

## 🚀 Project Overview
This project focuses on building a **Customer 360 dataset** from raw transactional data and using it to analyze customer behavior, identify churners, and detect high-value customers.

The goal is to help businesses **improve customer retention, increase revenue, and make data-driven decisions**.

---

## 🧠 Problem Statement
An online marketplace wants to:
- Understand **customer behavior**
- Identify **churned customers**
- Detect **high spenders**
- Improve **business performance and revenue**

---

## 📂 Dataset Description
The dataset contains transactional data from **Nov 2016 to Oct 2018**, including:

- **Customers** → demographic & location data  
- **Orders** → purchase timestamps & delivery info  
- **Order Items** → product & pricing details  
- **Payments** → payment type & value  
- **Reviews** → customer ratings  
- **Products** → product attributes  
- **Geolocation** → location mapping  

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Handling missing values  
- Removing duplicates  
- Converting data types  
- Filtering required time period  

---

### 2️⃣ Customer 360 Creation
Aggregated data at **customer level**:
- Total spend  
- Number of orders  
- Average order value  
- Recency (last purchase)  
- Frequency  
- Average review score  

---

### 3️⃣ Feature Engineering
Key features created:
- Customer Lifetime Value (CLV)  
- Purchase frequency  
- Delivery time  
- Payment behavior  

---

## 🤖 Machine Learning Models

### 📈 Regression
- **Goal:** Predict customer spending / CLV  
- **Model:** Linear Regression  

### 🔍 Classification
- **Goal:** Predict churn (Yes/No)  
- **Model:** Logistic Regression  

### 🧩 Segmentation
- **Goal:** Group customers based on behavior  
- **Method:** Heuristic Segmentation / Clustering  

---

## 📊 Key Insights
- Identified factors influencing **customer churn**
- Detected patterns of **high-value customers**
- Provided actionable insights for **business growth**

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📁 Project Structure
```
Customer-360-Analytics-Churn-Prediction/
│── data/
│── notebooks/
│── src/
│── images/
│── README.md
```

---

## ▶️ How to Run
```bash
git clone https://github.com/your-username/Customer-360-Analytics-Churn-Prediction.git
cd Customer-360-Analytics-Churn-Prediction
pip install -r requirements.txt
```

---

## 📌 Future Improvements
- Use advanced models (Random Forest, XGBoost)  
- Deploy model using Flask/Streamlit  
- Build real-time analytics dashboard  

---

## 🙌 Acknowledgment
This project was developed as part of an analytics assignment to understand real-world customer data and business problems.

---

## ⭐ If you like this project
Give it a ⭐ on GitHub!

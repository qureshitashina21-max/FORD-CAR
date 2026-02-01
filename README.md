# FORD-CAR
# 🚗 Car Price Prediction using Machine Learning

This project predicts the selling price of cars based on specifications like model, year, mileage, fuel type, transmission, engine size, tax, and MPG.  
The goal is to understand which features impact car prices and build a machine learning model that accurately estimates price.

---

## 📌 Project Workflow

### 1️⃣ Data Loading & Cleaning
- Removed missing values  
- Corrected datatypes  
- Handled outliers  
- Cleaned categorical and numerical columns  

### 2️⃣ Exploratory Data Analysis (EDA)
Performed visual analysis using:
- Histograms  
- Boxplots  
- Scatterplots  
- Correlation heatmap  

**Key insights discovered:**
- Newer cars have higher prices  
- More mileage → lower price  
- Automatic cars are generally priced higher  
- Engine size strongly influences price  
- Hybrid cars show higher average prices  
- Transmission, fuel type, and model also affect price  

---

## 🎯 Feature Engineering
- Label Encoding for:
  - Model  
  - Transmission  
  - Fuel Type  

- One-Hot Encoding for categorical features  
- StandardScaler for numerical features:
  - Year  
  - Mileage  
  - Tax  
  - MPG  
  - Engine Size  

---

## 🤖 Model Development
Model used: **Linear Regression**

Steps:
- Split data: 70% train, 30% test  
- Fit Linear Regression  
- Generated predictions  
- Calculated performance metrics  

### 📊 Model Accuracy
- **R² Score:** ~0.73  
- **Adjusted R² Score:** ~0.71  

This shows the model explains around 73% of price variation accurately.

---

## 🧪 Prediction on New Data
The model predicts car prices based on unseen input features, demonstrating real-world usability.

---

## 📁 Project Files
- `Car_Price_Prediction.ipynb` — Full code  
- `README.md` — Documentation  
- `car_data.csv` — Dataset (if included)  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## ✅ Conclusion
This project successfully analyzes the key factors affecting car prices and builds a machine-learning model capable of predicting prices with good accuracy.  
It demonstrates data analysis, visualization, feature engineering, and regression modeling skills.

---

## 👩‍💻 Author
Tashina Qureshi  
Machine Learning & Data Analysis Enthusiast

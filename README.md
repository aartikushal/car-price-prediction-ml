# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting **car prices** using machine learning techniques based on historical vehicle data.  
It analyzes how factors such as **brand, model year, engine size, fuel type, transmission, mileage, doors, and owner count** influence the final price of a car.

The project follows a complete **end-to-end ML lifecycle**:
- Data collection
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training & evaluation
- Model optimization
- Deployment readiness

---

## 🎯 Objective
To build a **high-accuracy regression model** that can predict car prices and help users make informed buying or selling decisions.

---

## 🗂️ Dataset Description
The dataset contains **10,000 car records** with the following attributes:

- Brand  
- Model  
- Manufacturing Year  
- Engine Size  
- Fuel Type  
- Transmission Type  
- Mileage  
- Number of Doors  
- Owner Count  
- Price (Target Variable)

✔️ No missing values  
✔️ No duplicate records  

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights discovered during EDA:

- **Newer cars are priced higher** (strong positive correlation with year)
- **Higher mileage reduces price** (strong negative correlation)
- **Engine size moderately impacts price**
- Automatic transmission vehicles generally have higher prices
- Fuel types are fairly evenly distributed

Visual analysis included:
- Fuel type distribution
- Brand distribution
- Mileage vs Price
- Year vs Price
- Correlation heatmap

---

## 🛠️ Data Preprocessing
- Converted numerical columns to optimized data types
- Applied **Label Encoding** to categorical features
- Selected relevant numerical and encoded categorical variables
- Split data into **training (80%) and testing (20%)** sets

---

## 🤖 Models Used
### 🔹 Random Forest Regressor
- Initially experimented with Random Forest
- Encountered memory limitations with large tree ensembles
- Tuned parameters for stable training

### 🔹 XGBoost Regressor (Final Model)
- Used for better performance and memory efficiency
- Handles complex feature interactions effectively
- Provides strong generalization

---

## 📊 Model Evaluation
Final model performance metrics:

- **R² Score:** ~0.97  
- **Mean Squared Error (MSE):** Low error indicating accurate predictions  

✔️ Regression metrics were used correctly  
❌ Classification metrics were intentionally avoided for continuous target values

---

## 🌐 Deployment Readiness
The trained XGBoost model is saved and integrated with a **Streamlit web application** that allows users to:
- Enter car details
- Instantly receive predicted car price
- Interact with a user-friendly UI

---

## 🚀 Key Learnings
- Proper metric selection is critical (Regression vs Classification)
- Large ensemble models can cause memory issues if not tuned
- XGBoost performs exceptionally well for structured tabular data
- EDA is essential for feature understanding and model trust

---

## 📌 Technologies Used
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- XGBoost  
- Streamlit  

---

## 👩‍💻 Author
**Aarti Potdar**  
Senior Consultant | Oracle & AI Enthusiast  
Passionate about Machine Learning, Data Science & AI-driven solutions

---

⭐ *If you like this project, don’t forget to star the repository!*  
📋 *Feel free to fork and experiment further.*

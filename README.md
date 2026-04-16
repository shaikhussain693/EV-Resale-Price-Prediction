# 🚗 EV Resale Price Prediction System

An end-to-end Machine Learning project to predict electric vehicle resale prices and provide intelligent pricing recommendations.

---

## 📊 Project Overview
This project analyzes EV data and predicts resale value based on vehicle condition score , usage, and other key parameters. It also determines whether the price is fair, overpriced, or underpriced.

---

## 🔍 Problem Statement
Buying or selling EVs without proper pricing insights can lead to losses. This project helps:
- Evaluate vehicle condition score
- Predict accurate resale value  
- Provide pricing recommendations  

---

## 📂 Dataset
The dataset includes:
- Battery health (%)  
- Range and top speed  
- Odometer reading  
- Warranty details  
- Maintenance cost  
- Purchase price and year  
- Mileage details  

---

## ⚙️ Model Architecture

### 🔹 Vehicle Condition Model
Predicts vehicle condition score based on user inputs such as  battery health, mileage, and warranty.

### 🔹 Price Prediction Model
Uses  vehicle condition score to predict resale price.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  

---

## 📈 Key Features
- Developed a machine learning model using XGBoost to predict resale value of electric vehicles.
- Data preprocessing and feature engineering  
- ML pipeline using Scikit-learn  
- Two-stage prediction system  
- Price classification (Fair / Overpriced / Underpriced)  
- Insight generation for users  


## 📊 Model Performance
- Condition Model R²: ~0.87  
- Price Prediction Model R²: ~0.85  
- MAE used to evaluate prediction accuracy

---

## 📁 Project Structure
- ev_resale_prediction.ipynb  
- condition_model.pkl  
- price_model.pkl  
- resale_value.csv  
- output.png  
- requirements.txt  

---

## ▶️ How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Open Jupyter Notebook:
   ev_resale_prediction.ipynb

3. Run all cells

4. Use prediction function for custom input

---

## 📷 Sample Output
![Output](output.png)

---

## 💡 Key Insights
- Predict vehicle condition score
- Predict resale price
- Classify pricing as Fair / Overpriced / Underpriced
- Detects overpriced vehicles  
- Helps users make better pricing decisions  
- Compares expected vs predicted price
- Provides intelligent pricing insights

---

## 🚀 Conclusion
This project demonstrates how machine learning can solve real-world pricing problems using prediction models and business logic.

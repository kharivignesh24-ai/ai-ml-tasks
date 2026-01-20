# 🚢 Titanic Dataset – Feature Encoding & Scaling

## 📌 Overview
This project demonstrates **data preprocessing** on the Titanic dataset to prepare it for **machine learning models**.  
It includes missing value handling, categorical encoding, and numerical feature scaling.

---

## 📂 Dataset
- **File:** `titanic.csv`
- **Target:** `Survived`  
  - `0` → Not Survived  
  - `1` → Survived  

---

## 🛠️ Tools
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Google Colab  

---

## 🔄 Preprocessing Steps
- Filled missing `Age` (median) and `Embarked` (mode)
- Dropped `Cabin`, `Name`, and `Ticket`
- Label encoded `Sex`
- One-hot encoded `Embarked`
- Scaled numerical features using **StandardScaler**
- Saved processed data as `titanic_processed.csv`

---

## 📁 Project Structure

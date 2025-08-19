# 🛒 Walmart Weekly Sales Prediction

## 📌 Project Overview
This project was developed as the **4th and final task** in my **Machine Learning Internship at Elevvo**.  
The goal is to predict **weekly sales for Walmart stores** using different machine learning models and compare their performance.

The dataset contains store-level information such as:
- Store number
- Department number
- Date
- Weekly sales
- Holiday indicator

---

## 📊 Dataset
- **Source:** Walmart Store Sales Forecasting Dataset  
- **Features:**
  - `Store` → Store number
  - `Dept` → Department number
  - `Date` → Weekly date
  - `IsHoliday` → Whether the week includes a holiday
- **Target:** `Weekly_Sales`

---

## ⚙️ Models Used
1. **Linear Regression**
2. **Random Forest Regressor**
3. **XGBoost Regressor**

---

## 🧾 Results
| Model                   |       RMSE        |       R² Score      |
|-------------------------|-------------------|---------------------|
| Linear Regression       | 22482.3683482147  | 0.03070948634089632 |
| Random Forest Regressor | 3786.7611084798896| 0.9725017117183021  |
| XGBoost Regressor       | 4954.463453370013 |0.9529279510345972   |

<img width="689" height="448" alt="Accuracy" src="https://github.com/user-attachments/assets/180df028-1d2c-4f3f-84d2-25f9d76673ef" />


---

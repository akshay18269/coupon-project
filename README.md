# 🎯 Coupon Acceptance Prediction

## 📘 Overview
This project predicts whether a customer will **accept or reject a coupon** based on various contextual and personal factors such as weather, destination, passenger, and coupon type.

Using supervised machine learning models, the goal is to identify the **key drivers behind coupon acceptance** and help design better marketing strategies.

---

## 📂 Project Structure
├── COUPON_ACCEPTANCE_YES_NO_PREDICTION.ipynb # Main notebook (EDA + Modeling)
├── DS_DATA.csv # Dataset used for analysis
└── README.md # Project documentation


---

## ⚙️ Workflow

### 1. Data Exploration
- Loaded and analyzed the dataset  
- Handled missing values  
- Visualized coupon acceptance trends by various features  

### 2. Data Preprocessing
- Encoded categorical features  
- Split the data into training and testing sets  

### 3. Model Building
- Implemented models like:
  - Decision Tree  
  - Random Forest  
  - XGBoost  
- Evaluated using **Accuracy** and **ROC–AUC** metrics  

### 4. Feature Importance
- Identified top factors influencing acceptance, e.g.:
  - `coupon`, `CoffeeHouse`, `Bar`, `destination`, `weather`, `toCoupon_GEQ25min`

### 5. Results
- The best model achieved strong performance on ROC–AUC and accuracy  
- Key insight: **Coupon acceptance increases when offers match user context**

---

## 💡 Business Insights
- Target users based on **context** (distance, company, weather, time).  
- **Personalized offers** drive higher acceptance rates.  
- Focus marketing on high-impact features from the model.

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **Tools:** Jupyter Notebook / VS Code  

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/akshay18269/coupon-acceptance-prediction.git
   cd coupon-acceptance-prediction

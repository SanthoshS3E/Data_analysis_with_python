# 🏡 NYC Airbnb Data Analysis & Price Prediction  

## 📌 Overview  
This project explores the **New York City Airbnb dataset** to perform:  
✅ **Data Cleaning & Preprocessing**  
✅ **Exploratory Data Analysis (EDA)**  
✅ **Clustering with KMeans**  
✅ **Dimensionality Reduction with PCA**  
✅ **Price Prediction using Linear Regression & Random Forest**  
✅ **Recommendation-like insights for hosts**  
✅ **Interactive Price Prediction Web App (Streamlit)**  

The goal is to understand Airbnb listing trends and **predict the price per night for a given listing**.  

---

## 📂 Dataset  
We used the **NYC Airbnb Open Dataset** with columns like:  
- `neighbourhood_group` → Manhattan, Brooklyn, Queens, Bronx, Staten Island  
- `neighbourhood` → specific areas within NYC  
- `room_type` → Entire home/apt, Private room, Shared room  
- `price` → price per night  
- `minimum_nights`, `number_of_reviews`, `reviews_per_month`, `availability_365`  

The dataset contains **missing values & outliers**, making it perfect for **real-world data cleaning practice**.  

---

## 🛠 Tech Stack  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Scikit-Learn** (Linear Regression, KMeans, PCA, RandomForest)  
- **Streamlit** (for interactive web app)  
- **Joblib** (for saving ML model)  

---

## 🚀 Project Workflow  

### 1️⃣ Data Cleaning & Preprocessing  
✔️ Handled missing values (`reviews_per_month`, etc.)  
✔️ Removed extreme outliers (listings with unrealistic price/minimum_nights)  
✔️ Encoded categorical columns (one-hot encoding for `room_type`, `neighbourhood_group`)  

---

### 2️⃣ Exploratory Data Analysis (EDA)  
📊 Visualized:  
- Top 5 most expensive neighbourhoods  
- Room type distribution across NYC  
- Correlation between **availability, reviews, and price**  

---

### 3️⃣ Clustering with KMeans  
- Grouped listings into **clusters based on price, reviews, and availability**  
- Helped identify **low-cost vs premium clusters**  

---

### 4️⃣ Dimensionality Reduction (PCA)  
- Reduced high-dimensional one-hot encoded data  
- Visualized clusters in **2D space** for better interpretability  

---

### 5️⃣ Price Prediction Model  
- Trained **Linear Regression** and **Random Forest** models  
- Features used:  
  - Neighbourhood group, Room type  
  - Minimum nights, Reviews per month, Availability  
- Achieved better accuracy with **Random Forest**  

---



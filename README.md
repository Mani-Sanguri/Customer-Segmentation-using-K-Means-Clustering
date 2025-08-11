# 🛍 Customer Segmentation Using K-Means Clustering

## 📌 Project Overview  
This project implements **K-Means clustering** on retail transaction data to segment customers based on their purchasing behavior.  
The aim is to help businesses **personalize marketing strategies**, improve customer retention, and boost revenue.  

(detailed step by step process in insights text file)

---

## 📂 Dataset  
- **Size:** ~500K+ transactions  
- **Features:**  
  - Invoice details  
  - Stock codes  
  - Quantity & Unit Price  
  - Customer IDs  
  - Transaction Dates  

---

## 🛠 Workflow  

### 1️⃣ Data Preprocessing  
- Removed missing **Customer IDs** and canceled orders  
- Filtered out irrelevant stock codes and anomalies  
- Handled outliers in **Quantity** and **Unit Price**  

### 2️⃣ Feature Engineering  
- Created **RFM (Recency, Frequency, Monetary)** features  
- Applied **IQR method** for outlier detection  
- Standardized features using **StandardScaler**  

### 3️⃣ Clustering  
- Determined optimal cluster count using **Elbow Method** & **Silhouette Score**  
- Applied **K-Means clustering** to group customers  

### 4️⃣ Segmentation Insights  
- **Normal Clusters:** Retain, Re-Engage, Nurture, Reward  
- **High-Value Clusters:** Pamper, Upsell, Delight  

---

## 📊 Results & Insights  
- Identified **high-LTV customers** for premium marketing campaigns  
- Designed **personalized engagement strategies** to reduce churn  
- Segmentation enables **targeted offers, loyalty programs, and upselling**  

---

## 🖥 Tech Stack  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Clustering Algorithm**: K-Means  
- **Feature Scaling**: StandardScaler  
- **Outlier Detection**: IQR Method  

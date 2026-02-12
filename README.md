# ✈️ Airlines Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project focuses on segmenting airline frequent flyer customers using **K-Means Clustering**.
The objective is to identify distinct behavioral customer groups based on their travel history, credit card usage, bonus transactions, and loyalty engagement.

The insights derived from clustering help the airline design **targeted marketing strategies**, improve retention, and optimize loyalty rewards.

---

## 🎯 Business Objective

The airline company aims to:

* Identify meaningful customer segments
* Understand mileage and transaction behavior
* Improve loyalty program effectiveness
* Enable personalized marketing campaigns
* Increase customer lifetime value

---

## 📊 Dataset Description

The dataset (`EastWestAirlines`) contains frequent flyer program data including:

| Feature                           | Description                           |
| --------------------------------- | ------------------------------------- |
| Balance                           | Miles eligible for award travel       |
| Qual_miles                        | Miles qualifying for elite status     |
| cc1_miles / cc2_miles / cc3_miles | Miles earned via credit cards         |
| Bonus_miles                       | Non-flight bonus miles                |
| Bonus_trans                       | Non-flight bonus transactions         |
| Flight_miles_12mo                 | Flight miles in last 12 months        |
| Flight_trans_12                   | Flight transactions in last 12 months |
| Days_since_enroll                 | Loyalty program duration              |
| Award                             | Whether award flight was redeemed     |

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing

* Removed irrelevant columns (ID)
* Checked for missing values
* Standardized features using `StandardScaler`

### 2️⃣ Finding Optimal Clusters

* Applied **Elbow Method**
* Validated using **Silhouette Score**

### 3️⃣ Model Implementation

* Applied **K-Means Clustering**
* Selected **K = 4 clusters**
* Assigned cluster labels

### 4️⃣ Cluster Profiling

* Calculated cluster-wise mean
* Interpreted behavioral patterns
* Derived business insights

---

## 📈 Cluster Insights

### 🔵 Cluster 0 – Credit Card Heavy Users

* High bonus miles
* Strong credit card engagement
* Moderate flight activity
  👉 Revenue through partner spending

### 🟢 Cluster 1 – Low Activity Customers

* Low balance
* Low transactions
* Low award usage
  👉 Target for reactivation campaigns

### 🟡 Cluster 2 – Loyal Balanced Customers

* Long enrollment duration
* Balanced flight + bonus usage
  👉 Retention and loyalty reward focus

### 🔴 Cluster 3 – Elite Frequent Flyers

* Highest flight miles & transactions
* Highest qualifying miles
* Strong award usage
  👉 Premium/VIP customer segment

---

## 💼 Business Impact

This segmentation enables:

* 🎯 Targeted marketing campaigns
* 💳 Optimized credit card partnerships
* 🏆 Improved loyalty program design
* 📈 Increased revenue from premium customers
* 🔁 Better customer retention strategies

---

## 🏗️ Solution Architecture

```
Raw Data
   ↓
Data Cleaning
   ↓
Feature Scaling
   ↓
Elbow & Silhouette Analysis
   ↓
K-Means Clustering
   ↓
Cluster Profiling
   ↓
Business Insights & Strategy
```

---

## ⏱️ Project Timeline

Total Development Time: **6–8 Hours**

* Data Exploration: 1.5 hrs
* Preprocessing & Scaling: 1 hr
* Model Selection & Validation: 2 hrs
* Cluster Interpretation: 1.5 hrs
* Documentation & Presentation: 1–2 hrs

---

## 🚧 Challenges Faced

* Determining optimal number of clusters
* Handling feature scale differences
* Interpreting clusters meaningfully
* Aligning technical output with business strategy

---

## 📊 Project Complexity

**Medium Complexity**

* Requires understanding of unsupervised learning
* Feature scaling importance
* Model validation techniques
* Business-driven interpretation


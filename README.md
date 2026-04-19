# 👥 Customer Segmentation for Targeted Marketing

A data-driven analysis to segment customers based on behavior and spending patterns, enabling personalized marketing strategies and improved customer retention.

---

## 📌 Business Problem
A company wants to better understand its customers to improve marketing effectiveness and maximize revenue.

**Key questions:**
- Can customers be grouped based on purchasing behavior?
- Which customer segments are most valuable?
- How can marketing strategies be tailored for each segment?

---

## 🎯 Objective
Segment customers into meaningful groups using data analysis and provide actionable insights for targeted marketing and customer engagement.

---

## 📊 Dataset
Customer dataset containing:

- `CustomerID` → Unique identifier  
- `Gender` → Male/Female  
- `Age` → Customer age  
- `Annual Income (k$)` → Income level  
- `Spending Score (1–100)` → Spending behavior  

---

## ⚙️ Approach

### 1. Data Preparation
- Cleaned dataset and handled inconsistencies  
- Selected relevant features for clustering  

### 2. Exploratory Data Analysis
- Analyzed distributions of age, income, and spending score  
- Identified initial patterns in customer behavior  

### 3. Clustering (K-Means)
- Applied **K-Means Clustering** algorithm  
- Determined optimal number of clusters using **Elbow Method**  

### 4. Segment Analysis
- Interpreted each cluster based on income and spending patterns  
- Compared behavior across segments  

---

## 📈 Key Insights

- Identified distinct customer segments based on income and spending behavior  
- High-income, high-spending customers contribute significantly to revenue  
- Mid-income customers show potential for upselling  
- Low-spending segments require engagement strategies  

---

## 🚀 Business Recommendations

- 🎯 Target high-value customers with premium offerings  
- 📈 Upsell mid-value customers through personalized campaigns  
- 📉 Engage low-spending customers using discounts and promotions  
- 📊 Use segmentation to drive personalized marketing strategies  

---

## 📊 Visualizations

### Customer Segments (Cluster Plot)
![Cluster Scatter Plot](cluster_plot.png)

### Feature Relationships
![Pair Plot](pair_plot.png)

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## ▶️ How to Run

```bash
git clone https://github.com/Harshu2326/Customer-Segmentation-Project.git
cd Customer-Segmentation-Project
pip install -r requirements.txt


👤 Author
Harika Komatireddy
LinkedIn: https://www.linkedin.com/in/harika-komatyreddy
GitHub: https://github.com/Harshu2326

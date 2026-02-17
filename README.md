# 🎭 Breaking Down Broadway  
A data exploration of Broadway’s weekly grosses, attendance, and capacity trends.

This project analyzes the **Broadway Weekly Grosses** dataset to uncover patterns in revenue, attendance, and theater capacity over time. The goal is to create a clean, beginner‑friendly notebook with clear visuals, a dashboard, and actionable insights.

---

## 📁 Dataset  
**Source:** Kaggle — Broadway Datasets  
Contains weekly grosses, attendance, and capacity percentages for Broadway shows across multiple years.

---

## 🧹 Data Cleaning  
The dataset required several cleaning steps:

- Standardized column names  
- Removed empty “Unnamed” columns  
- Converted `week ending` to datetime  
- Cleaned `gross` and `attendance` by removing commas and symbols  
- Converted `% capacity` from strings to decimals  
- Created `attendance_rate` as a clean metric  

These steps ensured the data was fully numeric and ready for analysis.

---

## 📊 Dashboard  
A quick visual overview of Broadway performance:

### **1. Total Gross Over Time**  
Shows seasonal spikes, especially around major holidays.

### **2. Highest-Grossing Weeks**  
Top 10 weeks by revenue, dominated by holiday periods.

### **3. Attendance Rate Over Time**  
Attendance remains consistently strong, averaging around 80%.

### **4. Summary Statistics**  
Cleaned summary of attendance and capacity metrics.

---

## 🔑 Key Insights

### 1. Broadway grosses show strong seasonal patterns  
Holiday weeks (Thanksgiving, Christmas, New Year’s) consistently generate the highest revenue.

### 2. Attendance remains stable even when grosses fluctuate  
Most weeks maintain attendance around 80%, showing steady audience demand.

### 3. Capacity rarely drops below 70%  
Theaters operate at strong capacity levels throughout the year.

### 4. A few weeks dramatically outperform the rest  
Holiday tourism and blockbuster shows create major revenue spikes.

### 5. Attendance and capacity move together  
Higher attendance aligns with higher capacity percentages, confirming dataset consistency.

---

## 🏁 Conclusion  
This project provides a clear overview of Broadway’s performance using weekly grosses, attendance, and capacity data. After cleaning and preparing the dataset, the dashboard visualizations reveal strong seasonal patterns, consistently high attendance, and reliable audience demand.

Broadway’s resilience is evident: even when revenue fluctuates, theaters maintain solid capacity levels, and holiday periods continue to drive major spikes in gross earnings. These insights highlight the stability and popularity of Broadway as a cultural and economic force.

---

## 🛠️ Tools Used  
- Python  
- Pandas  
- Matplotlib  
- Kaggle Notebooks  

---

## 📝 Edit History  
- Added data cleaning section  
- Added dashboard visualizations  
- Added insights and conclusion  
- Improved formatting for readability  

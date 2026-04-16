# 🏥 Healthcare Patient Analysis: Costs, Admissions & Outcomes

## 📌 Overview
This project analyzes hospital patient data to identify key drivers of healthcare costs, admission patterns, and patient outcomes. Using Python for data cleaning, analysis, and visualization, the goal is to uncover actionable insights that could support operational and financial decision-making in a healthcare setting.

---

## 🎯 Objectives
- Analyze patient admission trends across different admission types  
- Identify high-cost medical conditions  
- Examine the relationship between length of stay and billing amount  
- Explore patient outcomes through test results  

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, Matplotlib)  
- Data Cleaning & Transformation  
- Data Visualization  

---

## 📊 Dataset
The dataset includes hospital patient records with the following fields:
- Patient demographics (age, gender, blood type)  
- Medical condition  
- Admission type  
- Billing amount  
- Date of admission & discharge  
- Test results  

---

## 🧹 Data Preparation
- Cleaned and standardized column names  
- Converted date fields into datetime format  
- Created a new feature: **Length of Stay (LOS)**  
- Removed missing or inconsistent records  

---

## 📈 Key Metrics
- **Average Length of Stay:** X days  
- **Average Billing Amount:** $X  
- **Total Admissions:** X  
- **Most Common Admission Type:** X  

---

## 📊 Visualizations

### 💰  Average Cost by Medical Condition
![Cost by Condition](https://github.com/sforeman23/Healthcare-Analysis/blob/main/avg_amount_medical_condition.png)

### ⏱️ Length of Stay vs Billing Amount
![LOS vs Cost](python/visuals/los_vs_cost.png)

### 🏥 Admissions by Type
![Admissions](python/visuals/admissions_by_type.png)

### 🧪 Test Results Distribution
![Test Results](https://github.com/sforeman23/Healthcare-Analysis/blob/main/test_results.png)

---

## 🔍 Key Insights
- Certain medical conditions drive significantly higher average billing amounts  
- Longer hospital stays are strongly associated with increased costs  
- Emergency admissions represent a significant portion of total admissions  
- Patients with abnormal test results tend to have higher costs and longer stays  

---

## 💡 Recommendations
- Focus cost-reduction strategies on high-cost medical conditions  
- Improve discharge planning to reduce length of stay  
- Analyze emergency admissions to identify preventable cases  
- Prioritize follow-up care for high-risk patients  

---

## 🚀 Future Improvements
- Build a predictive model to identify high-risk patients  
- Incorporate additional datasets (e.g., insurance or treatment details)  
- Develop an interactive dashboard using Power BI or Tableau  

---

## 📁 Project Structure

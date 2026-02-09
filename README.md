# Codveda-Exploratory-Data-Analysis-EDA-churn-bigml-80.csv-Data-Analysis-Intern
---

# 📉 Telecom Customer Churn: Decoding Behavioral Patterns 
### **Predicting the Exit — A Comprehensive Data Story**

📊 **Python | Exploratory Data Analysis | Business Intelligence**

---
## 📌 Project Overview
Customer churn is a critical metric for telecom providers. It is often 5x more expensive to acquire a new customer than to retain an existing one. This project performs an in-depth **Exploratory Data Analysis (EDA)** on the BigML Churn dataset to identify the leading indicators of customer departure.

Instead of just looking at percentages, this analysis builds a behavioral profile of a "Churning Customer" by connecting usage patterns, service interactions, and plan types.

---
## ⚙️ Technical Workflow & Analysis
The project was executed in four distinct phases:

1.  **Data Sanitization & Preparation**:
    * Handled categorical encoding for 'International Plan' and 'Voice Mail Plan'.
    * Validated data types and checked for missing values in the 3,333-record dataset.
2.  **Statistical Profiling**: 
    * Generated summary statistics for usage metrics (Day, Evening, Night, and International).
    * Analyzed the distribution of "Customer Service Calls" to find the tipping point for dissatisfaction.
3.  **Correlation Analysis**:
    * Constructed a **Feature Correlation Matrix** using Seaborn to identify relationships between call charges and the churn target variable.
4.  **Behavioral Segmentation**:
    * Segmented users based on plan type to determine if specific service offerings correlate with higher turnover.

---
## 🖼️ Visual Insights

### **1. Distribution of Total Day Minutes**
<img width="695" height="547" alt="frequency-distribution" src="https://github.com/user-attachments/assets/0e4d3986-085d-4d02-99a3-fdb1b75511b2" />

*Figure 1: This histogram displays a normal distribution of daytime usage, identifying the 150-250 minute range as the standard engagement profile for customer base*

---
### **2. Boxplot: Customer Service Calls vs Churn**
<img width="678" height="547" alt="boxplot" src="https://github.com/user-attachments/assets/b00f8cd1-44c6-4545-a19b-96e1ecf1212a" />

*This plot shows if people who leave (Churn=True) call customer service more often*

---
### **3. Scatter Plot(Day Minutes vs Day Charge)**
<img width="531" height="547" alt="0f32a1dc-5ce6-401a-b4d2-50cbedf9aeca" src="https://github.com/user-attachments/assets/27b7d861-9d06-47c0-b282-dec33e76f1a1" />

*This plot shows the relationship between Day Minutes and Day Charge*

---
### **4. Scatter Plot(Day Minutes vs Day Charge)**
<img width="854" height="803" alt="correlaion plot" src="https://github.com/user-attachments/assets/1cf1dec6-8aec-478b-a94f-765277a0e644" />

*This correlation heatmap identifies the strength of relationships between usage variables, highlighting that Total Day Minutes and Total Day Charge are perfectly correlated drivers of customer cost*

---
## 💡 Key Actionable Insights
* **Threshold for Intervention**: A "Service Call Alert" system should be triggered after a customer’s 3rd call to prevent imminent churn.
* **Segmented Loyalty**: Since high day-time usage is linked to churn, loyalty rewards should be focused on the "Power User" segment.
* **Data Driven Success**: The analysis successfully exported a `churn_summary_statistics.csv` for use in broader business reports.
 
---
## 🛠️ Tools Used
* **Python 3.13**
* **Pandas** for data manipulation
* **Seaborn & Matplotlib** for statistical visualization


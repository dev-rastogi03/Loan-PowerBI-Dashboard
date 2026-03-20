#  Loan Risk & Financial Analysis Dashboard (Power BI)

# Project Overview
This project focuses on analyzing loan data, applicant demographics, and financial risk metrics using Power BI.  
The solution is built on a dataset of over **250,000+ records**, simulating real-world financial analytics.

---

#  Objectives
- Analyze loan distribution and purpose
- Identify patterns in loan defaults
- Study applicant demographics and financial profiles
- Track financial risk trends over time (YOY & YTD)

---

# Tech Stack
- **Power BI Desktop**
- **Power BI Service (Dataflows)**
- **Microsoft SQL Server**
- **DAX (Data Analysis Expressions)**

---

#  Data Pipeline
1. Data stored in SQL Server  
2. Imported into Power BI Service using Dataflows  
3. Connected to Power BI Desktop  
4. Configured Gateway for data refresh  
5. Implemented Scheduled & Incremental Refresh  

---

# Dashboards

 1. Loan Default & Overview
- Loan Amount by Purpose  
- Default Rate by Employment Type  
- Average Income by Employment Type  
- Default Trends by Year  

 2. Applicant Demographics & Financial Profile
- Median Loan by Credit Score  
- Loan Distribution by Age Group & Marital Status  
- Loan by Credit Score Bins  
- Loans by Education Type  

 3. Financial Risk Metrics
- YOY Loan Growth  
- YOY Default Change  
- YTD Loan Analysis  
- Decomposition Tree (Root Cause Analysis)

  
## 📸 Dashboard Preview

![Dashboard1](screenshots/dashboard1.png)
![Dashboard2](screenshots/dashboard2.png)
![Dashboard3](screenshots/dashboard3.png)
---

# Key Insights
- Higher default rates observed in specific employment categories  
- Credit score plays a critical role in loan approval and risk  
- Loan trends show fluctuations across years, indicating market dynamics  
- Income and demographic factors significantly impact loan behavior  

---

# Key DAX Functions Used
- CALCULATE  
- FILTER  
- SUMX / AVERAGEX / MEDIANX  
- DIVIDE  
- ALL / ALLEXCEPT  
- SWITCH  

---

# Features
- Interactive dashboards with filters  
- Data validation at multiple stages  
- Advanced DAX measures  
- Automated data refresh  
- Business-focused insights  

---

# Project Outcome
This project demonstrates the ability to:
- Build end-to-end data pipelines  
- Perform advanced data analysis using DAX  
- Create interactive dashboards for decision-making  
- Work with large-scale datasets  

---

## How to Use
1. Open `.pbix` file in Power BI Desktop  
2. Connect to data source (if required)  
3. Explore dashboards using filters  

---

# Feedback
I would love to hear your feedback and suggestions!

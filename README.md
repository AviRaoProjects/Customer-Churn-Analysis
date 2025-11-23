Customer Churn Analysis using Python (EDA Project)

## Overview  
This project analyzes telecom customer churn to understand why customers leave a service, and what patterns or behaviors contribute to their decision. Using Python-based Exploratory Data Analysis (EDA), this project identifies the key factors that influence churn—such as contract type, tenure, monthly charges, and payment methods.
The goal is to help businesses improve their customer retention strategies.

## Objectives  
Analyze customer demographics & account information
Identify the strongest factors contributing to churn
Visualize churn patterns using effective EDA techniques
Provide actionable insights to reduce customer churn

## Dataset Information  
**Rows:** 3,738
**Columns:** 21
**Target Column:** Churn

## Data Categories  
**Demographics:** Gender, SeniorCitizen, Partner, Dependents
**Account Details:** Tenure, Contract, PaymentMethod, PaperlessBilling
**Services:** InternetService, TechSupport, Streaming, Security Add-ons
**Financial:** MonthlyCharges, TotalCharges

## Technologies Used  
Python
Pandas, NumPy
Matplotlib, Seaborn
Jupyter Notebook

## Key Insights  
Customers with Month-to-Month contracts are most likely to churn.
Higher MonthlyCharges strongly correlate with churn.
Customers with low tenure (new customers) churn the most.
Electronic Check payment method shows significantly higher churn rates.
Customers using extra services like Tech Support or Security add-ons tend to churn less.

## Conclusion  
Customer churn is driven by pricing, contract duration, and customer service factors.
Telecom providers can reduce churn by:
Offering discounts for long-term contracts
Improving early customer engagement
Monitoring high-charge customers
Improving billing and support experience

## How to Run This Project  
```
pip install pandas numpy matplotlib seaborn openpyxl
jupyter notebook
```

👤 Author

Avinash Vidyasagar Rao
Data Analyst | Python | SQL | Power BI
GitHub: https://github.com/AviRaoProjects

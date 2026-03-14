Diwali Sales Analysis: Strategic Retail Insights (Python & EDA)
📌 Project Overview
Retail demand spikes significantly during the Diwali festive season. This project performs an Exploratory Data Analysis (EDA) on a Diwali Sales dataset containing over 11,000+ transaction records.

The goal is to analyze consumer behavior, identify high-performing demographics, and pinpoint the product categories driving the most revenue to help businesses optimize their inventory and marketing strategies.

🎯 Key Business Questions Addressed
Gender-wise Spending: Who spends more—Men or Women?

Age Group Impact: Which age bracket places the highest volume of orders?

State Performance: Which top 5 states are generating the most revenue?

Occupation & Sector: How do spending patterns vary across different industries (IT, Healthcare, Aviation)?

🛠️ Technical Implementation (Workflow)
1. Data Cleaning & Preprocessing
Handling Nulls: Identified and removed missing values in the 'Amount' column to ensure calculation accuracy.

Data Type Correction: Converted 'Amount' from float to integer for memory optimization and cleaner reporting.

Feature Engineering: Optimized columns for better grouping and visualization performance.

2. Exploratory Data Analysis (EDA)
Statistical Summary: Used df.describe() to understand the distribution of sales and customer age.

Visualization: Leveraged Seaborn and Matplotlib to create bar charts, count plots, and heatmaps for visual storytelling.

📊 Strategic Insights (Results)
High-Value Customers: Married women in the 26-35 age group are the most significant contributors to total sales.

Top States: Uttar Pradesh, Maharashtra, and Karnataka emerged as the top three regions by order volume.

Top Categories: The Food, Clothing, and Electronics sectors saw the highest sales volume.

Occupation Impact: Professionals in IT, Healthcare, and Aviation sectors have the highest purchasing power during the festive season.

📂 Repository Contents
Diwali_Sales_Analysis.ipynb: Complete Jupyter Notebook with code, comments, and visualizations.

Diwali_Sales_Data.csv: The raw dataset used for this analysis.

README.md: Project documentation.

🚀 How to Run
Clone the repository: git clone https://github.com/Akashnath1996/Diwali-sale-analysis.git

Install the required libraries: pip install pandas numpy matplotlib seaborn

Run the notebook using Jupyter or VS Code to view the step-by-step analysis.

Developed by: Akash Nath

Certification: Microsoft Certified: Power BI Data Analyst Associate (PL-300) | MCA Candidate (2027)

# 📊 Diwali Sales Analysis: Strategic Retail Insights (Python & EDA)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-31333F?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4479A1?style=for-the-badge&logo=python&logoColor=white)

## 📌 Project Overview
Festive seasons mein sales pattern change ho jate hain. Is project mein maine **Diwali Sales Dataset** ka Exploratory Data Analysis (EDA) kiya hai taaki customer behavior aur product performance ko samjha ja sake. 

Is analysis se business owners ko ye samajhne mein madad milti hai ki unhe apna **marketing budget** kahan kharch karna chahiye aur **inventory** kaise manage karni chahiye.

## 🎯 Key Business Questions Addressed
* **Gender-wise Spending:** Kaun zyada kharch kar raha hai—Men ya Women?
* **Age Group Impact:** Kis age group ke log sabse zyada orders place karte hain?
* **State Performance:** Kaunse top 5 states revenue generate kar rahe hain?
* **Occupation & Sector:** Kya IT sector ke log Healthcare sector se zyada kharch karte hain?

## 🛠️ Technical Implementation (Workflow)

### 1. Data Cleaning & Preprocessing
* **Handling Nulls:** 'Amount' column ke missing values ko remove kiya.
* **Data Type Correction:** 'Amount' column ko float se integer mein convert kiya (Memory optimization).
* **Column Management:** Unnecessary columns ko drop kiya analysis ki clarity ke liye.

### 2. Exploratory Data Analysis (EDA)
* **Statistical Summary:** Dataset ka distribution check karne ke liye `df.describe()` use kiya.
* **Visualization:** `Seaborn` aur `Matplotlib` ka use karke bar charts, count plots aur heatmaps banaye.

## 📊 Strategic Insights (Results)
* **High-Value Customers:** Married women (Age group 26-35) ne sabse zyada shopping ki hai.
* **Top States:** **Uttar Pradesh, Maharashtra, and Karnataka** top performers hain.
* **Top Categories:** Food, Clothing aur Electronics products sabse zyada sell hue.
* **Occupation:** IT Sector, Healthcare aur Aviation industry ke employees ka contribution revenue mein sabse high raha.

## 📂 Repository Contents
* `Diwali_Sales_Analysis.ipynb`: Detailed Python code with comments.
* `Diwali_Sales_Data.csv`: Raw dataset used for the analysis.
* `README.md`: Project documentation.

## 🚀 How to Use
1. Clone the repo: `git clone https://github.com/Akashnath1996/Diwali-sale-analysis.git`
2. Install libraries: `pip install pandas numpy matplotlib seaborn`
3. Run the Jupyter Notebook to see step-by-step analysis.

---
**Developed by:** [Akash Nath](mailto:akashnath001996@gmail.com)  
**Certification:** Microsoft Certified: Power BI Data Analyst Associate (PL-300) | MCA Candidate (2027)


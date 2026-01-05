# 🔄 Customer Pre-Churn Behavioral Analysis

## 📌 Project Overview
This project focuses on identifying **early warning signs of customer churn** by analyzing customer purchase behavior. Instead of directly predicting churn using machine learning, the project emphasizes **behavioral analysis** to understand *why* customers may stop buying.

---

## 🎯 Objective
- Analyze customer behavior to detect pre-churn patterns
- Identify customers at high risk of churn
- Understand how purchase gaps, spending drops, category switching, and payment changes affect retention
- Provide actionable business insights for customer retention

---

## 📂 Dataset Description
The dataset contains simulated customer behavior data with the following columns:

| Column Name           | Description                                      |
|-----------------------|--------------------------------------------------|
| customer_id           | Unique customer identifier                       |
| last_purchase_days    | Days since last purchase                         |
| purchase_frequency    | Number of purchases made                         |
| average_spend         | Average spending amount                          |
| category_switch       | Whether the customer switched product categories |
| payment_change        | Whether the customer changed payment method      |

---

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📊 Analysis Performed
- Customer risk segmentation based on purchase gap
- High-risk vs low-risk customer comparison
- Spending pattern analysis
- Impact of category switching on spending
- Impact of payment method changes on behavior
- Data visualization using bar charts

---

## 📈 Key Insights
- Customers with long gaps since their last purchase are at higher churn risk
- High-risk customers show significantly lower average spending
- Category switching is a strong indicator of unstable behavior
- Payment method changes often act as early churn warning signals
- Behavioral analysis helps businesses act *before* customers churn

customer-pre-churn-analysis/
│── customer_behavior.csv
│── customer_pre_churn_analysis.ipynb
│── README.md

## ▶️ How to Run the Project
1. Clone the repository
2. Install required libraries:
pip install pandas matplotlib
3. Open the notebook:
jupyter notebook
4. Run all cells in `customer_pre_churn_analysis.ipynb`

---

## 🚀 Future Enhancements
- Add machine learning models for churn prediction
- Include time-series analysis
- Expand dataset with customer demographics
- Build an interactive dashboard using Streamlit

---

## 👨‍💻 Author
**Himesh Kudalkar**  
B.Tech Artificial Intelligence & Data Science  
🔗 GitHub: https://github.com/himeshkudalkar07  
🔗 LinkedIn: https://www.linkedin.com/in/himesh-kudalkar-7838042b2

---

## 📁 Project Structure

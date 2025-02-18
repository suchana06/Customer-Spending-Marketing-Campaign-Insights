# 📊 Customer Spending & Marketing Campaign Insights  

## 🔥 Overview  
This project analyzes a marketing campaign dataset to uncover key insights into **customer spending behavior, purchasing trends, and marketing effectiveness**. The analysis was conducted using **Microsoft Excel**, leveraging its **Data Analysis Toolpak, Pivot Tables, and Visualizations** to extract meaningful patterns.  

📌 **Key Objectives:**  
- Understand how demographics affect spending  
- Evaluate the impact of website visits, discounts, and promotions on total revenue  
- Identify trends in purchasing channels (in-store, online, catalog)  
- Provide data-driven recommendations to optimize marketing strategies  

**Dataset Source**: Kaggle  
🔗 [Marketing Campaign Dataset](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign)  

---

## 📁 Dataset  
The dataset consists of **2,240 customer records and 21 features**, including:  
- **Demographics**: Age, Marital Status, Education Level, Income  
- **Spending Behavior**: Purchases by category (Wine, Meat, Fish, etc.), Total Amount Spent  
- **Marketing & Engagement**: Number of website visits, acceptance of promotional offers  
- **Transaction History**: Last purchase date (Recency), purchase channels (In-store, Online, Catalog)  

---

## ⚙️ Tools Used  
- **Microsoft Excel**  
  - **Data Cleaning**: Handling missing values, removing outliers  
  - **Pivot Tables**: Aggregating and summarizing data  
  - **Data Analysis Toolpak**: Statistical insights & trend analysis  
  - **Visualizations**: Bar charts, scatter plots, trendlines  

---

## 🛠 Data Cleaning & Preparation  
- **Missing Values**: Checked and handled missing income values.  
- **Feature Engineering**: Created two key columns:  
  - **Total Amount Spent**: Sum of all purchases per customer.  
  - **Total Purchases**: Count of total purchases per customer.  
- **Outlier Treatment**: Filtered extreme values in **income distribution** to improve visualization accuracy.  

---

## 📊 Exploratory Data Analysis (EDA)  

### 🏠 **Spending vs. Demographics**  
✔ **Married and cohabiting customers** spend the most.  
✔ **Single and divorced customers** have lower spending levels.  
✔ **Wine & Meat Products** have the highest purchase rates across all categories.  

### 🌐 **Website Visits vs. Purchases**  
✔ High website visits **do not** always lead to high spending.  
✔ Customers with **1-6 website visits** spend the most.  
✔ Website visits drop significantly **after 9-10 visits**.  

### 🎓 **Education Level vs. Income & Spending**  
✔ Higher education levels **correlate with higher income**.  
✔ Spending increases proportionally with income.  
✔ Customers with **Master’s, Graduation, and PhD degrees** spend the most.  

### ⏳ **Recency of Last Purchase vs. Spending**  
✔ Customers who purchased **within the last 90 days** spend the most.  
✔ Spending **decreases sharply** for customers whose last purchase was **90+ days ago**.  

### 💰 **Effect of Discounts on Spending**  
✔ Customers who purchased **only 1 deal spent the most** ($698,725).  
✔ As the **number of deals increases, spending decreases**.  
✔ Customers who purchased **15+ deals spent only $6,332**, suggesting **excessive discounting reduces revenue**.  

### 📆 **Year-wise Spending Trends**  
✔ Customers enrolled in **2013 spent the most**, followed by 2012.  
✔ Customers enrolled in **2014 had the least spending**.  

### 🔥 **Marketing Offer Acceptance Rate**  
✔ **1,631 out of 2,240 customers** **did not accept any offers**.  
✔ **Only 370 customers accepted a single offer**, and the number declines as offers increase.  
✔ **Only 10 customers accepted 5 offers**, meaning multiple accepted offers are **very rare**.  

### 📊 **Income vs. Total Purchases (Scatter Plot with Trendline)**  
✔ **Equation**: `y = 0.0002x + 2.461`  
✔ **R² value**: `0.4429` → Weak-to-moderate positive correlation  
✔ Higher income **slightly** increases purchases, but is **not the strongest predictor**.  

### 🏬 **Purchasing Channel Preferences**  
| Purchase Channel | Total Transactions |
|-----------------|------------------|
| **In-store**    | 12,970           |
| **Website**     | 9,150            |
| **Catalog**     | 5,963            |
| **Discounted Deals** | 5,208    |

✔ **In-store shopping** is the most preferred method.  
✔ **Website and catalog purchases** follow as secondary options.  
✔ **Discount-based purchases are the lowest**, showing discounts alone do not drive high sales.  

---

## 🏆 Key Takeaways  
📌 **High-income, highly educated customers** are top spenders.  
📌 **Discounts do not necessarily lead to higher revenue** – optimal discounting strategy needed.  
📌 **Customers with frequent but limited website visits (1-6) engage the most**.  
📌 **Most customers do not accept multiple promotional offers** – re-evaluate marketing campaigns.  
📌 **Customers from 2013 & 2012 spend the most** – focus marketing efforts on them.  

---

## 📢 Recommendations  
✔ **Target high-income, high-education customers** with premium promotions.  
✔ **Encourage in-store purchases**, as they generate the highest revenue.  
✔ **Optimize discounts** to attract deal-seeking customers without reducing total revenue.  
✔ **Improve engagement strategies** for customers with 5+ website visits but low conversion rates.  
✔ **Reassess marketing campaigns** to encourage multi-offer acceptance.  


---

## 📌 How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/suchana06/Customer-Spending-Marketing-Campaign-Insights.git
2. Open marketing_analysis.xlsx in Excel.
3. Navigate through different sheets for:
   - Data Cleaning
   - Pivot Table Insights
   - Visualizations
  
---

# ⭐ If you found this project useful, please give it a star! ⭐

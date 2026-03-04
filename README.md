# E-Commerce-Business-Intelligence-Data-Analysis-Project
An end-to-end Business Intelligence & Analytics Project built using Power BI, including complete Exploratory Data Analysis (EDA) and an interactive dashboard for business insights.

This project transforms raw ecommerce data into meaningful insights to support data-driven decision-making.

🎯 Project Objective

Perform Exploratory Data Analysis (EDA) on ecommerce dataset

Analyze sales performance, profitability & customer behavior

Identify top-performing products and categories

Track KPIs like Revenue, Profit, Orders & Growth

Build an interactive Power BI dashboard for stakeholders

📂 Dataset Used

E-Commerce Sales Dataset

Key Columns:

Order ID

Order Date

Customer Name

Segment

Region

Category

Sub-Category

Sales

Quantity

Profit

# dataset : https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data

🔎 Exploratory Data Analysis (EDA)

EDA was performed before building the dashboard to understand data patterns and quality.

1️⃣ Data Cleaning

Removed duplicates

Handled missing values

Standardized date format

Checked data types

Validated revenue and profit calculations

2️⃣ Data Integrity Checks

Revenue = Quantity × Unit Price

Verified profit margins

Checked negative profit transactions

Ensured unique combinations of:

Order ID + Date + Product
3️⃣ Univariate Analysis

Sales distribution

Profit distribution

Orders by Region

Category-wise sales contribution

4️⃣ Bivariate / Multivariate Analysis

Sales vs Profit correlation

Region vs Category performance

Segment-wise profitability

Monthly sales trend analysis

📈 Key Insights from EDA

Certain categories generate high revenue but low profit

Some regions show consistent losses

Seasonal spikes observed in Q4

Consumer segment contributes highest order volume

📊 Power BI Dashboard

After EDA, insights were transformed into an interactive dashboard.

🏠 Page 1 – Sales Overview
KPIs:

💰 Total Revenue

📦 Total Orders

📊 Total Profit

📈 Profit Margin %

Visuals:

Sales by Region

Sales by Category

Monthly Sales Trend

Segment-wise Revenue

📦 Page 2 – Product Performance
KPIs:

Top Selling Product

Most Profitable Category

Total Quantity Sold

Average Order Value

Visuals:

Category vs Profit

Sub-Category Analysis

Top 10 Products

Product Profitability Matrix

👥 Page 3 – Customer & Segment Analysis
KPIs:

Total Customers

Repeat Customer Rate

Segment-wise Revenue

Average Sales per Customer

Visuals:

Segment Distribution

Region-wise Customer Map

Customer Contribution Analysis

📊 Page 4 – Profit & Trend Analysis
KPIs:

Year-over-Year Growth

Monthly Growth %

Loss-Making Categories

High Margin Products

Visuals:

Sales & Profit Trend

Profit by Region

Growth Analysis

🛠 Tools & Technologies Used

Power BI – Dashboard & Data Modeling

Power Query – Data Cleaning

DAX – Calculated Measures

Excel / CSV – Dataset

📌 DAX Measures Used
Total Revenue = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Revenue], 0)

Total Orders = DISTINCTCOUNT(Sales[Order ID])
🚀 Business Impact

✔ Helps identify high-profit products
✔ Detects loss-making segments
✔ Improves inventory planning
✔ Supports regional performance analysis
✔ Enables strategic decision-making

📸 Dashboard Preview

(Add screenshots here)

📁 Project Structure
E-Commerce-BI-Dashboard/
│
├── Dataset/
├── EDA Analysis/
├── E-Commerce Business Intelligence Dashboard.pbix
└── README.md

👨‍💻 Author
Sujal Dhanwij
Aspiring Data Analyst | Power BI Developer


# output :

<img width="1280" height="715" alt="image" src="https://github.com/user-attachments/assets/644a2ffd-9f70-48aa-a1ac-62ed99a98468" />

<img width="1280" height="718" alt="image" src="https://github.com/user-attachments/assets/0969feb8-7560-412e-8762-4694e5b61771" />

<img width="1280" height="714" alt="image" src="https://github.com/user-attachments/assets/616a9b97-a66d-4396-a97d-2ee5b4243611" />

<img width="1280" height="712" alt="image" src="https://github.com/user-attachments/assets/abef4879-db30-4918-a6ba-eb8773e24464" />

<img width="1280" height="711" alt="image" src="https://github.com/user-attachments/assets/1f6a847a-562e-4511-ad1d-92d63a50ffdc" />

<img width="1280" height="717" alt="image" src="https://github.com/user-attachments/assets/e34f759b-50b0-464e-91c4-ffca2b7e4971" />


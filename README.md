# AdventureWorks Sales, Customer & Product Performance Analytics

An interactive **Power BI dashboard project** analysing sales activity, customer demographics, product performance and product returns to generate meaningful business insights.

## 📌 Project Overview

This project uses the AdventureWorks dataset to explore business performance through interactive dashboards. It demonstrates data cleaning, data modelling, DAX calculations and data visualisation using Power BI.

## 🎯 Project Objectives

- Analyse overall order and quantity trends.
- Identify top-performing products and product categories.
- Understand customer distribution across countries.
- Analyse customer demographics and segmentation.
- Evaluate product returns and return patterns.
- Present meaningful business insights and recommendations.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualisation
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and calculated columns
- **Data Modelling** – Table relationships and data analysis

## 📂 Dataset

The project uses the AdventureWorks dataset, containing the following tables:

- Sales
- Calendar
- Customer
- Product
- Product Subcategory
- Product Category
- Returns
- Territory

**Dataset source:** [AdventureWorks Dataset – GitHub](https://github.com/spencerdavis226/adventure-works)

## 📊 Dashboard Pages

### 1. Project Overview
Introduces the project, objectives, dataset and tools used.

### 2. Executive Dashboard
Provides a high-level view of overall business performance through KPI cards and sales trends.

### 3. Customer & Product Analysis
Explores customer distribution by country, top 10 products by order quantity and product category performance.

### 4. Product Returns & Quality Analysis
Examines returned quantities, product returns by country, monthly return trends and return rate.

### 5. Customer Demographics & Segmentation
Analyses customers by age group, gender, education level and occupation.

## 📈 Key Project Metrics

| Metric | Result |
|---|---:|
| Total Orders | 25,164 |
| Total Customers | 18,148 |
| Total Order Quantity | 84,174 |
| Total Returned Quantity | 1,828 |
| Return Rate | 2.17% |

*Note: The return rate is calculated using total returned quantity divided by total order quantity. The two measures use different date contexts, so this is an overall descriptive indicator.*

## 💡 Key Insights

- The dataset records 25,164 distinct orders and 84,174 units ordered.
- Customer demographics show that approximately 79% of customers fall into the 55-and-above age group.
- Male and female customers have a nearly balanced distribution.
- Product analysis highlights the leading products and categories by order quantity.
- Return analysis helps identify product and geographical patterns in returned quantities.

## 📁 Repository Structure

```text
AdventureWorks-PowerBI-Analytics/
│
├── README.md
├── AdventureWorks_Sales_Analytics.pbix
├── screenshots/
│   ├── 01-project-overview.png
│   ├── 02-executive-dashboard.png
│   ├── 03-customer-product-analysis.png
│   ├── 04-returns-quality-analysis.png
│   └── 05-customer-segmentation.png
└── .gitignore
```

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Explore the report pages and interact with the available slicers and visuals.

## 👩‍💻 Author

**Priyanka Kumari**

Master Certification in Data Science & Analytics with AI  
IT Vedant

[GitHub Profile](https://github.com/Priya3323)  
[LinkedIn Profile](https://www.linkedin.com/in/priyankakumari33/)

---

*This project was developed as part of my Data Science and Analytics learning journey to strengthen practical skills in Power BI, data analysis and business intelligence.*

## 🖼️ Dashboard Preview

### 1. Project Overview
![Project Overview](./screenshots/01-project-overview.jpeg)

### 2. Executive Dashboard
![Executive Dashboard](./screenshots/02-executive-dashboard.jpeg)

### 3. Customer & Product Analysis
![Customer & Product Analysis](./screenshots/03-customer-product-analysis.jpeg)

### 4. Product Returns & Quality Analysis
![Returns & Quality Analysis](./screenshots/04-returns-quality-analysis.jpeg)

### 5. Customer Demographics & Segmentation
![Customer Segmentation](./screenshots/05-customer-segmentation.jpeg)

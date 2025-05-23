# 📊 BUSINESS INSIGHTS 360 – Power BI Analytics Project
Power BI dashboard offers full-spectrum reports across Finance, Sales, Marketing, Supply Chain, and Executive views—delivering a complete 360° perspective of business performance.

## 🔍 Project Overview

**AtliQ Hardware**, a fast-growing global company in the computers and accessories sector, operates across three major sales channels: **retailers**, **direct sales**, and **distributors**. Despite rapid expansion, unexpected losses after launching a U.S. store revealed a lack of deep analytical insight.

To compete with data-savvy rivals, AtliQ adopted **Power BI** to transform decision-making across departments—**Finance, Sales, Marketing, Supply Chain**, and **Executive Leadership**.

This project was developed as part of the **Codebasics Power BI Bootcamp**, simulating a real-world enterprise reporting solution.

🔗 [**View Full Power BI Report**](https://app.powerbi.com/reportEmbed?reportId=0f1ee816-6b6c-4c5a-9ab6-1d65b638f67f&appId=9fc65aef-3cba-4ab8-b15b-106fba5191ac&autoAuth=true&ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4)  
🎥 [**Presentation on LinkedIn**](https://www.linkedin.com/feed/update/urn:li:activity:7298590161620131840/)

---

## 🗂️ Datasets Used
Before beginning the analysis, it’s important to understand the datasets. They include two types of tables:

Dimension tables: These have fixed information like customer and product details.

Fact tables: These contain transaction records and business activities.
### 📁 **Database: gdb041**
- `dim_customer`: Customer master data  
- `dim_market`: Market segmentation  
- `dim_product`: Product catalog  
- `fact_forecast_monthly`: Forecasted sales quantities  
- `fact_sales_monthly`: Actual monthly sales data  

### 📁 **Database: gdb056**
- `freight_cost`: Logistics costs  
- `gross_price`: Product pricing  
- `manufacturing_cost`: Production costs  
- `pre_invoice_deductions`
- `post_invoice_deductions`

---

## Importing Data and Data Modeling

Data was imported from MySQL into Power BI. After cleaning and transforming the data, a data model was created to enable effective analysis.

**Why is data modeling important?**  
A data analyst’s workflow typically follows four steps:

✅ Data Extraction → ✅ Data Cleaning → ✅ Data Modeling → ✅ Data Analysis

You cannot skip the third step, as data modeling lays the foundation for all reports. All visuals depend on a good data model; poor modeling can negatively impact report performance.

In this project, we used the **Snowflake schema** data modeling method.

![Data Model Diagram](images/data_model.png)


---

## 📊 Power BI Dashboard Overview

This report contains **6 interactive pages**, offering a 360° view of AtliQ’s operations:

- **Home**: Navigation dashboard  
- **Finance**: Profit & Loss, Net Sales, Top/Bottom performers  
- **Sales**: Customer & Product trends, Gross Margin  
- **Marketing**: Campaign analysis, Segment profitability  
- **Supply Chain**: Forecast accuracy, Inventory management  
- **Executive Summary**: Key metrics for senior leadership  

---

## 🧠 Skills & Concepts Learned

- Power BI fundamentals  
- DAX formulas & calculated measures  
- Data cleaning & modeling (Snowflake schema)  
- Conditional formatting, custom tooltips, dynamic titles  
- File optimization using **DAX Studio**  

---

## 🛠 Tools & Technologies

- **Power BI Desktop**  
- **DAX Studio**  
- **MySQL**  
- **Microsoft Power Platform**  

---

## 📚 Business Concepts Covered

- **Financial Metrics**: Gross/Net Sales, Net Profit, Net Invoice Sales  
- **Cost Metrics**: COGS, Freight & Manufacturing costs  
- **Performance Indicators**: YTD (Year-to-Date), YTG (Year-to-Go), Gross Margin %  
- **Sales Channels**: Direct, Retailers, Distributors  
- **Marketing KPIs**: Segment Profitability, Campaign Engagement  

---

## ✅ Conclusion

This Power BI project provides AtliQ Hardware with a comprehensive reporting tool to explore trends, uncover insights, and support strategic decisions. It offers a **360-degree** business view that helps convert raw data into actionable intelligence.

> **Explore, Analyze, Decide!** 📊🔍🚀

---

## 🖥️ Prerequisites

Ensure the following tools are installed before working with this project:

- [**Power BI Desktop**](https://powerbi.microsoft.com/desktop/)  
- [**DAX Studio**](https://daxstudio.org/)

---

## 🤝 How to Contribute

Contributions are welcome!

- 📌 Open an issue for suggestions or bugs  
- 📌 Fork the repository and submit a pull request  
- 💬 Let’s build and learn together!

---

## 🙏 Acknowledgments

- 👨‍🏫 **Hemanand Vadivel** – Instructor & Mentor  
- 👨‍💻 **Dhaval Patel** – Founder of [Codebasics](https://codebasics.io)  

Special thanks to the Codebasics community for making this project possible.

---


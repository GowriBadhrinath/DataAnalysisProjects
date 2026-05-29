# DataAnalysisProject
# Power BI Sales Insights Dashboard (MySQL Connected)

An interactive Power BI dashboard designed to analyze retail sales performance, track key business metrics, and uncover regional trends using data hosted in a MySQL database.

## 📊 Project Overview
This project transforms raw data from a MySQL database into actionable business insights. It connects directly to relational database tables to help stakeholders monitor health metrics, understand customer behavior, and identify growth opportunities.

## 🚀 Key Features
* **Executive Summary**: High-level overview of total sales, profits, and profit margins.
* **Regional Analysis**: Interactive maps and charts showing sales performance by location.
* **Product Insights**: Deep dive into top-performing product categories and items.
* **Time-Trend Tracking**: Sales growth comparison across months, quarters, and years.

## 🛠️ Tools & Technologies Used
* **MySQL Database**: Hosts the relational schemas, transaction histories, and customer tables.
* **Power BI Desktop**: For data modeling and visual dashboard creation.
* **Power Query**: For importing tables and filtering data directly via MySQL connectors.
* **DAX (Data Analysis Expressions)**: For creating custom calculated columns and measures.

## 📈 Key Metrics Tracked (DAX Measures)
* Total Revenue
* Total Profit & Profit Margin (%)
* Year-over-Year (YoY) Sales Growth
* Total Units Sold

## 📁 Repository Structure
* `/MySQL_Scripts`: Contains the `.sql` files used to set up tables or run views.
* `/Report`: Contains the main `.pbix` Power BI file.
* `/Screenshots`: Images of the dashboard pages for quick preview.

## 💻 How to View the Dashboard
1. Clone this repository to your local machine.
2. Review the data schema or views inside the `/MySQL_Scripts` folder.
3. Open the `.pbix` file located in the `/Report` folder using [Power BI Desktop](https://microsoft.com).

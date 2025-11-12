# ElectroHub Power BI Dashboard

## 🏪 Overview
**ElectroHub** is a small retail store that sells a wide range of products across multiple categories.  
This Power BI project visualizes key business insights, helping track performance, understand trends, and support data-driven decisions.

### 🛍️ Product Categories
- Electronics  
- Footwear  
- Clothing  
- Accessories  
- Home Appliances  
- Personal Care  
- Bags  
- Kitchenware  

## 🎯 Project Objectives
This Power BI dashboard is designed to answer key business questions, including:

- What are the **Top and Bottom 5 products** by sales, profit, or quantity sold?  
- How do **sales trends** change over time (daily, monthly, quarterly, annually)?  
- What is the **relationship between sales and profit**?  
- How do **two selected time periods** compare in terms of sales, profit, and quantity sold?  
- What is the **average discount** offered in each category?  
- What is the **total number of orders**?  
- How can users view **sales, profit, discounts, and other order-level details** interactively using filters?  
- How do **sales vary by city**?  

## 📈 Key Features
- Interactive visuals with drill-down capabilities  
- Dynamic filtering by category, time period, and region  
- Visual comparison of performance between different time periods  
- Insightful KPIs to measure overall business health  

## 🧠 Insights
The dashboard provides ElectroHub’s management with actionable insights into product performance, customer trends, and profitability — enabling smarter inventory and marketing decisions.

## ⚙️ Process

### 1. Identify Business Requirements
The first step was to define the key business questions and performance indicators (KPIs) that the dashboard needed to answer. These included tracking top and bottom products by sales, profit, and quantity, analyzing trends over time, comparing performance between periods, and examining sales by city and discount categories.

### 2. Load Data into Power BI
An Excel file (`.xlsx`) containing ElectroHub’s store data was imported into **Power BI Desktop**. The dataset included details on products, sales, customers, and transactions.

### 3. Data Profiling and Transformation
Data profiling and cleaning were performed using the **Power Query Editor**. This step involved:
- Inspecting column statistics to detect missing or invalid values.  
- Removing errors and duplicates to ensure data consistency.  
- Verifying that all `CustomerID` values were distinct and valid.  
- Correcting data types (e.g., dates, numeric fields, and text fields) to ensure smooth analysis and accurate visualizations.  
- Renaming columns for clarity and standardizing field names.  
- Creating a new field, `PromotionID`, to serve as a unique primary key for promotions.  

### 4. Data Modeling
In **Model View**, tables were connected using appropriate relationships to form a **Star Schema**.  
This included:
- Defining **primary and foreign keys** between fact and dimension tables.  
- Setting **cardinality** (one-to-many or many-to-one) and enforcing referential integrity.  
- Ensuring logical relationships that accurately reflect business rules.  

### 5. Filtering and Interactivity
The dashboard utilized different types of filters in the **Filters pane** to enable dynamic user interaction.  
This included:
- Page-level, visual-level, and report-level filters.  
- Adjusting filter behavior for dimension tables to ensure accurate slicing across visuals.  
- Implementing slicers and visual filters for categories such as time period, product category, and region.

### 6. Dashboard Development
Multiple visuals were created to represent insights effectively:
- Area charts for sales trends.  
- Bar and column charts for top/bottom product analysis.  
- A table with different filters (Filter by date, customer name, promotion name, etc).  
- Card visuals and KPIs for total orders.
- Maps for city-wise Netsales distribution.  

This structured process ensured that the **ElectroHub Power BI Dashboard** was both visually engaging and analytically powerful, allowing users to explore data intuitively and make informed decisions.

## 📁 Files Included
- `Electrohub Business.pbix` — Power BI project file containing the complete dashboard.  
- `ElectroHub Store Data.xlsx` — Dataset used for analysis and data modeling.  
- `README.md` — Project documentation.  
- `ElectroHub Project SS.png` — Folder containing dashboard preview images.  

## 🚀 How to Use
1. Download the `Electrohub Business.pbix` file.  
2. Open it using **Power BI Desktop**.  
3. Load the provided dataset (`ElectroHub Store Data.xlsx`) if prompted.  
4. Interact with the dashboard using slicers, filters, and visuals to explore insights.  

## 🧰 Tools & Technologies
- **Microsoft Power BI Desktop**  
- **Power Query Editor** (for data transformation)  
- **DAX** (Data Analysis Expressions)  
- **Excel (.xlsx)** for source data  

## 📊 Results & Key Insights
- Identified top-performing product categories driving the majority of revenue. (Example: Apple iphone 14 is ranked highest by net sales with 21.4 million INR and has sold the most units with 281 units).
- Detected cities with the highest and lowest sales performance.  
- Found that discount levels have a measurable impact on profit margins.  
- Provided managers with interactive visuals for time-based and regional analysis.  

## 🔮 Future Improvements
- Integrate real-time data updates through Power BI Service.  
- Automate monthly reports and email summaries using Power Automate.  


## View Dashboard
You can view the live Power BI dashboard here:  
[🔸 ElectroHub Power BI Dashboard](https://app.powerbi.com/links/5GBuSqNLBM?ctid=a06e9366-d14a-4a15-9642-9f0e11b01cd2&pbi_source=linkShare)

<img width="1716" height="957" alt="ElectroHub Project SS" src="https://github.com/user-attachments/assets/5212e724-5b5a-4ac5-b4cd-bbf0fa49dd52" />

### Dataset used
- <a href="https://github.com/GasperMulax2/ElectroHub-Business-Project/blob/main/ElectroHub%20Store%20Data.xlsx">Dataset</a>

## 👨‍💻 Author
**Gasper Mulamula**  
Data Analyst | Business Intelligence Enthusiast  
[LinkedIn](https://www.linkedin.com/in/gasper-mulamula-97766630b) | [GitHub](https://github.com/GasperMulax2/ElectroHub-Business-Project)

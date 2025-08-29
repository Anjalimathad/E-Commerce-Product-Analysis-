# E-Commerce-Product-Analysis-
"Exploratory Data Analysis (EDA) and insights on e-commerce product sales and trends using Python and visualization tools."


An end-to-end data analysis project using Python, SQL, and Power BI to extract actionable insights from an online retail dataset.


1.Project Summary
This project explores transaction data from a UK-based online retailer to understand customer purchasing behavior, sales trends, and product performance. The final outcome includes a cleaned dataset, Python notebook, and an interactive Power BI dashboard.


2.Tools Used
Python (Pandas, Matplotlib, Seaborn)
SQL (Optional: SQLite/PostgreSQL)
Power BI
Jupyter Notebook
GitHub for version control

3.Dataset
Source: Kaggle - E-commerce Dataset
Fields: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
Duration: 1 December 2010 to 9 December 2011


4.Workflow Summary

1.Data Cleaning 
a.Removed missing values, duplicates, and canceled invoices 
b.Converted date columns and engineered new time-based features 
c.Created TotalPrice column

2.Feature Engineering 
a.Extracted year, month, day, and hour from invoice dates 
b.Grouped data to find top products, peak hours, and revenue by country

3.Exploratory Data Analysis 
a.Top-selling products 
b.Monthly revenue trends 
c.Hourly purchase frequency 
d.Sales by country

4.Power BI Dashboard 
a.KPIs: Revenue, Invoices, Quantity, Unique Customers 
b.Line chart: Monthly trends 
c.Bar chart: Orders by hour 
d.Map: Revenue by country 
e.Slicers: Date, Country, Product

5.Output 
a.Cleaned CSV for dashboarding 
b.Power BI report with interactive filters and visuals


5.Project Structure
E-commerce-product-analysis
 ├── data # Raw dataset
 ├── cleaned_data # Cleaned CSV for Power BI
 ├── notebooks # Python analysis
 ├── dashboard # Power BI file
 ├── images # Dashboard screenshots
 └── README.md # Project overview


6.Resources
 Dataset https://www.kaggle.com/datasets/carrie1/ecommerce-data
 PythonCode https://colab.research.google.com/drive/183PcmCxcy0DOwdf7mNMJoVUIp-AAJeuJ?usp=sharing

7.Author
Anjali Mathad
Data Analyst | Python  | SQL | Power BI
Email: anjalirm1503@gmail.com
Linkdin: www.linkedin.com/in/anjalimathad 





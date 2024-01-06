# Northwind-Traders

## Introduction  
The Northwind Traders database is originally a fictional sample database used by Microsoft. The Northwind database contains sales data for a fictitious company called Northwind Traders, which imports and exports specialty foods from around the world. For an updated version of this project, you can check out the [Maven Analytics Challenge](https://mavenanalytics.io/challenges/maven-northwind-challenge/24).

## About the dataset
Sales & order data for Northwind Traders, a fictitious gourmet food supplier, including information on customers, products, orders, shippers, and employees.

## Power BI Steps:
1. Know the objectives
2. Understanding the dataset
3. Classify them into Facts & Dimension tables
4. Data cleaning
5. Data visualization

## 1. Objective:
Taking up the role of a BI Developer for Northwind Traders, a global import and export company, I have been tasked with building a top-level KPI dashboard for the executive team aimed at providing quickly understanding into the company’s performance in key areas, namely:
Sales trends, Product performance, Key customers and Shipping costs.

## 2. Dataset Overviews: 
The Northwind dataset includes sample data for the following.
1. Suppliers: Suppliers and vendors of Northwind
2. Customers: Customers who buy products from Northwind
3. Employees: Employee details of Northwind traders
4. Products: Product information
5. Shippers: The details of the shippers who ship the products from the traders to the end-customers
6. Orders and Order_Details: Sales Order transactions taking place between the customers & the company

**Other information:**
-  On the discontinued column: 0 means it’s still active with the company while 1 means inactive or not a profitable product.
-  Freight charges: amount that it costs while shipping any good.
-  Shipment: There are three shipping company. To get the difference, substract shipped date from the orderDate.
-  Missing date: are basically open orders

## 3. Classified into fact & dimension table
Facts
- Orders
- Orders_details

Dimension
- Categories
- Product
- Customer
- Employee
- Shippers
- Date (added)

4. Data cleaning
- To explore this, I merged data from the “Orders”, “Order Details”, “Products” and “Suppliers” files and for each product grouped orders into buckets of orders sent to the same region as production and another for order sent to regions outside of production.

5. Data visualization
- this is the link to the interactive Power BI [report](https://app.powerbi.com/view?r=eyJrIjoiYmY3MjJhMTAtYzJiMC00YWE4LTlhNWItZmEzZWRjOGY2MDUzIiwidCI6Ijg0ZGZiOGY5LWYzMTItNDk1NC05ZTk5LWYzZjcxMTgzZDZmMSJ9) 

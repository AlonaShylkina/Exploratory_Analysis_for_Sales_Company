# Exploratory Data Analysis (EDA) of Sales Data (2010–2017)

This repository contains a project focused on performing **Exploratory Data Analysis (EDA)** on historical sales data from 2010 to 2017. The primary objective is to uncover patterns, trends, and insights that can inform future decision-making.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Environment](#environment)
- [Results](#results)
- [Conclusions](#conclusions)

---

## Project Overview

This project explores historical sales data to:
- Identify the key aspects of the company's operations.
- Identify trends over time.
- Analyze seasonal and regional sales patterns.
- Investigate relationships between variables such as product categories, revenue, and sales channels.

---

## Dataset

- **Source:** The dataset consists of 3 CSV files containing sales, products and geography data from 2010 to 2017.
- **Structure:** 
  - Events Column includes: `Order Id`, `Order Date`, `Ship Date`, `Order Priority`, `Country Code`, `Product Id`, `Sales channel`, `Units Sold`, `Unit Price`, `Unit Cost`.
  - Products Column includes: `Id`, `Item Type`.
  - Countries Column includes: `Name`, `Alpha-2`, `Alpha-3`, `Region`, `Sub-Region`.
  - Data cleaning and preparation steps are documented in the notebook.

> **Note:** Sample data is provided for illustration purposes. Sensitive or proprietary information has been removed.

---

## Environment
This project was developed in Google Colab. 
At the beginning of the project, the following Python libraries are imported:
  - `pandas`
  - `numpy`
  - `matplotlib` (includes `matplotlib.ticker`)
  - `seaborn`
  - `plotly.express`

---

## Results 
General information about the company's operations:
- total number of company orders: 1328
- total company revenue: $ 1,702,129,408.21
- total product cost: $ 1,200,694,949.21
- tatal company profit: $ 501,434,459.0
- the company works with 45 countries
- the company sells products in 12 categories, all of them are profitable 
- categories "Office Supplies" and "Beverages" were ordered the most and sold the most product units
- cotegory "Cosmetics" brought the most profit
- coregory "Office Supplies" has the highest cost and revenue 

The largest number of products were sold in the Office Supplies (617,641 units) and Beverages (613,133 units) categories.
In the same time, the Cosmetics category brought the company the largest profit - $92,723,306.17 with orders for 533,291 units. While Office Supplies remained in second place with a profit of $77,977,176.25, and the Beverages category - in 7th place with a profit of $36,776,002.72.
The most profitable category in terms of revenue and expenses is Clothes with a share of revenue of 75% and expenses of 24%, respectively.

The vast majority of the company’s business is concentrated in Europe, accounting for 89.5% of its revenue, compared to 5.5% from Asia.
By country, Andorra leads in terms of orders and revenue.
However, there is an unpleasant trend: a significant portion of orders and revenue is not geographically determined, which could complicate decisions regarding further regional development.

The company successfully operates through both offline and online channels, with the distribution of orders and profits being almost equal.

There is a wide range in the time taken to prepare orders for shipment, varying from same-day shipment to 50 days of processing. Interestingly, the company generates the highest profits from orders with the longest processing times. Therefore, we can conclude that orders and profits are not dependent on the processing time.

When looking at orders over the years, we observe a significant increase in Snack sales in 2017 — the number of units sold is 52% higher within just 7 months compared to the previous year. The best year in terms of units sold and profit is 2012. January is the most profitable month. Cosmetics is the most profitable category. We see that there are no clear leaders among the countries, but consistently every year, orders with no specified country account for one of the largest shares. However, this doesn't change the fact that Europe is the undisputed leader every year.

An interesting fact is that the company receives the most orders on weekends.

---

## Conclusions
It is important to continue developing online sales and consider expanding the company’s presence in Asian countries, as well as entering the North and South American markets.
Although there is no correlation between profit and order processing time, the company should implement a faster workflow system. Reducing processing and shipping times is always a good practice.
The company should focus on data quality to obtain complete information about the operational geography. This will help inform decisions regarding company development.

# Exploratory Data Analysis (EDA) of Sales Data (2010–2017)

This repository contains a project focused on performing **Exploratory Data Analysis (EDA)** on historical sales data from 2010 to 2017. The primary objective is to uncover patterns, trends, and insights that can inform future decision-making.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Environment](#environment)
- [Results](#results)

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

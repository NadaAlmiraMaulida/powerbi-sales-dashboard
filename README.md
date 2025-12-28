# Power BI Sales Revenue Dashboard

## Overview

This project is a sales revenue analysis dashboard developed using **Power BI**.  
The dashboard provides insights into revenue distribution across countries and manufacturers, as well as revenue trends over time.  
All datasets used in this project have been cleaned and transformed to ensure accurate and meaningful analysis.

## Project Objectives

- Analyze total sales revenue by country
- Compare revenue performance across different manufacturers
- Identify top-performing manufacturers
- Observe daily revenue trends over a specific time period
- Present sales insights through interactive visualizations

## Dataset Description

The project uses multiple datasets related to sales transactions and geographical information.

### Data Structure

The data is organized into two main categories:

#### Raw Data

Original datasets before any transformation.

#### Clean Data

Datasets that have been processed and transformed using Power BI Power Query.

Example cleaned datasets:

- geography_clean.xlsx
- sales_clean.xlsx
- product_clean.xlsx

## Data Cleaning and Transformation Process

Data preparation was performed using **Power BI Power Query**, including the following steps:

- Removing missing or invalid values
- Correcting and standardizing data types
- Removing unused or irrelevant columns
- Creating new columns where necessary for analysis
- Ensuring data consistency across related tables

The cleaned datasets are used directly in the Power BI dashboard.

## Dashboard Features

The Power BI dashboard includes the following visual components:

- **Revenue by Country and Manufacturer**  
  Displays revenue comparison across countries with manufacturer grouping
- **Revenue by Manufacturer**  
  Highlights top manufacturers based on total revenue contribution
- **Daily Revenue Trend**  
  Shows revenue patterns by day to identify trends and fluctuations
- **Total Revenue KPI**  
  Displays overall revenue as a key performance indicator

## Tools and Technologies

- Power BI Desktop
- Microsoft Excel
- Visual Studio Code
- Git
- GitHub

## Project Structure

powerbi-sales-dashboard/
│
├── data/
│ ├── raw/
│ └── clean/
│
├── dashboard/
│ └── sales-dashboard.pbix
│
├── screenshots/
│ └── dashboard-overview.png
│
├── documentation/
│ └── report.pdf
│
└── README.md

## How to Use This Project

1. Clone or download this repository
2. Open the `.pbix` file located in the `dashboard/` folder using Power BI Desktop
3. Ensure the cleaned datasets are available in the `data/clean/` folder
4. Refresh the data within Power BI if required
5. Explore the dashboard and interact with the visualizations

## Key Insights

- The USA generates the highest total revenue among all countries
- A small number of manufacturers contribute a significant portion of total revenue
- Revenue trends show noticeable daily fluctuations, indicating peak sales periods

## Author

Nada Almira Maulida

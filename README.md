# Microsoft Fabric Sales Analytics

## 📌 Project Overview

This project demonstrates an end-to-end sales analytics solution using Microsoft Fabric and Power BI. It focuses on transforming raw sales data into structured analytical tables and building an interactive dashboard to support business decision-making.

The project follows a medallion architecture and uses a dimensional data model to analyze sales performance across regions, product categories, and time periods.

## 🎯 Business Objectives

* Monitor key sales performance indicators.
* Analyze revenue and order trends over time.
* Compare sales performance across regions.
* Understand product category contributions to revenue.
* Demonstrate role-based access to regional sales data.

## 🏗️ Solution Architecture

The solution follows a medallion architecture:

1. **Bronze Layer:** Raw sales data ingestion.
2. **Silver Layer:** Data cleaning and transformation.
3. **Gold Layer:** Curated data prepared for analytical reporting.

The analytical model uses a fact-and-dimension structure to support reporting.

**High-level workflow:**

Raw Sales Data → Bronze → Silver → Gold → Analytical Model → Power BI Dashboard

Microsoft Fabric components and the exact implementation details should be documented according to the artifacts available in the project workspace.

## 📊 Dashboard Features

The Power BI report is designed to provide the following insights:

* **Total Revenue:** Overall sales revenue.
* **Total Orders:** Number of orders.
* **Average Order Value (AOV):** Average revenue per order.
* **Regional Analysis:** Revenue and order comparisons across regions.
* **Monthly Trends:** Changes in revenue and order volume over time.
* **Product Category Analysis:** Revenue contribution by product category.
* **Interactive Filters:** Explore results using report slicers.
* **Reset Functionality:** Return the report to its default filter state.

## 🛠️ Tools and Technologies

* Microsoft Fabric
* Power BI
* DAX
* SQL
* Lakehouse and Warehouse concepts
* Delta tables
* Medallion architecture
* Dimensional data modeling
* Row-level security (RLS)

*The technologies listed above describe the project approach; repository files and screenshots will indicate which components are included locally.*

## 📁 Repository Structure

```text
Microsoft-Fabric-Sales-Analytics/
├── README.md
├── Sales Analytics Project.pbix
├── Dataset/
└── Screenshots/
```

Additional folders for SQL scripts and notebooks can be added if those files are available locally and intended for publication.

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the Power BI report file in Power BI Desktop.
3. If prompted, configure the required data source or connection settings.
4. Refresh the data if the required source is accessible.
5. Explore the report using its visuals and filters.

**Note:** A `.pbix` file may depend on data sources or Fabric workspace resources that are not included in this repository. You may need access to the original environment to refresh the report or reproduce the complete solution.

## 📸 Dashboard Preview

Dashboard screenshots will be added to the `Screenshots/` folder and linked here once they are ready.

## 📚 Learning Outcomes

This project provides practical experience with:

* Designing a medallion-based analytics workflow.
* Understanding data transformation across Bronze, Silver, and Gold layers.
* Structuring data for analytical reporting.
* Building Power BI measures and interactive visualizations.
* Analyzing sales performance through business KPIs.
* Understanding row-level security and controlled report access.

## 👤 Author

**Mayank Jha**

* LinkedIn: https://www.linkedin.com/in/mayank-jha-30801823b/



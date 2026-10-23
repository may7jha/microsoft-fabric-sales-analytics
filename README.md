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

## 🏗️ Microsoft Fabric Architecture

This project explores an end-to-end sales analytics workflow using Microsoft Fabric and Power BI, following a medallion architecture and dimensional modeling principles.

### Data Flow

```text
Sales CSV Dataset
       |
       v
Data Pipeline
(Data Ingestion)
       |
       v
Bronze Layer — Raw Data
       |
       v
Silver Layer — Cleaned and Transformed Data
       |
       v
Gold Layer — Curated Analytical Data
       |
       v
Fabric Warehouse
(Fact and Dimension Tables)
       |
       v
Power BI Semantic Model
       |
       v
Interactive Sales Analytics Dashboard
```

*Note: This diagram represents the intended logical workflow. The actual implementation may differ depending on the Fabric components configured in the workspace.*

### Microsoft Fabric Components

| Component                 | Purpose                                                              |
| ------------------------- | -------------------------------------------------------------------- |
| Data Pipeline             | Orchestrates data ingestion and movement between stages.             |
| Lakehouse                 | Provides a lake-centric environment for storing and processing data. |
| Bronze Layer              | Preserves the ingested source data.                                  |
| Silver Layer              | Supports data cleaning, validation, and transformation.              |
| Gold Layer                | Contains curated data prepared for analytical use.                   |
| Warehouse                 | Supports SQL-based analytical queries and dimensional modeling.      |
| Fact and Dimension Tables | Organize business events and descriptive attributes for analysis.    |
| Semantic Model            | Defines relationships, measures, and business logic for reporting.   |
| Power BI Report           | Presents sales KPIs and interactive business insights.               |

### Dimensional Modeling

The analytical model is designed around a fact-and-dimension approach to support reporting across sales, products, regions, and time.

The final table structure and relationships should reflect the tables actually created in the Fabric environment.

### Security and Governance

Row-level security (RLS) can restrict access to sales data based on user roles or regional assignments. Security configurations should be tested before the report is shared.

### Implementation Evidence

Screenshots of the Fabric workspace, pipeline, Lakehouse tables, Warehouse, semantic model, and Power BI report can be added to the `Screenshots/` folder to demonstrate the implementation.

Only components that have actually been created and tested should be described as completed project features.



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



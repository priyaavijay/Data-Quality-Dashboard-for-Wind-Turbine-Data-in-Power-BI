# Data-Quality-Dashboard-for-Wind-Turbine-Data-in-Power-BI
As part of my internship, I developed a Data Quality Dashboard in Power BI to analyze data auditing statistics for external data sources in the Azure Synapse Data Analytics Platform. This dashboard provides insights into data integrity by performing key data quality checks on incoming datasets.

# **Data Quality Checks Implemented**

The dashboard evaluates external data sources based on the following criteria:

# Completeness

Ensures that all necessary data records are present.

Checks for missing values in critical fields.

Validates the presence of essential power plant data.

# Uniqueness

Identifies duplicate records in hourly data submissions.

Ensures data consistency across different timeframes.

# Timeliness

Tracks data arrival times and flags late or missing data submissions.

Compares expected vs. actual ingestion timestamps.

# Accuracy

Cross-verifies data against predefined benchmarks.

Ensures correct data formats and valid values.

# Architecture & Implementation

Data Source: External data ingested into Azure Synapse Analytics.

Data Processing: ETL pipelines preprocess the data before loading into Power BI.

Power BI Reports: Interactive visualizations and summary statistics for data completeness, timeliness, uniqueness, and accuracy.

# Benefits

Provides real-time insights into data health.

Automates data quality validation, reducing manual effort.

Enhances trust in external data sources by ensuring high-quality standards.

Helps identify and resolve data issues proactively.

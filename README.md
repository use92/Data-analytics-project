# Data-analytics-project
A collection of data analytics projects showcasing SQL, Python, PySpark, and Power BI for data transformation, exploratory analysis, and actionable insights.

# Healthcare Encounter ETL and Analytics Pipeline

## Overview
This project uses Maven Analytics’ synthetic Hospital Patient Records
dataset to build a reproducible healthcare data pipeline and an
analysis-ready dataset for utilization, length-of-stay, and cost reporting.

## Project Scope
Build a batch data pipeline using Databricks, PySpark, Spark SQL,
and Delta tables.

The pipeline will:
- Ingest the source CSV files.
- Apply explicit schemas and standardize dates, timestamps, and identifiers.
- Validate primary keys, relationships, and required fields.
- Separate invalid records for review.
- Create encounter-level and procedure-level analytical tables.
- Produce aggregated datasets for Power BI reporting.
- Record pipeline execution status and row counts.
- Demonstrate that rerunning the same input does not create duplicates.

Out of scope:
- Real-time streaming.
- Production clinical decision-making.
- Claims adjudication.
- Predictive modeling in the initial version.

## Business Questions
1. How do encounter volumes change over time and by encounter class?
2. What is the average inpatient length of stay, and how does it vary over time?
3. What is the average recorded encounter cost by encounter class and payer?
4. Which procedures are most frequent and contribute the most to
   recorded procedure costs?

## Data Source
Maven Analytics — Hospital Patient Records.
Synthetic healthcare data covering 2011–2022.

## Tools
Databricks, PySpark, Spark SQL, Delta tables, GitHub, and Power BI.

## Deliverables
- Reproducible ingestion and transformation code.
- Validated analytical tables.
- Data-quality and reconciliation results.
- Pipeline execution logs.
- A Power BI report answering the business questions.
- Documentation of metric definitions and limitations.

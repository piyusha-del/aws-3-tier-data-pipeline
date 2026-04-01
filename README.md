# AWS 3-Tier Data Engineering Pipeline (Medallion Architecture)

##  Project Overview

This project demonstrates the implementation of a **3-tier data architecture (Bronze, Silver, Gold layers)** using AWS services. The pipeline processes raw data into structured and analytics-ready datasets using ETL workflows and orchestration.

---

##  Architecture

The project follows the **Medallion Architecture**:

* **Bronze Layer:** Raw data ingestion from source systems into Amazon S3
* **Silver Layer:** Data cleaning, transformation, and structuring using AWS Glue
* **Gold Layer:** Curated, analytics-ready data for reporting and insights

---

##  Workflow Orchestration

* Implemented **AWS Glue Workflows and Triggers**
* Automated ETL job execution across layers
* Managed dependencies between jobs (Bronze → Silver → Gold)
* Ensured smooth and reliable pipeline execution

---

## Tech Stack

* **Cloud:** AWS (S3, Glue, Athena, Lambda)
* **Languages:** Python, SQL
* **ETL:** AWS Glue
* **Query Engine:** AWS Athena
* **Orchestration:** AWS Glue Workflows
* **Visualization (Optional):** Power BI / QuickSight

---

##  Key Features

* End-to-end **ETL pipeline design**
* Scalable **data lake architecture**
* Automated workflow orchestration
* Data validation and querying using Athena
* Layered data processing (raw → cleaned → business-ready)

---

##  Project Structure

```
project/
│── bronze/        # Raw data (S3)
│── silver/        # Cleaned data
│── gold/          # Aggregated data
│── scripts/       # Glue ETL scripts
│── workflow/      # Workflow configuration
│── queries/       # Athena SQL queries
```

---

##  How It Works

1. Raw data is ingested into **S3 (Bronze layer)**
2. AWS Glue processes and transforms data into **Silver layer**
3. Further transformations create **Gold layer datasets**
4. AWS Athena is used for querying and validation
5. Glue Workflows orchestrate the entire pipeline

---

##  Sample Use Case

* Processing customer / sales data
* Transforming raw logs into structured datasets
* Creating analytics-ready reports

---

##  Future Enhancements

* Integrate **Snowflake / Redshift**
* Add **dbt transformations**
* Implement **data quality checks & logging**
* Add **real-time streaming (Kinesis)**

---

##  Author

**Piyusha Patel**
Aspiring Data Engineer

---

##  If you like this project

Give it a ⭐ on GitHub and connect with me!

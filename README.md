# 🎓 Capstone Project: Data Analytics in Modern Corporate Business
**International Hellenic University**

---

## 📝 Project Overview
This repository contains the source code and automation scripts for my final Capstone Project. The project establishes a robust end-to-end data engineering and analytics pipeline, moving data from a transactional database into a cloud data warehouse for transformation, automation, and business intelligence reporting.

---

## 📌 Architecture & Tech Stack

### 1. Data Source
* **Database:** `Pagila` transactional database.
* **Environment:** Hosted in a **PostgreSQL** environment.

### 2. Data Replication
* **Ingestion:** Continuous data replication (CDC) from PostgreSQL to the cloud.
* **Tooling:** **Google Datastream** seamlessly streams data into the data warehouse.

### 3. Data Transformation & Analysis
* **Data Warehouse:** **Google BigQuery** handles heavy data transformations and analytical queries.
* **Development:** **Jupyter Notebooks (`.ipynb`)** used locally for initial prototyping, reading directly from BigQuery.
* **Production/ETL:** Notebooks are converted to **Python (`.py`)** scripts to manage advanced ETL tasks and automation workflows.
* **Orchestration:** Python scripts are automated and scheduled using **Cron jobs**.

### 4. Version Control
* **Tool:** **Git** & **GitHub**.
* **Scope:** Version tracking for all production-ready Python (`.py`) automation scripts and project documentation.

### 5. Data Visualization
* **Dashboards:** Transformed data is connected to **Tableau Cloud** and **Metabase** to build interactive business intelligence dashboards.

---

## 📁 Repository Structure
* `/scripts` — Contains the productionized `.py` files used for ETL and automation.
* `/notebooks` — Contains the original `.ipynb` files used for data exploration and prototyping.

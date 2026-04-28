# GoodCabs Medallion Pipeline

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-0033A0?style=for-the-badge&logo=databricks&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**A production-grade Data Pipeline** built with **Databricks Delta Live Tables (DLT)** following the **Medallion Architecture** (Bronze → Silver → Gold).

---

### 🎯 Project Overview

This project implements a modern **Lakehouse Data Pipeline** for GoodCabs (Transportation/Taxi company) to process trips data efficiently and reliably.

It follows the industry-standard **Medallion Architecture** to ensure:
- High data quality
- Incremental processing
- Clear data lineage
- Scalable and maintainable layers

---

### 🏗️ Architecture

| Layer     | Purpose                          | Key Features |
|-----------|----------------------------------|--------------|
| **Bronze**    | Raw data ingestion              | Metadata, schema evolution, CDF enabled |
| **Silver**    | Cleaned & validated data        | Transformations, Data Quality, SCD Type 1 |
| **Gold**      | Business-ready aggregated data  | (Coming soon) |

---

### ✨ Key Features

- ✅ **Delta Live Tables (DLT)** pipeline with full orchestration
- ✅ Data Quality expectations and validation
- ✅ Incremental loading using **Streaming Tables**
- ✅ **Auto CDC Flow** with SCD Type 1 (Upsert)
- ✅ Change Data Feed (CDF) enabled
- ✅ Auto Optimization & Compaction
- ✅ Unity Catalog integration
- ✅ Clean separation between staging and target tables

---

### 🛠️ Tech Stack

- **Databricks** (Delta Live Tables + Unity Catalog)
- **Delta Lake**
- **PySpark**
- **Medallion Architecture**
- **SCD Type 1** (Slowly Changing Dimension)


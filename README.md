# **Delivery SLA Breach Analyzer**

**Author:** Sakshi Patil

## **Project Title**

**Delivery SLA Breach Analyzer – An End-to-End Azure Data Engineering Pipeline for Incremental Data Ingestion, Medallion Architecture, and Delivery Performance Analytics**

---

# **Project Summary**

Delivery SLA Breach Analyzer is an end-to-end Azure Data Engineering solution developed to analyze e-commerce delivery performance and identify Service Level Agreement (SLA) breaches using approximately **10,000 simulated order records**. The project demonstrates how modern cloud-based data engineering practices can automate the ingestion, transformation, and preparation of operational data for business analytics.

The solution implements a **metadata-driven, incremental ingestion framework** using **Azure Data Factory**, where watermark-based change detection enables efficient loading of only new or modified records. A single dynamic **ForEach** pipeline orchestrates ingestion across multiple source tables, creating a scalable and reusable ETL framework.

The ingested data is stored and transformed in **Azure Databricks** following the **Medallion Architecture (Bronze, Silver, and Gold)**. Parameterized **PySpark** notebooks perform data cleansing, validation, joins, and business transformations while leveraging **Delta Lake** for ACID-compliant storage and efficient append/overwrite operations. The final Gold layer produces analytics-ready datasets that help identify delivery delays across states, product categories, payment methods, and other business dimensions, enabling operational monitoring and data-driven decision-making.

This project showcases practical implementation of Azure cloud services, scalable ETL design patterns, Delta Lake, and distributed data processing using PySpark.

---

# **Project Conclusion**

The Delivery SLA Breach Analyzer successfully demonstrates the design and implementation of a modern, scalable Azure Data Engineering pipeline capable of processing incremental data efficiently. By combining **Azure Data Factory** for metadata-driven orchestration with **Azure Databricks** and **Delta Lake** for distributed data processing, the project establishes a reusable and production-oriented ETL framework following the Medallion Architecture.

The solution highlights industry-standard practices such as incremental loading, parameterized pipelines, dynamic orchestration, reusable notebook development, and layered data architecture. The resulting curated datasets provide meaningful business insights into delivery SLA performance, enabling stakeholders to monitor operational efficiency, identify recurring delivery delays, and support data-driven logistics optimization. Overall, the project demonstrates hands-on expertise in Azure Data Engineering, cloud-based ETL development, PySpark, Delta Lake, and scalable data pipeline design.

---

# **Tech Stack Used**

**Cloud Platform**

* Microsoft Azure

**Data Integration**

* Azure Data Factory (ADF V2)

**Data Processing**

* Azure Databricks

**Programming**

* Python
* PySpark

**Data Storage**

* Azure Data Lake Storage Gen2 (ADLS Gen2)

**Data Format**

* Delta Lake

**Architecture**

* Medallion Architecture (Bronze, Silver, Gold)

**ETL Design**

* Metadata-driven ETL
* Incremental Data Loading
* Watermark-based Change Detection
* Dynamic ForEach Pipelines
* Parameterized PySpark Notebooks

**Data Transformation**

* Data Cleansing
* Multi-table Joins
* Business Aggregations
* Delta Append & Overwrite Operations

**Version Control**

* Git & GitHub

**Development Environment**

* Azure Portal
* Azure Data Factory Studio
* Azure Databricks Workspace
* VS Code
* Git Bash

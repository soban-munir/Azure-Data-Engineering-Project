# Data Engineering Project with Medallion Architecture on Azure

## 📌 Project Overview

This project demonstrates a complete **Data Engineering pipeline** built on **Microsoft Azure** using the **Medallion Architecture (Bronze, Silver, Gold layers)**. The project covers data ingestion, transformation, and analytics using modern data engineering tools and practices.

The main goal of this project is to showcase how raw data can be ingested, cleaned, transformed, and optimized for analytics using **PySpark, Delta Lake, and Databricks**.

---

## 🏗️ Architecture

The project follows the **Medallion Architecture**:

* **Bronze Layer**: Stores raw data in its original format (Parquet/JSON/CSV).
* **Silver Layer**: Cleansed and transformed data (removes duplicates, standardizes schema, applies business rules).
* **Gold Layer**: Aggregated and analytics-ready data for reporting and dashboards.

![Medallion Architecture](./images/medallion_architecture.png)

---

## ⚙️ Tech Stack

* **Microsoft Azure** (Storage, Databricks)
* **Azure Data Lake Storage (ADLS)**
* **Azure Databricks** (Delta Live Tables, PySpark)
* **Delta Lake & Delta Tables**
* **Python & SQL**
* **Git & GitHub** for version control

---

## 📂 Repository Structure

```
├── notebooks/                # Databricks notebooks (ETL scripts)
├── diagrams/                 # Architecture & pipeline diagrams
└── README.md                 # Project documentation
```

---

## 🚀 Features

* Implemented **Medallion Architecture** (Bronze → Silver → Gold)
* Used **PySpark** for data cleaning, transformations, and aggregations
* Created **Delta Tables** for efficient storage and querying
* Built **Data Pipelines** using **Delta Live Tables**
* Stored and processed data on **Azure Data Lake Storage (ADLS)**
* Managed project with **Git & GitHub**

---

## 🖼️ Screenshots

Below are some screenshots and diagrams of the project:

* Medallion Architecture Diagram
* Data Pipeline in Databricks
* Delta Tables Output
* DBFS layers list
* Star Schema
* Jobs

(All images are available inside the `diagrams/` folder.)

---

## 📊 Applications

* Can be extended for **real-time streaming data pipelines**
* Suitable for **Data Warehousing & Analytics**
* Forms the base for **Machine Learning workflows**
* Scalable for **Enterprise Data Lakehouse** solutions

---

## 🔑 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/soban-munir/Azure-Data-Engineering-Project.git
   ```
2. Upload the notebooks to **Azure Databricks**
3. Configure access to your **Azure Data Lake Storage (ADLS)**
4. Run the notebooks step by step:

   * Bronze Layer (Raw Data Ingestion)
   * Silver Layer (Cleaning & Transformation)
   * Gold Layer (Aggregation & Analytics)

---

## 📌 Future Improvements

* Add **real-time streaming ingestion** using Event Hubs or Kafka
* Automate pipelines with **Azure Data Factory (ADF)**
* Connect with **Power BI** for dashboards

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## 📧 Contact

**Author:** Soban Munir
For queries, reach out via GitHub or LinkedIn.

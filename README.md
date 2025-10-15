# 🏗️ Modern Data Warehouse with SQL Server (Medallion Architecture)

## 📘 Overview  
This project implements a **Modern Data Warehouse (DWH)** using **SQL Server**, following the **Medallion Architecture** — a layered approach that improves data quality, governance, and scalability.

---

## 🧱 Architecture  
The DWH is organized into three core layers:

| Layer | Purpose | Description |
|-------|----------|-------------|
| **Bronze (Raw)** | Ingestion | Stores raw data from source systems with minimal transformation. |
| **Silver (Processed)** | Cleaning & Standardization | Applies data quality rules, joins, and transformations to create clean, standardized datasets. |
| **Gold (Presentation)** | Analytics-Ready | Contains aggregated, business-ready tables for reporting, BI, and ML consumption. |

---

## ⚙️ Tech Stack  
- **SQL Server 2022** – Core DWH and transformation engine  
- **Azure Data Studio / SSMS** – Development and management  
- **ETL/ELT** – Implemented via stored procedures or SQL Agent jobs  
- **Version Control** – Git + GitHub  

---

## 📂 Project Structure  

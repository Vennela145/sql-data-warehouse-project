# 📊 Data Warehouse & Analytics Project

> *Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Language](https://img.shields.io/badge/Language-T--SQL-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## 🎯 Quick Overview

This project demonstrates an **end-to-end data warehousing solution** following the **Medallion Architecture** pattern. From raw data ingestion to actionable analytics, it covers:

- ✅ **Data Architecture** - Medallion pattern (Bronze → Silver → Gold)
- ✅ **ETL Pipelines** - Extract, transform, and load from ERP & CRM systems
- ✅ **Data Modeling** - Star schema with fact and dimension tables
- ✅ **Analytics & Reporting** - SQL-based insights on sales, customers, and products

---

## 🏗️ Architecture Flow

```
┌─────────────────────────────────────────────────────────────┐
│                    DATA WAREHOUSE FLOW                       │
├─────────────────────────────────────────────────────────────┤
│                                                               │
│  CSV Files (ERP & CRM)                                       │
│      ↓                                                        │
│  ┌─────────────────────────────────────────────────────┐    │
│  │  BRONZE LAYER: Raw Data Ingestion                   │    │
│  │  • Data loaded as-is from source systems           │    │
│  │  • No transformations applied                      │    │
│  └─────────────────────────────────────────────────────┘    │
│      ↓                                                        │
│  ┌─────────────────────────────────────────────────────┐    │
│  │  SILVER LAYER: Data Cleansing & Transformation     │    │
│  │  • Standardization & normalization                 │    │
│  │  • Data quality checks                             │    │
│  │  • Remove duplicates & handle null values          │    │
│  └─────────────────────────────────────────────────────┘    │
│      ↓                                                        │
│  ┌─────────────────────────────────────────────────────┐    │
│  │  GOLD LAYER: Business-Ready Analytics              │    │
│  │  • Star schema design                              │    │
│  │  • Fact & dimension tables                         │    │
│  │  • Optimized for reporting & BI tools              │    │
│  └─────────────────────────────────────────────────────┘    │
│      ↓                                                        │
│  📈 Analytics, Dashboards & Reports                         │
│                                                               │
└─────────────────────────────────────────────────────────────┘
```

---

## 📂 Project Structure

```
sql-data-warehouse-project/
│
├── 📁 datasets/                    # Raw CSV files (ERP & CRM data)
│
├── 📁 docs/                        # Project documentation
│   ├── data_architecture.drawio    # Architecture diagram
│   ├── data_models.drawio          # Star schema design
│   ├── data_flow.drawio            # Data flow diagram
│   ├── etl.drawio                  # ETL techniques
│   ├── data_catalog.md             # Data dictionary
│   └── naming-conventions.md       # Naming standards
│
├── 📁 scripts/                     # SQL scripts (T-SQL)
│   ├── bronze/                     # Raw data ingestion
│   ├── silver/                     # Data cleaning & transformation
│   └── gold/                       # Analytics & reporting
│
├── 📁 tests/                       # Data quality tests
│
├── README.md                       # This file
├── LICENSE                         # MIT License
├── .gitignore
└── requirements.txt
```

---

## 🚀 Key Features

| Feature | Description |
|---------|------------|
| **📥 Data Integration** | Consolidate ERP & CRM data from multiple CSV sources |
| **🧹 Data Quality** | Automated cleansing, standardization & validation |
| **⭐ Star Schema** | Optimized for OLAP queries and reporting |
| **📊 SQL Analytics** | Customer behavior, product performance & sales trends |
| **📖 Documentation** | Data catalog, naming conventions & flow diagrams |
| **🧪 Testing** | Data quality checks & validation scripts |

---

## 🛠️ Tech Stack & Tools

All free and open-source! 🎉

| Tool | Purpose | Download |
|------|---------|----------|
| **SQL Server Express** | Database engine | [Download](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) |
| **SQL Server Management Studio (SSMS)** | Query & management tool | [Download](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms) |
| **Git & GitHub** | Version control | [GitHub](https://github.com/) |
| **Draw.io** | Architecture & diagrams | [Draw.io](https://www.drawio.com/) |
| **Notion** | Project management | [Notion](https://www.notion.com/) |

---

## 💡 What You'll Learn

Perfect for building expertise in:

```
🔹 SQL Development (T-SQL)
🔹 Data Architecture & Design Patterns
🔹 ETL Pipeline Development
🔹 Data Modeling & Star Schema
🔹 Data Quality & Governance
🔹 Analytics & Business Intelligence
```

---

## 🎯 Project Objectives

### Phase 1: Data Warehouse Development
- ✨ Design medallion architecture (Bronze → Silver → Gold)
- ✨ Load ERP & CRM data into SQL Server
- ✨ Implement data quality & cleansing
- ✨ Create business-ready data models

### Phase 2: Analytics & Reporting
- 📊 Customer segmentation & behavior analysis
- 📊 Product performance metrics
- 📊 Sales trends & forecasting
- 📊 KPI dashboards

---

## 📖 Documentation

| Document | Purpose |
|----------|---------|
| [Data Catalog](docs/data_catalog.md) | Field descriptions & metadata |
| [Requirements](docs/requirements.md) | Detailed project specifications |
| [Naming Conventions](docs/naming-conventions.md) | Consistent naming standards |

---

## 🚦 Getting Started

1. **Clone Repository**
   ```bash
   git clone https://github.com/Vennela145/sql-data-warehouse-project.git
   cd sql-data-warehouse-project
   ```

2. **Setup Database**
   - Install SQL Server Express
   - Install SSMS
   - Open scripts in `scripts/bronze/` and execute

3. **Load Data**
   - Use CSV files from `datasets/` folder
   - Execute Bronze layer scripts first

4. **Transform Data**
   - Run Silver layer transformation scripts

5. **Create Analytics**
   - Execute Gold layer scripts for analytics

---

## 📈 Analytics Insights

The project delivers actionable insights on:

- **👥 Customer Behavior**: Segmentation, lifetime value, purchase patterns
- **📦 Product Performance**: Top sellers, inventory metrics, margins
- **💰 Sales Trends**: Revenue, growth rates, seasonal patterns

---

## 📄 License

This project is licensed under the **[MIT License](LICENSE)** – feel free to use, modify, and share with attribution.

---

## 🌟 About

Hi! 👋 I'm **Vennela Salvaji**, a data science student passionate about making data work enjoyable and impactful. This project showcases real-world data warehousing practices and best practices.

---

<div align="center">

**⭐ If you found this helpful, please star the repository!**

[Share Your Feedback](https://github.com/Vennela145/sql-data-warehouse-project/issues) | [Explore More Projects](https://github.com/Vennela145)

</div>

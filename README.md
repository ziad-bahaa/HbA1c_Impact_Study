# 🏥 HbA1c Impact Study: 30-Day Hospital Readmission Analysis

<div align="center">

[![Status](https://img.shields.io/badge/Status-Completed-success.svg)]()
[![Python](https://img.shields.io/badge/Python-3.8%252B-blue.svg)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-Server-orange.svg)]()
[![Power BI](https://img.shields.io/badge/Power%252BI-Dashboard-yellow.svg)]()
[![DEPI Graduation Project](https://img.shields.io/badge/DEPI-Graduation%20Project-purple.svg)]()

*A comprehensive data analytics project examining the association between HbA1c testing and 30-day hospital readmissions among diabetic patients.*

</div>

---

## 📌 Table of Contents
- [About the Project](#-about-the-project)
- [Project Architecture & Workflow](#-project-architecture--workflow)
- [Repository Structure](#-repository-structure)
- [Tech Stack](#-tech-stack)
- [Key Features & Analysis](#-key-features--analysis)
- [Dashboard Preview](#-dashboard-preview)
- [Documentation & Resources](#-documentation--resources)
- [How to Run the Project](#-how-to-run-the-project)
- [Project Team & Acknowledgments](#-project-team--acknowledgments)

---

## 📖 About the Project
Hospital readmissions within 30 days are a critical metric for healthcare quality and patient care efficiency, especially for chronic conditions like diabetes. This project—completed as part of the **Digital Egypt Pioneers Initiative (DEPI)**—investigates whether regular HbA1c testing and specific clinical factors significantly impact 30-day readmission rates.

Using a robust pipeline covering **SQL** (ETL & Modeling), **Python** (Advanced EDA & Statistical Modeling), and **Power BI** (Interactive Dashboard), we transformed raw hospital data into actionable healthcare insights.

---

## 🔄 Project Architecture & Workflow
1. **Data Ingestion & Staging:** Raw CSV data loaded into SQL Server staging tables.
2. **Data Modeling & ETL:** Building a Star Schema (Dimension and Fact tables) and creating clean views and procedures.
3. **Exploratory Data Analysis (EDA) & Statistics:** Using Python for data cleaning, Chi-Square tests of independence, and Logistic Regression modeling.
4. **Visualization:** Developing an interactive Power BI dashboard to track key clinical and demographic metrics.

---

## 📁 Repository Structure

```text
HbA1c_Impact_Study/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── data/
│   ├── raw/                  # Original raw datasets (diabetic data & mapping)
│   └── processed/            # Cleaned datasets ready for analysis
│
├── sql/
│   ├── database/             # Database creation scripts
│   ├── tables/               # Staging, Dimension, and Fact tables
│   ├── etl/                  # Data loading and transformation scripts
│   ├── views/                # Analytical SQL views
│   ├── procedures/           # Stored procedures
│   └── analysis/             # SQL queries for readmission & HbA1c insights
│
├── python/
│   ├── data_cleaning/        # Data pre-processing notebooks
│   ├── eda/                  # Exploratory Data Analysis notebooks
│   └── analysis/             # Statistical tests & Logistic Regression models
│
├── powerbi/
│   ├── dashboard/            # Power BI file (.pbix)
│   └── screenshots/          # Dashboard preview images
│
├── documentation/            # Project proposals, data dictionary, ERD, reports
├── presentation/             # Final PowerPoint presentation
└── video/                    # Project demo video (or link)

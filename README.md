# HbA1c_Impact_Study
Data analytics project examining the association between HbA1c testing and 30-day hospital readmission among diabetic patients, using SQL, Python, and Power BI. DEPI Graduation Project.

hba1c-impact-study/
│
├── README.md
├── .gitignore
├── requirements.txt
│
├── data/
│   ├── raw/
│   │   ├── diabetic_data.csv
│   │   └── IDS_mapping.csv
│   └── processed/
│       ├── diabetic_data_clean.csv
│       └── icd9_diagnosis_groups.csv
│
├── sql/
│   ├── database/
│   │   └── 01_create_database.sql
│   ├── tables/
│   │   ├── 02_create_staging_table.sql
│   │   ├── 03_create_dimension_tables.sql
│   │   └── 04_create_fact_table.sql
│   ├── etl/
│   │   ├── 05_load_raw_data.sql
│   │   └── 06_clean_and_transform.sql
│   ├── views/
│   │   ├── vw_readmission_overview.sql
│   │   ├── vw_hba1c_impact.sql
│   │   ├── vw_demographics.sql
│   │   └── vw_clinical_factors.sql
│   ├── procedures/
│   │   └── sp_refresh_clean_data.sql
│   └── analysis/
│       ├── 01_readmission_rate_queries.sql
│       ├── 02_hba1c_analysis_queries.sql
│       └── 03_subgroup_analysis_queries.sql
│
├── python/
│   ├── data_cleaning/
│   │   └── 01_data_cleaning.ipynb
│   ├── eda/
│   │   └── 02_eda.ipynb
│   └── analysis/
│       ├── 03_chi_square_tests.ipynb
│       └── 04_logistic_regression.ipynb
│
├── powerbi/
│   ├── dashboard/
│   │   └── hba1c_impact_dashboard.pbix
│   └── screenshots/
│       └──  .png)
│
├── documentation/
│   ├── project_proposal.docx            ✅
│   ├── data_dictionary.xlsx             ✅
│   ├── milestones_tracker.xlsx          ✅
│   ├── er_diagram.png
│   ├── data_cleaning_log.md
│   ├── kpi_definitions.md
│   ├── egypt_context_brief.md
│   ├── analysis_report.docx
│   ├── user_manual.md
│   └── final_report.docx
│
├── presentation/
│   └── hba1c_impact_study_final.pptx
│
└── video/
    └── project_demo.mp4  (أو رابط في الـ README لو الملف كبير)

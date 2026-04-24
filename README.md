AI Job Market Analysis: Impact of AI on Employment, Salaries, and Workforce Trends
Project Overview

This project analyzes the impact of Artificial Intelligence (AI) on job markets across industries. The goal is to understand how AI influences job growth, salary patterns, automation risk, and workforce structure, and to derive actionable insights for data-driven decision-making.

The project follows a structured data pipeline, including data extraction, cleaning, exploratory data analysis (EDA), statistical analysis, and final data preparation for dashboard visualization.

Objectives
Identify high-growth industries and job roles influenced by AI
Analyze salary patterns across industries and experience levels
Evaluate automation risk and its impact on job stability
Understand workforce trends including education, experience, and remote work
Prepare structured datasets for interactive dashboard visualization
Dataset Description
Dataset: AI Job Trends Dataset
Records: ~30,000 job entries
Format: Structured tabular data
Key Features
Job Title
Industry
Job Openings (2024, 2030)
Median Salary (USD)
AI Impact Level
Automation Risk (%)
Required Education
Required Experience (Years)
Remote Work Ratio (%)
Project Structure
SectionC_Group2_AI-Job-Market-Analysis/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   └── ai_job_trends_dataset.csv
│   └── processed/
│       ├── cleaned_jobs.csv
│       ├── kpi_data.csv
│       ├── industry_summary.csv
│       ├── job_summary.csv
│       ├── salary_summary.csv
│       ├── risk_summary.csv
│       ├── workforce_summary.csv
│       ├── remote_summary.csv
│       └── final_dashboard_data.csv
│
├── notebooks/
│   ├── 01_extraction.ipynb
│   ├── 02_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_statistical_analysis.ipynb
│   └── 05_final_load_prep.ipynb
│
├── tableau/
│   ├── screenshots/
│   └── dashboard_links.md
│
├── reports/
│   ├── project_report.pdf
│   └── presentation.pdf
│
└── docs/
    └── data_dictionary.md
Methodology
1. Data Extraction
Dataset loaded using Python (Pandas)
Initial inspection of structure, data types, and missing values
2. Data Cleaning and Transformation
Standardization of column names
Handling missing values
Data type corrections
Feature engineering:
Growth Rate
Risk Categories (Low, Medium, High)
Growth Categories
3. Exploratory Data Analysis (EDA)

EDA is structured into four business-focused sections:

Job Growth & Demand
Growth rate distribution
Industry-wise growth comparison
Identification of top growing and declining jobs
AI impact vs growth
Salary Analysis
Salary distribution
Salary variation across industries
Experience vs salary
AI impact vs salary
Automation Risk
Risk distribution
Risk vs job status
Risk vs growth
Risk segmentation
Workforce Structure
Education distribution
Experience trends
Remote work analysis
Remote vs salary and growth
4. Statistical Analysis
Correlation analysis between key variables
Hypothesis testing:
AI impact vs salary
AI impact vs growth
Automation risk vs job decline
Education vs salary
Regression models:
Salary prediction model
Growth rate prediction model
5. Final Data Preparation (Final Load Prep)
Column standardization
Feature engineering
KPI creation
Aggregated datasets for dashboards:
Industry summary
Job summary
Salary summary
Risk summary
Workforce summary
Remote work summary
Export of Tableau-ready CSV files
Dashboards (Tableau)

The project includes four dashboards:

Job Growth & Future Demand
Salary Drivers & AI Impact
Automation Risk & Job Vulnerability
Workforce Trends & Hiring Strategy

Each dashboard is aligned with business questions derived from EDA and validated through statistical analysis.

Key Insights
AI-driven roles show significantly higher growth rates
High AI impact roles command higher salaries
Jobs with high automation risk are more likely to decline
Mid-level experience roles dominate job demand
Remote work is increasingly associated with competitive salaries
Tools and Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook / Google Colab
Tableau Public
Git and GitHub
How to Run
Clone the repository
Open notebooks in Jupyter or Google Colab
Run notebooks in order:
01 → 02 → 03 → 04 → 05
Use generated CSV files in Tableau
Current Status
Data extraction and cleaning: Completed
Exploratory data analysis: Completed
Statistical analysis: Completed
Final data preparation: Completed
Dashboard development: In progress
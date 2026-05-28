# Nexloom SaaS Data Cleaning & SQL Transformation Project

## Overview
This project demonstrates an end-to-end **SQL-based data cleaning workflow** for a SaaS company dataset.  
It highlights data validation, transformation, and restructuring techniques used to prepare raw operational data for analytics, reporting, and BI dashboards.

The goal is to showcase proficiency in:
- Building structured **data-cleaning pipelines**
- Applying **SQL transformations** to standardize and normalize SaaS datasets
- Producing **clean, analysis-ready tables** for downstream use
- Documenting a clear, repeatable **data quality process**

---

## Project Architecture

### Data Flow
1. **Raw Excel Files** → Initial uncleaned SaaS operational data  
2. **SQL Cleaning Scripts** → Standardization, validation, and transformation  
3. **Clean Output Tables** → Ready for BI tools, modeling, or reporting  

### Database Schema (Post-Cleaning)
- **Core Cleaned Tables:**  
  - `clean_users`  
  - `clean_subscriptions`  
  - `clean_transactions`  
  - `clean_products`  
  - `clean_usage_logs`  

- **Supporting Tables:**  
  - Lookup tables  
  - Validation tables  
  - Audit logs (where applicable)

These tables were cleaned to remove duplicates, fix inconsistent formatting, standardize date fields, and ensure referential integrity across the dataset.

---

## Key Features
- **Data Cleaning:** Removed nulls, standardized formats, validated IDs, and corrected inconsistent values.  
- **SQL Transformations:** Applied joins, CASE logic, date conversions, and normalization techniques.  
- **Quality Checks:** Ensured referential integrity and consistent primary/foreign key relationships.  
- **Documentation:** Organized scripts and outputs for transparency and reproducibility.

---

## Cleaned Output Tables
1. **Users Table** – Standardized user profiles and metadata  
2. **Subscriptions Table** – Cleaned subscription lifecycle and status fields  
3. **Transactions Table** – Validated revenue, timestamps, and transaction types  
4. **Product Table** – Normalized product names, categories, and pricing  
5. **Usage Logs** – Cleaned event-level SaaS usage data  

---

## Tech Stack
| Tool | Purpose |
|------|----------|
| **Excel** | Raw SaaS data source |
| **SQL** | Data cleaning, transformation, and validation |
| **Copilot AI** | Assisted documentation and workflow optimization |

---

## Setup Instructions
1. Place raw Excel files into the `/Raw Files` directory.  
2. Run the SQL scripts in `/Data Cleaning` in the recommended order.  
3. Export or query the cleaned tables from `/Cleaned Datasets`.  
4. Use the cleaned outputs for BI dashboards, modeling, or further analysis.

---

## Repository Structure

data-cleaning-sql-saas-project/
│
├── Raw Files/               # Original SaaS data exports
├── Data Cleaning/           # SQL scripts for cleaning and transformation
├── Cleaned Datasets/        # Final cleaned tables ready for analysis
├── Video-walkthrough/       # Optional walkthrough of the cleaning workflow
└── README.md                # Project overview and setup guide


---

## Outcomes
- Delivered a **fully cleaned SaaS dataset** ready for analytics.  
- Demonstrated strong SQL skills in cleaning, validation, and transformation.  
- Created a **repeatable, documented workflow** for future data quality projects.  
- Established a foundation for BI dashboards, forecasting models, and KPI reporting.

---

## 🔗 Author
**Samuel John-Maxwell**  
Charlottetown, PE, Canada  
*Data Analytics & Process Improvement Professional*





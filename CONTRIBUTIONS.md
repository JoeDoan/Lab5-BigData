# Week 5 Contributions (Required)

## Project Title: Lab 5 Snowflake Integration

### Member 1: Joe Doan
- Responsibilities:
  - Lead developer: Architected the end-to-end data pipeline from local CSVs to Snowflake.
  - Designed the Snowflake database schema (`MASTER_CLAUSE`, `MASTER_CLAUSE_DATA`) and implemented the internal staging setup.
  - Implemented the core SQL scripts for schema creation, staging, complex JOIN queries, and derived analysis views.
  - Oversaw and integrated the work of other members to ensure seamless end-to-end flow.
- Evidence (PR/commits):
  - Commits related to `sql/01_create_schema.sql` and `sql/02_stage_and_load.sql`.
- Tested:
  - Verified Snowflake internal stages, table creations, view generations, and the end-to-end application runtime.

### Member 2: Manan Koradiya
- Responsibilities:
  - Python scripts for data extraction, transformation, and load (ETL).
  - Configured Snowflake Python connector for local CSV uploads to stage.
- Evidence (PR/commits):
  - Commits related to Python loading scripts and `.env` setup.
- Tested:
  - Executed and validated Python data pipeline and data consistency in Snowflake.

### Member 3: Aditya Naredla
- Responsibilities:
  - Developed the Streamlit dashboard to visualize the dataset from Snowflake.
  - Integrated SQL queries within the application for live data reporting.
- Evidence (PR/commits):
  - Commits related to Streamlit App and frontend UI components.
- Tested:
  - Validated dashboard rendering, query execution times, and UI interactivity.

### Member 4: Ruixuan Hou
- Responsibilities:
  - Established end-to-end monitoring and logging for data pipelines.
  - Optimized complex SQL queries and documented the end-to-end architecture flow.
- Evidence (PR/commits):
  - Commits improving logging mechanisms and documentation (`README.md`).
- Tested:
  - Monitored application logs and ensured no silent failures during the pipeline execution.

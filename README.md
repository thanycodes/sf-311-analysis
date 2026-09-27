# SF 311 Analysis

**Question:** Where and why does San Francisco respond slowly to 311 service requests?

**Goal:** Help the city decide where to focus to cut response times.

**Data:** SF 311 Cases, DataSF — ~1 year of public service request records.

## Stack
Python 3.12+, Pandas, DuckDB, Matplotlib, Jupyter, Streamlit

## Project Structure
```
sf-311-analysis/
├── data/        # raw + cleaned data (not tracked by git)
├── notebooks/   # exploration and cleaning
├── sql/         # SQL queries, one file per question
└── app/         # Streamlit dashboard (Phase 5)
```

## Phases
1. Setup
2. Ingest & Clean
3. Model in SQL
4. Analyze
5. Visualize
6. Communicate

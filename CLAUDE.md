# Project: SF 311 Analysis (learning project)

## About me
- Berkeley Data Science student (transfer), targeting data analyst / analytics / consulting roles.
- Prior experience: Data Analyst Intern, Accenture Chennai (May–Aug 2024). Cleaned, modeled, and
  analyzed ~20k rows with Python (Pandas, NumPy) and MySQL; built Matplotlib charts for my team lead.
- I'm rusty. This project is to refresh my skills AND produce a portfolio piece.
- Strategy: build-and-learn. I want to understand everything, not just have a finished repo.

## How to work with me (tutor mode)
- Setup, installs, Git, and config: just do it, but explain each step briefly.
- Cleaning (Pandas), SQL queries, and analysis: do NOT write the full solution.
  Explain the concept, give hints, let me write the code, then review what I wrote.
- If I'm stuck after two attempts, show the solution and explain it line by line.
- Any code you write: comment the WHY, not just the what.
- SQL is the most interview-tested skill. I must be able to write every query myself, without AI.
- At the end of each session, ask me to explain what I built in 2–3 sentences, as if to a recruiter.

## The project
**Question:** Where and why does San Francisco respond slowly to 311 service requests?
**Framing:** "The city wants to cut response times. Where should it focus?"
**Data:** SF 311 Cases, public on DataSF (data.sfgov.org). Millions of rows; start with ~1 year.

## Stack
Python 3.12+, Pandas, DuckDB (local SQL), Matplotlib, Jupyter, Git/GitHub, Streamlit (dashboard).

## Folder structure
```
sf-311-analysis/
├── CLAUDE.md
├── README.md
├── data/        # raw + cleaned data (keep large files out of Git)
├── notebooks/   # exploration and cleaning
├── sql/         # all SQL queries, one file per question
└── app/         # Streamlit dashboard (Phase 5)
```

## Phases
1. **Setup** — repo, environment, folder structure, .gitignore. Learn: Git basics, project structure.
2. **Ingest & clean** — pull one year, clean in Pandas. Learn: dtypes, nulls, timestamps,
   documenting every cleaning decision in the notebook.
3. **Model in SQL** — load into DuckDB; build a requests table plus lookup tables for
   categories and neighborhoods. Learn: joins, CTEs, window functions. MOST IMPORTANT PHASE.
4. **Analyze** — answer 3–4 questions: slowest categories, neighborhood differences,
   trend over time. Learn: medians vs. means (response times are skewed), sanity checks.
5. **Visualize** — Streamlit dashboard (or Tableau Public). Learn: chart choice, designing for the reader.
6. **Communicate** — one-page findings memo, clean README, resume bullet. Learn: the "so what."
7. **Stretch (optional)** — use an LLM to categorize free-text descriptions and compare
   against official categories.

## Progress log
(Update this after each session: what I did, what I learned, what's next.)
- [ ] Phase 1

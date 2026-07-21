# IBM Data Analyst Capstone: Stack Overflow Developer Survey Analysis

Analysis of a 65,000-row developer survey dataset to uncover trends in compensation, technology adoption, and job satisfaction. Built as the capstone project for the IBM Data Analyst Professional Certificate.

View the interactive dashboard: https://datastudio.google.com/s/rUfiNSdiJWk

## Overview

This project cleans, analyzes, and visualizes results from the Stack Overflow Developer Survey to answer three questions:
- What factors are most associated with higher developer compensation?
- How does technology adoption vary across experience levels and regions?
- What patterns in the data relate to job satisfaction?

## Tools & Methods

- **Python** (pandas, matplotlib, seaborn) — data cleaning, transformation, exploratory analysis
- **SQL** — querying and aggregating survey responses
- **Looker Studio** — interactive dashboard for compensation, tech adoption, and satisfaction trends

## Process

1. **Data cleaning** — resolved structural inconsistencies in the raw survey export not accounted for in the original course template (e.g. The IBM course uses a survey that is updated yearly. This year, the surveyer made it an option for you to choose multiple optins in several questions. The result is that certain columns had fields with lists. In order to analyze and make insights from this data I used python to explode and split the data and make it it's own column)
2. **Exploratory analysis** — used Python to identify relationships between experience, technology stack, and compensation
3. **Visualization** — built an interactive dashboard so results can be filtered and explored rather than read as static charts
4. **Insights** — translated findings into practical takeaways around hiring, skills development, and workforce planning

## Key Findings

1. JavaScript currently leads developer language usage, but Python is the #1 most-desired language going forward, signaling a clear shift in demand
2. PostgreSQL dominates both current and desired database preferences, reflecting its strength as a consolidated, AI-compatible data stack
3. Compensation scales with both age and experience, but job satisfaction shows only a weak correlation with pay, experience matters more to satisfaction than salary does
4. AWS holds a clear lead as the preferred cloud platform, both currently and for future adoption, ahead of Azure and Google Cloud

## Repository Contents

- `notebooks/` — Python analysis and data cleaning
- `sql/` — queries used for aggregation
- `dashboard/` — Looker Studio export or screenshots
- `data/` — [note if raw data is included, or link to the public source if it's too large for the repo]

## Dashboard Preview

[Insert a screenshot of the dashboard here, this matters more than people expect. A visual preview is often what actually gets someone to click through to the live version.]

---

**Author:** Garrett Hanson · [LinkedIn](your-link) · IBM Data Analyst Professional Certificate, 2026

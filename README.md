# Hospital Readmission Analysis Dashboard

![Power BI Dashboard Screenshot](https://via.placeholder.com/800x450.png?text=Power+BI+Dashboard+-+Hospital+Readmission)  
*(Replace with actual screenshot of your full dashboard – upload it to the repo and link here)*

An end-to-end healthcare analytics project to explore and visualize **30-day hospital readmission patterns**, focusing on age, gender, admission type (Elective vs Emergency), length of stay, and other clinical factors. Built to uncover high-risk patient groups and support better discharge planning.

Overall readmission rate in the dataset: **~28.8%**

## Project Overview

Hospital readmissions within 30 days are a major issue in healthcare — they increase costs, indicate potential care gaps, and affect patient outcomes. This project analyzes patient-level data to identify key drivers of readmission, particularly in elderly populations (>60 years old).

**Goal**: Provide clear, interactive visuals in Power BI to highlight patterns by:
- Age group (<40, 40-60, >60)
- Admission type (Elective vs Emergency)
- Gender
- And derived features like stay length groups

## Tech Stack & Workflow

- **Data Processing** → Snowflake (cleaning, feature engineering: age groups, stay groups, rates calculation)
- **Visualization & Dashboard** → Power BI (interactive filters, bar charts, donut charts, KPIs)
- **Presentation** → Canva (executive slides – PDF linked below)
- **Repository** → GitHub (this portfolio showcase)

Full workflow: Raw data → Snowflake ETL → Power BI Dashboard → Canva Presentation → GitHub

## Key Insights from the Dashboard

- **Age is a strong factor** — Patients >60 have consistently higher readmission rates (~29–30%)
- **Emergency admissions** show higher readmission proportion compared to Elective (~47.9% Elective vs 52.1% Emergency in some views)
- **Gender distribution** appears fairly balanced, with slight variations in rates
- High-risk profile emerging: Older patients + Emergency admission + longer stays / multiple previous admissions

![Readmission by Age Group & Admission Type](https://via.placeholder.com/600x400.png?text=Readmission+Rate+by+Age+Group+&+Admission)  
*(Upload & link your key visuals here – e.g., the bar chart and donut chart)*

## Dashboard Features

- Interactive slicers/filters for Age Group, Gender, Admission Type
- KPI card: Overall Readmission Rate (0.288)
- Bar charts: Readmission counts & rates by category
- Donut chart: Admission type breakdown
- Drill-through capability for deeper exploration

## Files in this Repository

- `PowerBI_HospitalReadmission.pbix` → The main Power BI file (you can share via OneDrive link if too large)
- `screenshots/` → Folder with dashboard images (add them!)
- `presentation/` → Canva exported PDF or link
- `data/` → Sample anonymized data or schema (if you can share)
- `Snowflake_SQL_scripts/` → Key SQL queries used for cleaning/feature creation (highly recommended to include!)

## How to View / Use

1. Clone the repo:  
   ```bash
   git clone https://github.com/YOUR_USERNAME/hospital-readmission-analysis.git

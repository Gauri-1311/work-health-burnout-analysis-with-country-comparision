# Work, Health & Burnout Analysis — How Modern Work Culture Impacts Human Health

An end-to-end data analytics capstone project uncovering what actually drives employee burnout, stress, and health deterioration — backed by data, not assumptions — with a global comparison across 41 OECD countries.

## Goal

To identify the real drivers of employee burnout and health decline, and translate those findings into practical, data-backed recommendations for organizations.

## Tools Used

`Python` · `SQL` · `Excel` · `Power BI` · `Machine Learning`

## Project Structure

```
├── data/
│   ├── raw data/          # Original datasets (survey, sleep, country comparison)
│   └── cleaned data/      # Processed/merged datasets used for analysis
├── notebook/
│   ├── data_exploration_01.ipynb
│   ├── SQL_Analysis.ipynb
│   └── Ml_Analysis.ipynb
├── dashboards/
│   ├── Capstone Project.pbix     # Power BI dashboard
│   └── Work_Health_Analysis.xlsx # Excel dashboard
└── report/
    └── Work_Health_Burnout_Report_Gauri_Panwar.docx
```

## Key Findings

- Work hours alone do **not** predict burnout
- Remote work does not reduce stress or boost productivity — a commonly held myth doesn't hold up
- Physical activity only marginally reduces stress — not sufficient on its own
- Overweight individuals report the least sleep
- A clear link exists between workplace stress and cardiovascular health
- Higher salary does not reduce burnout — employees earning 80K–100K show **more** burnout than those earning 100K+

**The real insight:** no single factor drives burnout. It's a combination of stress, sleep quality, physical activity, management support, career growth, and work-life balance acting simultaneously.

## Global Comparison (OECD Data — 41 Countries)

- Mexico leads in overworked employees (25.8%)
- Finland, Iceland & Netherlands top global life satisfaction
- Japan shows a paradox — high life expectancy but the lowest self-reported health, reflecting its "Karoshi" (overwork) culture
- Denmark & Norway stand out as role models — balanced across health, satisfaction, and longevity
- Countries that prioritize personal time report significantly higher wellbeing

**Note on India:** India isn't part of the OECD dataset, but ranks among the highest globally in weekly working hours — a reminder that the Indian workforce deserves similar data-driven wellbeing initiatives.

## What Actually Drives Burnout (ML Feature Importance)

| Rank | Factor | Importance |
|------|--------|-----------|
| 1 | Manager Support Score | 9.1% |
| 2 | Career Growth Score | 8.4% |
| 3 | Job Satisfaction | 8.4% |
| 4 | Productivity Score | 8.3% |
| 5 | Stress Level | 8.2% |

## Recommendations

- **Invest in manager development** — a good leader supports people rather than pressures them; build trust, fairness, and respect
- **Choose growth over salary** — work without hope or interest accelerates burnout; the Netherlands & Sweden's strong learning cultures offer a model
- **Prioritize IT & Engineering wellbeing** — no-meeting blocks, dedicated mental health days, and on-call rotation limits
- **Move beyond salary as the primary lever** — autonomy, flexibility, and meaningful work matter more
- **Give special attention to the 45–54 age group** — responsibility, retirement planning, and savings pressures often converge in this range

## Context

Built as a capstone data analytics project targeting HR Analytics and Healthcare Analytics domains, with real-world applications relevant to consulting and enterprise HR functions.

## Author

**Gauri Panwar**

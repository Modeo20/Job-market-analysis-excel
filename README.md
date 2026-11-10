# Job Market Analysis: Data & Analytics Roles in the U.S.

A self-directed data analysis project examining **12,874 data and analytics job postings across 51 U.S. states** to find out which roles, tools, work arrangements and locations are driving hiring demand. Data was cleaned and analysed in **Microsoft Excel**, and the results are presented in an interactive dashboard and a formal written report.

## Project Overview

The data job market is broad, with titles ranging from "Data Analyst" to "HR Analyst" and "Financial Analyst", and tool requirements that vary widely. This project answers four practical questions:

- Which job categories have the highest demand?
- Which tools (SQL, Python, Tableau, Power BI, Excel) are requested most, overall and by seniority?
- Where are the jobs located?
- How common are onsite, hybrid and remote roles?

## Key Findings

| Metric | Result |
|---|---|
| Total job postings | 12,874 across 51 states |
| Top job category | Data & Business Analytics (5,081 postings), more than 4x the next named category, Technology Analytics (1,164) |
| Most common job level | Junior (7,898 postings, 61.4%) |
| Work arrangement | Onsite 51.8%, Hybrid 33.6%, Remote 14.6% |
| Top hiring states | California (1,003), Florida (620), Texas (613), Virginia (465), Illinois (455) |
| Most requested tools | SQL (37.6%), Excel (29.5%), Python (17.2%), Tableau (17.0%), Power BI (15.0%) |

**Main takeaways**

- **SQL and Excel are the foundation.** They are the two most requested tools at every seniority level, so they are baseline expectations rather than early-career skills.
- **Generalist roles dominate.** Business-focused analytics roles make up the bulk of hiring, ahead of specialised technical, financial, operational or HR roles.
- **Onsite and hybrid still lead.** Together they account for over 85% of postings; fully remote roles are a small minority.
- **Hiring is concentrated.** A handful of large states account for much of the located demand.

## Data Cleaning & Methodology

Each posting recorded a job title, category, seniority level, state, search location, work type and five tool indicators. Cleaning and preparation in Excel included:

- Mapping raw job titles into **six consistent categories**: Data & Business Analytics, Technology Analytics, Financial Analytics, Operational Analytics, HR Analytics and Other.
- Standardising seniority into **five levels**: Junior, Mid, Senior, Lead and Principal.
- Normalising location fields into state codes and full state names, and flagging postings with no state as "Not Specified".
- Creating **binary (0/1) flag columns** for SQL, Python, Tableau, Power BI and Excel based on whether each was mentioned in the posting.

Analysis used PivotTables, summary formulas and chart objects, consolidated into a single interactive dashboard.

## Tools Used

- Microsoft Excel: data cleaning, formulas, PivotTables, charts and dashboard

## Repository Structure

> Adjust the file names below to match what you upload.

```
├── README.md
├── report/
│   └── Job_Market_Analysis_Report.pdf
├── dashboard/
│   └── Job_Market_Dashboard.xlsx
├── data/
│   └── cleaned_job_postings.xlsx
└── images/
    └── dashboard_preview.png
```

## Dashboard Preview

![Dashboard preview](images/dashboard_preview.png)

## Recommendations from the Analysis

- **Job seekers:** Build strong SQL and Excel fundamentals first, then add Python, Tableau or Power BI.
- **Senior and lead candidates:** Core tool expectations do not change much with seniority; domain expertise and business judgement set candidates apart.
- **Location-flexible candidates:** Focus on high-volume states such as California, Florida and Texas.
- **Training programmes:** Treat SQL, Excel and one visualisation tool as the minimum analytics toolkit for new hires.

## Limitations

- 3,605 postings had no specified state, which limits the completeness of the geographic analysis.
- The "Other" category (5,577 postings) mixes many roles that did not map cleanly to a named category; a more granular classification could reveal more patterns.
- Tool requirements were captured as simple binary flags, which may understate demand for tools mentioned indirectly (for example "BI tools" instead of "Power BI").
- The data is a snapshot in time and may not reflect seasonal hiring trends.

## Author

**[Your Name]**, Data Analyst
[LinkedIn URL] | [your.email@example.com]

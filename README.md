# Data Professional Survey Breakdown Dashboard

## Problem
Job seekers and professionals in the data field often lack a clear, data-backed picture of salary expectations, market entry difficulty, and career satisfaction across job titles, countries, and tools. This project turns a public survey of 630 data professionals into an interactive Power BI dashboard that answers these questions with real numbers instead of guesswork.

## Approach & Thinking
- Imported and cleaned the raw survey dataset in Power Query (column standardization, handling blanks/outliers)
- Built DAX measures for average salary, average age, and satisfaction scores
- Designed a fully interactive, cross-filtered dashboard: clicking any visual (country, job title, language) filters the entire report
- Selected visual types by purpose: treemap for country distribution, ranked bar chart for salary by job title, gauge charts for satisfaction scores, donut chart for market entry difficulty, column chart for programming language usage

## Result
- Interactive one-page dashboard covering 630 survey responses
- Average respondent age: 29.87
- Salary by job title ranked from Data Scientist (highest) down to Student/Looking for a job (lowest)
- Full cross-filtering across all visuals for exploratory analysis

## What We Found & Impact
- 42.7% of respondents rated breaking into the data field as "neither easy nor difficult," 24.76% said "difficult," 21.27% said "easy," and 6.98% said "very difficult"
- Average happiness with work/life balance: 5.74 / 10
- Average happiness with salary: 4.27 / 10 — notably lower than work/life balance, showing salary is the bigger satisfaction gap for data professionals
- Python is the dominant language among respondents, far ahead of R and all other languages
- United States and India are the top two respondent countries, followed by the UK and Canada

## Tools & Methods
Power BI, Power Query, DAX, Data Modeling, Data Visualization, Excel

# Compensation-Benchmarking-Analysis
# Compensation Benchmarking & Pay Equity Analysis

An analysis of 6,599 data science salary records in Python to understand how pay varies by role, experience, company size, and work model, and how many roles fall below the market median.

## Questions Explored
- Which job titles pay the most?
- How does salary change with experience level?
- Do company size and work model (remote, hybrid, on-site) affect pay?
- What share of roles at each experience level fall below the overall market median?

## Approach
1. Loaded the dataset with Pandas
2. Cleaned it by dropping rows with missing values and standardizing column names
3. Used `groupby` to compare average salary by job title, experience level, company size, and work model
4. Calculated the overall median salary and flagged roles below it to measure pay equity by experience level
5. Visualized the salary distribution with Matplotlib and exported a clean dataset

## Key Findings
- About 88% of entry-level roles fall below the overall market median, compared with about 38% of senior-level roles
- Average salary rises with experience: about $84K (entry), $119K (mid), $162K (senior), and $190K (executive)
- Medium-sized companies had the highest average salaries (about $150K)

## Next Steps
- Compare roles to the median within the same job title for a fairer benchmark
- Add duplicate checks and before/after row counts to the cleaning step

## Tech
Python · Pandas · Matplotlib · Jupyter (Google Colab)

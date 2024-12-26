# Salary Trends and Factors in the Job Market

## Project Overview
This project analyzes salary trends from 2020 to 2024 across various job categories, experience levels, company sizes, and work settings. The dataset combines Kaggle data, web-scraped job listings, and student survey responses. Insights are visualized using R to uncover key patterns in the evolving job market.

## Data Sources
- **Kaggle (2020–2023):** Comprehensive salary data.
- **Web Scraping (2024):** Job listings from websites like Monster and Indeed.
- **Survey Responses:** Contributions from INFO 526 students on job preferences.

## Dataset Details
The dataset consists of 50,000 records with variables such as:
- **work_year:** Year the salary data was recorded.
- **experience_level:** Entry, Mid, Senior, or Executive.
- **employment_type:** Full-time, Part-time, Contract.
- **salary_in_usd:** Salaries converted to USD.
- **work_setting:** Remote, In-person, or Hybrid.

## Key Questions
1. How do salaries vary by job category across experience levels?
2. Which job titles are common for executive-level roles?
3. What are the salary trends over the years?
4. How do company size and job category affect salaries?
5. How does work setting correlate with employee residence and salary?
6. How have remote and in-person work settings evolved over time?

## Analysis Plan
- Data preprocessing (cleaning, handling missing values).
- Visualizations: Boxplots, bar charts, line graphs, scatter plots.
- Tools used: R (ggplot2, dplyr, gganimate).

## Findings
- Salary variations depend heavily on experience level and job category.
- Remote work has seen significant growth, with salaries trending higher for some roles.
- Large companies offer higher salaries on average, but trends vary by job category.

## Repository Structure
```
├── data
│   └── updated_data.csv
├── scripts
│   └── analysis.R
├── visuals
│   └── plots (generated visualizations)
├── README.md
└── report
    └── final_report.html
```

## How to Run the Project
1. Clone this repository.
   ```bash
   git clone <repository_url>
   ```
2. Open the R project file.
3. Run `analysis.R` to generate insights and visualizations.

## Conclusion
This analysis highlights significant salary trends and patterns in the job market, offering valuable insights into factors influencing compensation.

## Contact
For questions or collaboration opportunities, please reach out to [Your Email Address].

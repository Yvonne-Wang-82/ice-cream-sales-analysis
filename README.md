# Frost Bite Sales Analysis

This repository contains my final project for a Data Programming course at the University of Washington. As the Frost Bite Student Coordinator (a student-run ice cream shop on campus), I wanted to explore our sales data to better understand customer behavior, flavor popularity, and how external factors like weather affect visits.

## Repository Contents
- `project.ipynb` – Jupyter Notebook with full analysis and visualizations
- `data/` – Folder containing raw CSV data (flavor usage, customers, weather)
- `Frost_Bite_Sales_Analysis.pdf` – Slides used for presenting results with classmates
- `project.html` – Exported HTML version of the notebook

## Research Questions
1. How does the weather or temperature affect ice cream usage and the number of customers?
2. What ice cream flavors are the most popular?
3. Is there a day of the week that we have the most customers?
4. Does the existence of very popular flavors affect sales of other flavors?

## Key Findings
1. Warmer temperatures lead to more customers, but rain does not affect customer visits or ice cream usage.
2. Top flavors: Cookie Dough, Salted Caramel Brownie, Dawg Tracks, Cookies & Cream.
3. We are busiest on Thursdays. Weekdays tend to have more customers than weekends.
4. The existence of popular flavors do not reduce sales of other flavors.

Full Project: [`project.ipynb`](project.ipynb) – includes all code, visualizations, and detailed analysis.

## Methods
- Cleaned and merged sales and weather datasets using Python (Pandas, NumPy).
- Explored relationships with visualizations (scatter, bar, and box plots) and correlation analyses.
- Conducted statistical tests (Pearson, Spearman, ANOVA) to answer research questions about customer behavior, flavor popularity, and day-of-week trends.

## Tools & Libraries
- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib, Seaborn, SciPy

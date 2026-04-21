# Data Professionals Survey Breakdown

![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## Project Overview
This project focuses on the exploration and analysis of real-world survey data collected from hundreds of data professionals across the globe. By analyzing career-related metrics such as job titles, salaries, programming language preferences, and workplace happiness, this initiative aims to provide a comprehensive look into the current state of the data industry. This dashboard serves as a tool for aspiring and current data professionals to understand trends in compensation, demographics, and job satisfaction.



## Problem Description
In the rapidly evolving data landscape, understanding the distribution of roles and the factors that influence career satisfaction is vital for both professionals and employers. This project addresses the challenge of interpreting raw survey data to uncover what data professionals truly experience—ranging from the difficulty of breaking into the field to the average salary across different countries and job titles.

## Dataset Information
The project utilizes a [dataset](https://github.com/gauravkamble-insights/Data-Professionals-Survey-Breakdown/tree/main/src/data) sourced from a real-world survey posted on social media platforms like LinkedIn and Twitter. The dataset includes several key metrics:
- **Job Titles:** Specific roles such as Data Analyst, Scientist, Engineer, and Architect.
- **Salary:** Yearly compensation ranges, transformed into a numeric average for analysis.
- **Programming Languages:** Preferred tools including Python, R, SQL, and others.
- **Happiness Scores:** Ratings (0–10) for work-life balance and salary satisfaction.
- **Demographics:** Information on age, gender, and country of residence.

## Background Information
This project is driven by the need for transparent, data-backed insights into the data professional community. By cleaning and visualizing raw survey responses, the project identifies high-performing roles (like Data Scientists) and highlights how geography significantly impacts compensation. It provides a clear picture of the diversity and satisfaction levels within the field.

## Project Workflow
**1. Data Connection & Cleaning:** Importing raw CSV/Excel data into Power BI and using Power Query to remove unnecessary columns.  
**2. Data Transformation:** Standardizing job titles and programming languages by handling "Other" text entries through column splitting and delimiters.  
**3. Salary Normalization:** Cleaning salary strings (removing 'k', '+', and dashes) and using DAX to create a custom "Average Salary" column for numeric analysis.  
**4. Data Visualization:** Designing an interactive dashboard in Power BI featuring:
- Cards for high-level totals like survey taker count and average age.
- Bar/Column Charts for favorite languages and salary by job title.
- Tree Map for geographical breakdown.
- Gauges for happiness metrics.
- Donut Charts for gender and entry difficulty analysis.

**5. Theming & Formatting:** Customizing the dashboard background, font sizes, and color schemes to enhance readability and professional appeal.  

## Conclusion
The project offers a deep dive into the demographics and professional realities of the data world. By transforming messy, raw survey responses into a structured dashboard, we can see that while Data Scientists often command the highest salaries, Data Analysts make up the largest portion of the workforce. These insights allow users to navigate their career paths with a better understanding of the global data landscape.

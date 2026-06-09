# Job Market Data Analysis

## Project Overview

This project explores trends in the AI job market using Python, Jupyter Notebook, and Power BI. The analysis focuses on salary patterns, experience levels, skill demand, job openings, and hiring trends across different industries and countries.

The goal is to uncover insights that can help job seekers, recruiters, and organizations better understand the current AI employment landscape.

## Dataset Description

The dataset contains 10,345 job records and includes the following features:

* Job Title
* Company Size
* Company Industry
* Country
* Remote Work Type
* Experience Level
* Years of Experience
* Education Level
* Technical Skills (Python, SQL, Machine Learning, Deep Learning, Cloud Computing)
* Salary
* Hiring Urgency
* Job Openings
* Job Posting Month and Year

## Tools and Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI
* HTML

## Data Preparation

The following data cleaning steps were performed:

* Checked for missing values
* Removed duplicate records
* Converted salary values to numeric format
* Saved the cleaned dataset for further analysis

## Analysis Performed

### 1. Salary Analysis by Job Title

Average salaries were compared across AI-related job roles.

| Job Title                 | Average Salary |
| ------------------------- | -------------- |
| AI Engineer               | 139,945        |
| Machine Learning Engineer | 139,705        |
| Business Analyst          | 101,642        |
| Data Engineer             | 99,711         |
| Data Scientist            | 99,646         |
| Data Analyst              | 99,136         |

### 2. Salary vs Experience Level

The analysis examined how salary changes with experience.

| Experience Level | Average Salary |
| ---------------- | -------------- |
| Entry            | 89,096         |
| Mid              | 113,592        |
| Senior           | 138,289        |

### 3. Remote Work Analysis

Salary comparison based on work arrangement:

| Work Type | Average Salary |
| --------- | -------------- |
| Hybrid    | 113,364        |
| Onsite    | 113,650        |
| Remote    | 113,305        |

### 4. Skills Demand Analysis

Most demanded technical skills:

| Skill            | Demand Count |
| ---------------- | ------------ |
| Cloud Computing  | 5,291        |
| Machine Learning | 5,254        |
| SQL              | 5,204        |
| Deep Learning    | 5,152        |
| Python           | 5,101        |

### 5. Job Openings Analysis

Roles with the highest number of openings:

| Job Title                 | Openings |
| ------------------------- | -------- |
| Business Analyst          | 8,940    |
| Machine Learning Engineer | 8,767    |
| Data Scientist            | 8,659    |
| Data Analyst              | 8,632    |
| AI Engineer               | 8,483    |
| Data Engineer             | 8,286    |

### 6. Monthly Hiring Trends

Hiring activity was analyzed across different months to identify recruitment patterns and seasonal demand.

## Visualizations

The project includes:

* Salary by Experience Level chart
* Skill Demand chart
* Most In-Demand Job Roles chart
* Interactive Power BI Dashboard
* Dashboard screenshots available in the `screenshots` folder

## Key Findings

* Salaries increase significantly with experience level.
* AI Engineers and Machine Learning Engineers receive the highest average salaries.
* Cloud Computing and Machine Learning are the most demanded technical skills.
* Business Analyst roles have the highest number of job openings.
* Hiring demand remains relatively stable throughout the year.
* Remote, hybrid, and onsite jobs show similar salary ranges.

## Conclusion

The analysis demonstrates that experience level and technical skills strongly influence salary in AI-related careers. Organizations continue to demand expertise in Cloud Computing, Machine Learning, SQL, and related technologies. These insights can support career planning, recruitment strategies, and workforce development initiatives.

## Repository Contents

* `Job_Market_Analysis.ipynb` – Jupyter Notebook analysis
* `Job_Market_Analysis.html` – HTML version of the notebook
* `Job_Market_Dashboard.pbix` – Power BI dashboard
* `screenshots/` – Dashboard screenshots

## Author

**Furahini Siyanga**

Aspiring Data Analyst | Power BI Expert | Python Enthusiast

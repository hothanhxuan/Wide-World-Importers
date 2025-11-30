# 📊 Project 1: Employee Turnover & Workforce Performance Analysis | HR Domain | Excel + Power BI

Business Question:
How can HR leaders understand turnover drivers, workforce composition, and performance trends to improve employee retention and optimize operational decisions?

Domain:
Human Resources Analytics (HR Operations)



Author: [Susan Ho]
Date: 2025-12-01
Tools Used: Excel / Power BI

📑 Table of Contents

📌 Background & Overview

📂 Dataset Description & Data Structure

🧠 Design Thinking Process

⚒️ Main Process

📊 Key Insights & Visualizations

🔎 Final Conclusion & Recommendations

📌 Background & Overview
Objective
📖 What is this project about?

This project develops an operational HR analytics dashboard using Excel and Power BI to uncover workforce patterns, turnover behavior, and employee performance insights that drive business decisions.

✔️ Analyze employee turnover rates across departments
✔️ Understand workforce demographics (gender, age, tenure)
✔️ Evaluate satisfaction & engagement levels
✔️ Identify top recruitment sources and departure reasons
✔️ Support HR leaders with actionable insights for retention

This dashboard provides a 360° view of the employee lifecycle, making it easier for business and HR stakeholders to make evidence-based decisions.

👤 Who is this project for?

✔️ HR Analysts & HR Managers
✔️ People Operations & Talent Acquisition Teams
✔️ Business Leaders & Department Heads
✔️ Workforce Planning & Organizational Development Teams

📂 Dataset Description & Data Structure

📌 Data Source
HRDataset.xlsx
  Format: Excel (.xlsx)
  Rows: 300 (employees)
  Columns: 20+ HR attributes (demographics, performance, termination, satisfaction)
DAC PBI – Project 1.pdf (Power BI Dashboard)

Visualized metrics: turnover, demographics, satisfaction, recruitment sources, department performance

📊 Data Structure & Relationships

1️⃣ Tables Used
Only one main HR dataset was used from the Excel file, containing all employee-level information:
Employee Master Table — includes demographics, job info, performance, satisfaction, termination, recruitment source, etc.

2️⃣ Table Schema & Data Snapshot
| Column Name       | Description                       |
| ----------------- | --------------------------------- |
| EmployeeID        | Unique employee identifier        |
| ManagerID         | Manager supervising the employee  |
| PositionID        | Role/position code                |
| MaritalStatusID   | Marital status classification     |
| PerformanceScore  | Performance rating                |
| Location          | Work location                     |
| Birthday          | Employee date of birth            |
| Gender            | Gender identity                   |
| CitizenDesc       | Citizenship                       |
| RaceDesc          | Racial group                      |
| Date of Hire      | Hire date                         |
| RecruitmentSource | Where the employee was hired from |
| EmploymentStatus  | Active / Terminated               |
| Salary            | Current salary                    |
| SatisfactionScore | Level of satisfaction             |
| EngagementScore   | Engagement rating                 |
| AbsenceDays       | Total days absent                 |

<details> <summary>Click to toggle: Raw data snapshot</summary>
A small preview extracted from Excel:
Employee | ManagerID | PositionID | Gender | RaceDesc | Date of Hire | RecruitmentSource | EmploymentStatus | Salary | SatisfactionScore | EngagementScore | AbsenceDays
10026-Adinolfi | 22 | 19 | M | White | 1983-10-07 | Indeed | Active | 62506 | 5 | 4.6 | 1
10084-Ait Sidi | 4 | 27 | M | White | 1975-05-05 | Indeed | Voluntarily Terminated | 104437 | 3 | 4.96 | 17
...
</details>

3️⃣ Data Relationships

Since the dataset is a single fact table, Power BI uses:

Calculated columns (Tenure, Age)

DAX measures (Turnover Rate, Avg Salary, Absence Rate)

Segmentation by dimensions such as:

Department

Gender

Marital Status

Employment Status

Performance Score

🧠 Design Thinking Process

1️⃣ Empathize
HR leaders need quick, accurate insights about workforce composition, turnover, and performance to make operational decisions.

2️⃣ Define Point of View
“How might we help HR understand the root causes of turnover and maintain an optimized workforce?”

3️⃣ Ideate
Brainstormed dashboard requirements:

Turnover analysis

Department-level benchmarking

Demographic breakdown

Satisfaction & engagement scoring

Recruitment source efficiency

4️⃣ Prototype and Review
Developed a Power BI dashboard visualizing all key metrics; refined with stakeholder feedback to improve usability.

⚒️ Main Process
1️⃣ Data Cleaning & Preprocessing

✔ Removed empty header rows
✔ Standardized date formats
✔ Derived fields: Age, Tenure
✔ Cleaned inconsistent employment status labels
✔ Removed duplicate employee entries

2️⃣ Exploratory Data Analysis (EDA)

Analyzed:

Distribution of tenure

Salary differences by department

Termination reasons

Recruitment source patterns

Demographic structures

3️⃣ Power BI Measures (DAX)

Created measures:

Turnover Rate = Terminated Employees / Total Employees

Absence Rate = SUM(AbsenceDays) / Employee Count

Average Tenure, Average Engagement, Average Salary

4️⃣ Power BI Visualization

Built a multi-page dashboard:

Workforce Overview

Department Analysis

Recruitment & Termination Insights

Employee Detail View

📊 Key Insights & Visualizations
📌 Dashboard Preview & Main Insights

(Screenshots would be inserted here on GitHub)

1️⃣ Dashboard: Workforce Overview

Observation:
From the PDF metrics:

Total employees: 299

Turnover rate: 34.78%

Avg tenure: 12.31 years

Absence rate: 0.23%

Avg satisfaction score: 3.89

Avg engagement score: 4.11


DAC PBI - Project 1

Recommendation:
✔ Strengthen engagement efforts among long-tenure employees
✔ Monitor departments with persistently low satisfaction scores

2️⃣ Dashboard: Department Analysis

Observation (from PDF):

Production has the highest turnover (40.69%)

Sales has the lowest turnover (16.13%)

IT/IS and Software Engineering have strong engagement (>4.0)


DAC PBI - Project 1

Recommendation:
✔ Investigate why Production turnover is elevated
✔ Replicate Sales retention strategies across other departments

3️⃣ Dashboard: Recruitment & Termination Insights

Observation:

Top recruitment sources: Indeed (82) and LinkedIn (74)

Top exit reasons:

Another position (20)

Unhappy (14)

More money (11)


DAC PBI - Project 1

Recommendation:
✔ Strengthen employee value proposition to reduce “more money” exits
✔ Conduct stay interviews to address “unhappy” reasons proactively

🔎 Final Conclusion & Recommendations
📌 Key Takeaways

✔ The organization has high turnover (34.78%), especially in the Production department.
✔ Majority of workforce falls between 35–54 age range, a mature and experienced demographic.
✔ Satisfaction and engagement scores are relatively strong but vary significantly by department.
✔ Recruitment heavily depends on Indeed and LinkedIn, presenting an opportunity to diversify sourcing.
✔ Many departures are preventable (salary dissatisfaction, unhappy, career change).

📌 Final Recommendations

✔ Implement targeted retention programs for Production employees.
✔ Build competitive compensation benchmarking to address “more money” attrition.
✔ Improve internal mobility pathways to reduce career-change exits.
✔ Enhance onboarding and engagement programs, especially for early-tenure employees.
✔ Use data-driven hiring strategy to optimize recruitment channels and cost-per-hire.





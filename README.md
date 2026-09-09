# HR Attrition Analysis

## Overview
An independently designed Excel project analyzing employee attrition patterns across departments, age groups, and tenure. Built using Excel's Power Pivot / Data Model as a self-directed project (not tutorial-based) to demonstrate data modeling and DAX measure development outside of a traditional Power BI environment.

## Tools Used
- Excel (Power Pivot / Data Model)
- DAX (Data Analysis Expressions)
- Star Schema Data Modeling
- Pivot Tables & Pivot Charts

## Data Model
Designed a star schema in Power Pivot with a central fact table and 5 supporting dimension tables:
- **FactEmployee** — core employee attributes and attrition status
- **DimDepartment** — department and manager details
- **DimLocation** — city/state information
- **DimDate** — calendar table for time-based analysis
- **DimEmployee** — employee demographic details
- **DimJob** — job role and job level

## Key Measures (DAX)
- Total Employees
- Active Employees
- Employees Left
- Attrition Rate %
- Average Salary
- Average Rating
- Last Year Headcount
- Headcount Growth %

## Key Findings
- **Overall attrition rate: 16.12%** across 1,470 employees
- **Age is the strongest attrition driver**: employees under 25 had a **39.18% attrition rate** — dramatically higher than every other age group (25-34: 20.22%, 35-44: 10.10%, 45-54: 10.20%, 55+: 15.94%)
- **Department-level differences**: Sales (20.68%) and Human Resources (19.05%) saw notably higher attrition than Research & Development (13.84%)
- Additional analysis included salary band distribution and headcount trends by hire year (1986-2024)

## Screenshots
<img width="928" height="535" alt="image" src="https://github.com/user-attachments/assets/7fbc55bb-d1f7-4858-a6c2-2386cab8352c" />

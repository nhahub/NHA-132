# Depi HR Data Analysis Final Project 

## Project Overview

This project focuses on analyzing Human Resources (HR) data to identify the key factors that influence employee attrition and performance. By studying employee demographics, job roles, salary, satisfaction, training, and performance ratings, the project aims to provide data-driven insights that support better HR decision-making.

---

## Project Objectives
- Analyze employee performance across different departments and job roles  
- Identify the factors that affect employee attrition  
- Study salary distribution and its impact on performance and job satisfaction  
- Evaluate employee satisfaction and work-life balance  
- Support HR decision making using data driven insights  

---

## Team Members & Roles
- **Mostafa Bakry** – Data Cleaning & Project Documentation  
- **Esraa Ayman** – Data Processing & Data Analysis  
- **Menna Allah Taha** – Data Visualization & Dashboard  
- **Rahma Hassan** – Reporting & Presentation

---

## Tools Used
- ***Python, Jupyter Notebook***  - For data cleaning and analysis   
- ***Tableau*** – For dashboards and visualizations
- ***Microsoft Word***  - For Documentation
- **prezi.com, Power Point** - For Presentation
- **Google Drive** - For uploading Files
- ***GitHub*** – for version control and project hosting
---

## Dataset Description

This project uses two datasets that are linked using the **EmployeeID** column.

### Employee.csv

| Item | Details |
|----------|--------|
| Number of Rows | 1,470 |
| Number of Columns | 23 |


| Column  | Description |
|--------|-------------|
| EmployeeID | Unique identifier for each employee |
| Gender | Gender of the employee |
| Age | Age in years |
| Department | Department of work |
| JobRole | Employee job position |
| Salary | Monthly salary |
| OverTime | Employee works overtime (Yes/No) |
| HireDate | Date of joining the company |
| Attrition | Whether the employee left the company |
| YearsAtCompany | Total years at the company |
| YearsSinceLastPromotion | Years since last promotion |
| YearsWithCurrManager | Years with current manager |

----

### PerformanceRating.csv

| Item | Details |
|----------|--------|
| Number of Rows | 6,709 |
| Number of Columns | 11 |


| Column  | Description |
|--------|-------------|
| PerformanceID | Unique ID for each evaluation |
| EmployeeID | Links to Employee.csv |
| ReviewDate | Date of performance review |
| EnvironmentSatisfaction | Satisfaction with work environment |
| JobSatisfaction | Job satisfaction level |
| RelationshipSatisfaction | Satisfaction with colleagues |
| TrainingOpportunitiesWithinYear | Training opportunities provided |
| TrainingOpportunitiesTaken | Training programs attended |
| WorkLifeBalance | Work-life balance rating |
| SelfRating | Rating given by employee |
| ManagerRating | Rating given by manager |

---

## Project Workflow
1. Data Collection  
2. Data Cleaning & Preprocessing  
3. Data Analysis  
4. Data Visualization & Dashboard  
5. Documentation & Reporting  
6. Presentation Preparation  
---
## How to Navigate Through the Project

- **[01_Raw_Data](01_Raw_Data/)**  
  Contains the original raw datasets in **CSV** format before any processing.

- **[02_Data_Cleaning](02_Data_Cleaning/)**  
  Contains the **cleaned and prepared datasets** used for analysis and visualization.

- **[03_Cleaning_Script](03_Cleaning_Script/)**  
  Contains the **data cleaning steps**
  
  **(`.ipynb`)** → can be viewed directly on **GitHub** or you can run it by downloading **Jupyter Notebook**
  
  **(`.html`)** → download to view in your **browser**

- **[04_Analysis](04_Analysis/)**  
  Contains the **analysis steps, results**:
  - `.ipynb` → can be viewed directly on **GitHub** or by downloading **Jupyter Notebook**
  - `.html`  → download to view in your **browser**  
  - `.pdf/`  → has the questions that have been answered in the analysis  can be viewed directly on **GitHub**


- **[05_visualization](05_.visualization/)**  
  Contains the Final Dashboard
  
 
  **(`.twbx`)** → can be viewed by using tableau
  
---

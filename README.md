**ITSM Incident Management Dashboard (Power BI)**

This project presents a comprehensive Power BI dashboard developed to analyze key IT Service Management (ITSM) metrics, focusing on incident volumes, SLA breaches, resolution efficiency, and team performance. The dataset used is a simulated ITSM incident log, modeled on real-world enterprise-level service desk data.

**1. Project Overview**

The dashboard enables IT managers and stakeholders to:

Monitor incident trends and SLA compliance
Evaluate team efficiency and assignment bottlenecks
Perform drill-down analysis on priority, urgency, and category
Identify patterns in reassignment and delays
The analysis provides actionable insights to improve service operations and ensure timely resolution.

**2. Dataset**

https://www.kaggle.com/datasets/shamiulislamshifat/it-incident-log-dataset?resource=download

**3. Features**

Total incidents and average resolution time
SLA breach analysis by category and month
Ticket status and lifecycle visualization
Incident trends by month
Reassignments by configuration item (CI) and group
Interactive filtering by date, category, priority, urgency, and assignment group

**4. Tools & Technologies**

Power BI Desktop
Power Query (data cleaning and transformation)
DAX (custom measures and columns)
Microsoft Excel (source data)
Dataset sourced from Kaggle

**5. Key Performance Indicators (KPIs)**

KPI	Description
Total Incidents	Number of incidents raised
SLA Breaches	Incidents closed after SLA threshold
Average Resolution Time	Hours taken from ticket open to resolution
Reassignment Count	Number of times a ticket is reassigned before resolution
Priority and Urgency Mix	Breakdown of ticket severity across time
Monthly Trends	Number of incidents raised and resolved each month
Resolution by CI Category	Resolution count and status grouped by configuration item

**6. Data Preparation Workflow**

Imported raw dataset from Kaggle into Power BI
Cleaned column names and standardized date formats
Removed duplicate entries and null values
Added calculated columns using Power Query and DAX:
Resolution Time (hours) = DATEDIFF(opened_at, resolved_at, HOUR)
SLA Breached = IF(made_sla = FALSE, "Yes", "No")
Extracted Month/Year from opened_at
Built multiple report pages with custom visuals and slicers

**7. Deliverables**

ITSM Dashboard Power BI file (.pbix)
Dashboard visuals in PDF format (.pdf)
Cleaned dataset used for analysis
README documentation (this file)

**8. Project Structure**

├── ITSM-Dashboard.pbix

├── ITSM-Dashboard.pdf

├── ITSM-Incident-Dataset.xlsx

└── README.md

**9. Dahsboard Preview**
<img width="891" height="502" alt="Screenshot 2026-01-08 150732" src="https://github.com/user-attachments/assets/7cfe6994-0aea-4f8b-a708-a773ecaa37e5" />


s. 

## Pbix link - https://drive.google.com/file/d/1dngUuFSwvSqN7Uhi-TXMu7jvToJqiAvM/view?usp=sharing
## Data link - [https://drive.google.com/file/d/1dngUuFSwvSqN7Uhi-TXMu7jvToJqiAvM/view?usp=sharing](https://drive.google.com/file/d/1opTeG-3OybCuO8-2rC_R_VYTiXlEwFUW/view?usp=sharing)



#📊 Data Jobs Dashboard 2.0
An interactive Power BI dashboard analyzing 479,000+ real job postings from April to December 2024 — built to help job seekers, students, and hiring professionals explore the global data job market.

#👤 Student Details
FieldDetailsNameKaustubh Gaurav TiwariRoll Number23052078ProgramB.Tech Computer Science EngineeringBatch / YearCSE-4 | 2027

#📌 Problem Statement
Job market data is scattered, unstructured, and hard to interpret. Job seekers and analysts lack a centralized view of what data jobs exist, what they pay, and what skills they require. This dashboard solves that by consolidating 9 months of raw job posting data into a single, interactive analytical experience.

#✨ Features
KPI Cards — Job Count, Skills Per Job, Median Yearly Salary, Median Hourly Salary
Skill Popularity Chart — Top 10 in-demand skills (Python, SQL, AWS, Azure, Tableau, etc.)
Job Salaries Chart — Median salary comparison across 10 major data job titles
Dynamic Measure Toggles — Switch between Job Count / Job Percent and Yearly / Hourly Salary
Dual Slicers — Filter by Job Title and Country simultaneously
Clear Slicers Button — Reset all filters in one click
Dark Professional Theme — Custom Innovate theme for a polished UI


#🛠️ Tech Stack
ToolPurposePower BI DesktopDashboard design & visualisationPower Query (M)Data ingestion, transformation & appendDAXKPIs, measures & dynamic calculationsExcel (.xlsx)Source data files

#📁 Project Structure
Data_Jobs_Dashboard_Project/
├── Data_Jobs_Dashboard_2.0.pbix        ← Main Power BI file
├── README.md
├── Data_Sources/
│   ├── job_postings_04-2024 ff.xlsx
│   ├── job_postings_05-2024 ff.xlsx
│   ├── job_postings_06-2024 ff.xlsx
│   ├── job_postings_07-2024 ff.xlsx
│   ├── job_postings_08-2024 ff.xlsx
│   ├── job_postings_09-2024 ff.xlsx
│   ├── job_postings_10-2024 ff.xlsx
│   ├── job_postings_11-2024 ff.xlsx
│   ├── job_postings_12-2024 ff.xlsx
│   ├── company_dim ff.xlsx
│   ├── skills_dim ff.xlsx
│   └── skills_job_dim ff.xlsx
└── Documentation/
    └── Project_Documentation.pdf

#🗄️ Data Model
The project uses a star schema design:

job_postings_fact — Central fact table with 479K+ job postings (title, company, location, country, salary, schedule type, posted date, skills)
skills_dim — Dimension table mapping skill IDs to skill names and types (e.g., Python → programming)
company_dim — Dimension table with company metadata linked to job postings

All 9 monthly Excel files are appended automatically in Power Query using Table.Combine, making the report easy to update with future months.

#🔮 Future Improvements
Live data refresh via job board API (LinkedIn, Indeed)
Geographic heat map by country/state
Month-over-month trend analysis page
Skill gap analysis — input your skills, see what's missing
Company-level drill-through pages
Mobile-optimised layout for Power BI Mobile


#📄 License
This project was created as a Capstone submission for academic purposes.
© 2026 Kaustubh Gaurav Tiwari — B.Tech CSE, Batch 2027

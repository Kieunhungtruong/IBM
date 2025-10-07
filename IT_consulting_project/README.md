# 📊 In-Demand Programming Skills — Project Overview

**Estimated time:** ~10 minutes (initial setup & understanding)  
**Role:** Data Analyst  
**Organization:** Global IT & Business Consulting Firm (IBM Skills Network Lab Project)

---

## 🔍 Project Scenario

You have recently been hired as a **Data Analyst** at a global IT and business consulting firm known for its IT solutions and experienced consultants.  
To remain competitive in the rapidly evolving tech industry, your company conducts annual analyses to identify **emerging and future skill requirements**.

Your primary responsibility is to collect data from various sources and identify trends for this year's report on **in-demand technical skills**.

---

## 🎯 Objectives

- Identify the **most in-demand programming languages**.  
- Find out which **database technologies** are most sought after.  
- Analyze which **Integrated Development Environments (IDEs)** are most popular.  
- Collect data from:
  - Job postings  
  - Training portals  
  - Developer surveys (e.g., Stack Overflow Developer Survey)

Once the data is gathered, you will clean, analyze, and visualize it using IBM Cognos Analytics and present your insights in a final dashboard and presentation.

---

## 🧭 Suggested Workflow

1. **Data Collection**
   - Scrape or call APIs for job postings.  
   - Download and explore the Stack Overflow Developer Survey dataset (.csv).  
   - Collect data from online learning platforms or training APIs.

2. **Data Storage**
   - Save raw data in structured formats (CSV, JSON, SQL).

3. **Data Wrangling**
   - Clean, normalize, and structure data (handle duplicates, missing values, naming inconsistencies).

4. **Data Analysis**
   - Use statistical methods to find frequency counts, patterns, and correlations.  
   - Compare trends across sources (jobs vs survey).

5. **Visualization**
   - Build a dashboard using **IBM Cognos Analytics** (bar charts, heatmaps, trends).

6. **Presentation**
   - Summarize findings in a report or presentation, focusing on insights and recommendations.

---

## 🧰 Tools & Libraries

| Purpose | Tools |
|----------|-------|
| Data collection | `requests`, `BeautifulSoup`, APIs |
| Data processing | `pandas`, `numpy`, `openpyxl` |
| Visualization | IBM Cognos Analytics, `matplotlib`, `seaborn` |
| File formats | CSV, JSON, Excel |
| Version control | Git, GitHub |

---

## 📁 Recommended Folder Structure

```
ibm-practices/
├─ IT_consulting_project/
│ ├─ Collecting_job_data_using_APIs-Lab.ipynb
│ │ 
│ │ └─ job_postings_raw.json
│ └─ processed/
│ └─ skills_counts.csv
├─ notebooks/
│ ├─ 01_data_collection.ipynb
│ ├─ 02_data_cleaning.ipynb
│ └─ 03_analysis.ipynb
├─ reports/
│ └─ final_presentation.pdf
├─ images/
│ └─ ibm-skills-network-logo.png
├─ scripts/
│ └─ fetch_jobs.py
└─ README.md
```
---
```
👩‍💻 Author
Kieu Nhung Truong
IBM Data Analyst Learner
📍 Vietnam
```
⭐ Feel free to explore, fork, and learn from this project!

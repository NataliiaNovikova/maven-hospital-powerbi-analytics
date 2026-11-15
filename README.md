# Maven Hospital Healthcare Analytics | Power BI Dashboard

## 📌 Project Overview
This project delivers an end-to-end analytical BI solution for the Maven Hospital network. The primary goal is to provide hospital executives and medical staff with an interactive tool to monitor department workload, analyze treatment costs, explore patient demographics, and evaluate overall service efficiency.

---

## 🎬 Відео-демонстрація дашборду (Video Demo)

▶️ **[Watch the full dashboard video walkthrough on YouTube](https://youtu.be/1bE5GafITwc)**

*The video demonstrates dashboard interactivity, dynamic filtering, cross-slicing, and key analytical views.*

---

## 📐 Data Model

![Data Model Star Schema](screenshots/data_model.jpg)
* **Architecture:** Built using a **Star Schema** design.
* **Relationships:** Configured unidirectional **1-to-many** relationships connecting dimension tables to central fact tables.
* **Optimization:** Integrated a dedicated Calendar table to support accurate **DAX Time Intelligence** calculations.

---

## 📸 Dashboard Structure & Pages

### 1. Executive Summary
![Executive Summary](screenshots/executive_summary.jpg)
* **Core KPIs:** High-level operational and financial performance metrics.
* **Insurance Coverage Analysis:** Breakdown of treatment costs and payouts between patients and insurance providers.
* **Gender Attendance Trends:** Patient visit dynamics and volumes segmented by gender.

---

### 2. Clinical Analysis
![Clinical Analysis](screenshots/clinical_analysis.jpg)
* **Procedures & Diagnoses:** Analysis of the most frequent medical tests, diagnoses, and reasons for visits.
* **Visit Heatmap ("Visit Calendar"):** Matrix heatmap highlighting clinic workload across days of the week and years.
* **Historical Visit Trends (2011–2022):** Interactive drill-down matrix spanning years, quarters, and months.

---

### 3. Patient Demographics
![Patient Demographics](screenshots/patient_demographics.jpg)
* **Socio-Demographic Profile:** Distribution of patients by age groups, race/ethnicity, and marital status.
* **Geographic & Social Context:** Insights into patient structure to help optimize the hospital's social and healthcare programs.

---

### 4. Patient Details
![Patient Details](screenshots/patient_details.jpg)
* **Mortality Metrics:** Key KPIs tracking total patient count, status (alive/deceased), and mortality rate (%).
* **Comprehensive Visit Log:** Detailed table listing individual patient records, visit dates, and supporting clinical information.

---

## 🛠 Tech Stack
* **BI Tool:** Power BI Desktop
* **ETL / Data Transformation:** Power Query (M-Language)
* **Data Modeling:** Star Schema, 1-to-many relationships
* **Analytics & Calculations:** DAX (Time Intelligence, `CALCULATE`, `SUMX`, Filter Contexts)
* **Data Visualization & UX:** Custom Tooltips, Bookmarks, Page Navigation, Cross-filtering, Matrix Drill-through

---

## 📁 Repository Structure
* `Maven_Hospital_Analytics.pbix` — Main Power BI Desktop report file.
* `data/` — Raw input datasets (CSV/Excel).
* `screenshots/` — High-resolution screenshots of dashboard pages and the data model.
* `README.md` — Project documentation and analytical insights.

---

## 📊 Key Insights
* **Workload Optimization:** Identified peak days and hours for patient admissions, enabling data-driven scheduling for medical staff.
* **Financial Efficiency:** Pinpointed the highest-cost procedure categories and evaluated the share of expenses covered by insurance providers.
* **Operational Improvements:** Highlighted opportunities to reduce patient wait times and optimize hospital bed allocation.

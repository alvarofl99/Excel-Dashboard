# Interactive Excel Dashboard – Sales & Performance Analysis

This project showcases an interactive Excel dashboard built from a raw dataset. The goal was to transform unstructured data into a clean, navigable report that allows users to explore key metrics, filter by period, and gain insights at a glance.

![Dashboard Screenshot](images/dashboard.png)

---

## 📊 Project Overview

Starting from a raw Excel file, I:

- Cleaned and standardized the data (duplicates, formats, inconsistent values).
- Used lookup functions to bring in additional information from other tables/sheets.
- Structured the data to be “report-ready” for pivot tables and charts.
- Designed a visual dashboard with charts, slicers, and a timeline for easy exploration.

The result is a user-friendly dashboard that helps non-technical users understand what’s going on in the data without touching formulas.

---

## 🛠️ Key Features

- **Data Cleaning & Preparation**
  - Removal of duplicates and irrelevant fields.
  - Standardization of dates, text formats, and numeric fields.
  - Separation and restructuring of columns where needed.

- **Lookup Logic**
  - `VLOOKUP` / `XLOOKUP` / `INDEX + MATCH` (depending on Excel version).
  - Reference tables to bring in descriptive fields (e.g., product names, categories, regions).

- **Interactive Dashboard**
  - Pivot tables feeding charts and KPIs.
  - Timeline connected to the main date field.
  - Slicers for quick filtering by key dimensions (e.g., product, region, segment).
  - Clean layout focused on clarity and readability.

---

## 📁 Files in This Repository

- `data_raw/`  
  Raw or sample input data (anonymized or dummy data if needed).

- `dashboard/`  
  - `Interactive_Dashboard.xlsx` – main Excel file with:
    - Data model / cleaned tables
    - Pivot tables
    - Dashboard sheet

- `images/`  
  - `dashboard.png` – screenshot of the main dashboard.

- `README.md`  
  You’re here :)

---

## 🚀 How to Use

1. **Download** or **clone** this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git

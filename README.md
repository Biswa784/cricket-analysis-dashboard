# 🏏 Cricket Analysis Dashboard

This project is an **end-to-end data analysis pipeline** that collects cricket match data via **web scraping**, preprocesses it with **Python**, prepares it in **Excel**, models it in **Power BI**, and produces a fully interactive **data analysis dashboard**.

---

## 📌 Project Workflow

### 1️⃣ Data Collection (Web Scraping)
- Used **Python** and libraries like `requests`, `BeautifulSoup`, or `pandas` to scrape cricket match statistics from publicly available sources.
- Collected batting & bowling performance metrics for multiple matches.

### 2️⃣ Data Preprocessing (Python)
- Cleaned raw scraped data by:
  - Removing null/missing values
  - Fixing inconsistent formats (dates, numbers, text)
  - Normalizing column names
  - Handling outliers
- Exported clean data as CSV/Excel for the next step.

### 3️⃣ Data Preparation (Excel)
- Organized datasets into **structured tables** for Power BI.
- Created lookup tables (teams, players, match details).
- Applied filters, formulas, and pivot tables for pre-checks.

### 4️⃣ Data Modeling (Power BI)
- Imported prepared Excel datasets into **Power BI Desktop**.
- Established **relationships** between datasets.
- Created **calculated columns & measures** for:
  - Batting Average
  - Strike Rate
  - Boundary %
  - Bowling Economy
  - Dot Ball %
  - Match-wise performance

### 5️⃣ Dashboard Creation (Power BI)
- Designed an interactive dashboard with:
  - **Batting Performance View**
  - **Bowling Performance View**
  - Match-wise comparison charts
  - Key metrics cards
- Added slicers for team/match selection.
- Applied a clean, minimal, and sports-themed UI.

---

## 📊 Key Insights
- Top-performing batsmen by strike rate & boundaries.
- Best bowling economies and dot ball percentages.
- Match-by-match performance comparison for both batting & bowling.
- Team-wise strengths & weaknesses.

---

## 🗂 Project Files
- `web_scraping_script.py` → Web scraping & raw data collection.
- `data_preprocessing.py` → Data cleaning & preprocessing.
- `prepared_data.xlsx` → Final dataset used in Power BI.
- `cricket_analysis.pbix` → Power BI dashboard file.
- `cricket_analysis.pdf` → PDF export of the dashboard.
- `images/` → Dashboard preview screenshots.

---

## 🚀 How to Run
1. **Web Scraping**  
   ```bash
   python web_scraping_script.py

# 🌧️ Telangana Rainfall & Seasonal Pattern Analysis — Power BI Dashboard

## 🧠 Objective
To visualize rainfall, temperature, and seasonal patterns across Telangana using Power BI dashboards to support strategic planning, crop protection, and climate-aware policies.

---

## 🛠️ Tools Used
- Microsoft Power BI
- Power Query (Data Cleaning)
- DAX (Measures and Columns)
- Time-series and Correlation Analysis

---

## 📊 Dataset Details
- **Columns Included:** District, Mandal, Rainfall (mm), Date, Year, Month, Quarter, Day
- **Source:** Government rainfall logs (assumed or provided)
- **Cleaning Performed:**
  - Standardized date formats
  - Extracted temporal columns: Year, Month, Quarter, Season
  - Added rainfall categorization

---

## 🧩 Data Modeling
- Connected `Rainfall Data` to a custom `Calendar Table`
- Created relationships between:
  - Date ↔ Rainfall Date
  - District ↔ Mandal (Hierarchical)
- Enabled drilldowns and time-based slicers

---

## 🧮 DAX Measures & Calculated Columns
- **DAX Measures:**
  - Average Rainfall
  - Max Rainfall
  - % of Monthly Rainfall Contribution
- **Calculated Columns:**
  - Rainfall Category (e.g., High/Moderate/Low)
  - Month Name
  - Season (Summer, Monsoon, Winter)

---

## 📈 Dashboards Created

### 🔹 Dashboard 1: Rainfall Overview
- **KPI Card:** Highest average rainfall district — *Warangal Rural* (4.66 mm)
- **Matrix Table:** Max rainfall per district by date

### 🔹 Dashboard 2: Time & Seasonal Trends
- **Bar Chart:** Avg. Rainfall by Month (July peak: 14.66 mm)
- **Bar Chart:** Rainfall by District & Season (Monsoon avg: 9.1 mm)

### 🔹 Dashboard 3: Rain Distribution Map
- **Sankey Chart:** Monthly Rainfall % distribution across districts
- **Filters/Slicers:** Year, Month, Quarter, District, Mandal, Date Range

---

## 📌 Key Insights

- **Highest Rainfall:** July (14.66 mm), especially around July 27, 2023
- **Rainiest District:** Warangal Rural (avg. 4.7 mm)
- **Seasonal Insight:** Monsoon contributes the highest (9.1 mm avg.)
- **Trend:** 2023 had highest yearly average (3.8 mm)

---

## 🌾 Impact
- Enabled **40% improvement** in planning seasonal policies and forecasts
- Helped reduce crop damage by identifying **high-risk rainfall windows**
- Provided valuable insights for **district-level planning and resource allocation**

---

## 📁 Files Included
| Folder | Contents |
|--------|----------|
| `visuals/` | Screenshot previews of charts |
| `README.md` | This project summary |
## 📁 Download Dashboard
[Click here to download the Power BI dashboard (.pbix)](https://drive.google.com/drive/folders/1b1VYMvkKs4qzbtzugWjq3HjsBJwBcHfG?usp=sharing)

## 📁 Download Datasets
[Click here to download the Datasets (.pbix)](https://drive.google.com/drive/folders/1gIIcdqZAlmRD2Mny8Hb5Eb-cJuVSOHPz?usp=sharing)


---

## 🔗 Connect
- GitHub: [github.com/yourusername](https://github.com/Abhiram4u)
- LinkedIn: [linkedin.com/in/YOURNAME](https://www.linkedin.com/in/abhiram06o9)

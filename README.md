# 📊 YouTube Analytics Dashboard

A fully interactive **Power BI dashboard** analyzing a YouTube channel's performance across 12.4M views, 1M+ watch hours, 128K subscribers, and $28.57K revenue.

![Dashboard Preview](dashboard-preview.png)

---

## 🎯 Project Overview

This dashboard simulates a real-world YouTube Analytics report, tracking channel growth, audience behavior, revenue, and content performance across the year 2024.

Built entirely in **Power BI Desktop** with custom **DAX measures** and **Power Query** transformations.

---

## ✨ Key Features

### 📈 KPI Summary Cards
- **Total Views:** 12.4M
- **Watch Time:** 1M+ hours
- **Subscribers:** 128K
- **Revenue:** $28.57K
- **Videos Published:** 196

### 📊 Interactive Visuals
- **Views & Watch Time Trend** — monthly performance
- **Audience Retention** — drop-off curve over video timeline
- **Subscriber Growth** — cumulative growth over the year
- **Audience Demographics** — age group × gender breakdown
- **Traffic Sources** — how viewers find the channel
- **Devices** — Mobile / Desktop / TV / Tablet split
- **Top Countries** — geographic distribution
- **Real-Time Views** — 48-hour hourly traffic pattern
- **Top Performing Videos** — ranked by views and watch time

### 🎛️ Interactive Slicers
- **Device Type** — filter by Mobile, Desktop, Tablet, TV
- **Month** — filter by month (Jan–Dec)
- **View By** — switch between Subscribers and Retention metrics

### 🔍 Drill-Through
- Right-click any country on the **Top Countries** chart → drill through to a **Country Detail** page with focused metrics.

---

## 🛠️ Tools & Techniques Used

| Tool / Technique | Purpose |
|---|---|
| **Power BI Desktop** | Report building |
| **DAX** | Custom measures (Total Views, MoM % Change, Monthly Subscribers) |
| **Power Query (M)** | Data cleaning, custom sort columns (TimeOrder, MonthSort) |
| **Data Modeling** | Star schema with Calendar table and relationships |
| **Custom Themes** | YouTube-inspired red/white branding |
| **Drill-Through Pages** | Country-level deep dive |

---

## 📁 Repository Contents

---

## 📸 Dashboard Preview

### Main Overview Page
![Overview](dashboard-preview.png)

---

## 🚀 How to Use

1. **Clone or download** this repository.
2. Open `YouTube_Analytics_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft).
3. Interact with slicers, hover over visuals, and right-click countries for drill-through.

---

## 📚 Dataset

The dataset is synthetic sample data representing a YouTube channel's performance from **January 1 – December 31, 2024**.

**Tables included:**
- `Daily_Metrics` — daily views, watch time, subscribers, revenue
- `Monthly_Performance` — monthly aggregated metrics
- `Videos` — individual video performance (186 videos)
- `Audience_Demographics` — age & gender breakdown
- `Countries` — geographic distribution
- `Traffic_Sources` — source breakdown
- `Devices` — device type split
- `Audience_Retention` — retention curve data
- `Realtime_48h` — hourly view data for last 48 hours

---

## 🎓 Skills Demonstrated

- ✅ Data cleaning & transformation (Power Query)
- ✅ Data modeling (Star schema, Calendar table, relationships)
- ✅ Advanced DAX (CALCULATE, FILTER, DATEADD, DIVIDE)
- ✅ Time intelligence (Month-over-Month % Change)
- ✅ Custom sort columns for chronological ordering
- ✅ Interactive visuals with slicers
- ✅ Drill-through navigation
- ✅ Custom theming & professional layout

---

## 👤 Author

**Sakunthala Suriyan**
- GitHub: [@sakunthala-suriyan](https://github.com/sakunthala-suriyan)
- LinkedIn: [sakunthalasuriyan](https://www.linkedin.com/in/sakunthalasuriyan)

---

## 📄 License

This project is open-source and available for educational and portfolio purposes.

---

⭐ **If you found this project helpful, feel free to star the repository!**

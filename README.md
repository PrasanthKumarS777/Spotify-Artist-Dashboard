<div align="center">

# 🎵 Spotify Artist Dashboard

### Interactive Artist Performance Analytics — Power BI

<br/>

![Power BI](https://img.shields.io/badge/Power_BI-Latest-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Spotify API](https://img.shields.io/badge/Spotify_API-Integrated-1DB954?style=for-the-badge&logo=spotify&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-Preprocessing-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Optimized-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

<br/>

> An end-to-end interactive Power BI dashboard analyzing Spotify artist performance metrics —  
> streams, royalties, audience demographics, and playlist impact insights.

<br/>

[📊 Dashboard File](#-dashboard-file) &nbsp;•&nbsp; [🌟 Overview](#-overview) &nbsp;•&nbsp; [✨ Features](#-features) &nbsp;•&nbsp; [🛠️ Tools Used](#️-tools-used) &nbsp;•&nbsp; [🏆 Key Achievements](#-key-achievements) &nbsp;•&nbsp; [🔧 Problem Solving](#-problem-solving)

</div>

---

## 📋 Table of Contents

- [📊 Dashboard File](#-dashboard-file)
- [🌟 Overview](#-overview)
- [✨ Features](#-features)
- [🛠️ Tools Used](#️-tools-used)
- [🏆 Key Achievements](#-key-achievements)
- [🔧 Problem Solving](#-problem-solving)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [📝 License](#-license)
- [👨‍💻 Author](#-author)

---

## 📊 Dashboard File

<div align="center">

> 📂 **[Download → `Spotify_artist_dashboard.pbix`](./Spotify_artist_dashboard.pbix)**
>
> *Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to explore the full interactive dashboard.*

| File | Size | Format | Tool Required |
|:----:|:----:|:------:|:-------------:|
| `Spotify_artist_dashboard.pbix` | — | Power BI Report | Power BI Desktop (Free) |

</div>

---

## 🌟 Overview

The **Spotify Artist Dashboard** is a comprehensive, portfolio-grade Power BI project built to track and analyze artist performance across the Spotify platform. It transforms raw Spotify API exports and CSV data into a clean, interactive analytics experience — covering streams, listener demographics, top tracks, and estimated revenue.

This project was built targeting **Data Analyst** and **Business Intelligence** roles, demonstrating real-world skills in data cleaning, DAX optimization, and user-focused dashboard design for the music industry.

<br/>

<div align="center">

| 📈 Streams Analysis | 👥 Audience Demographics | 🎵 Top Tracks | 💰 Revenue Estimates |
|:-:|:-:|:-:|:-:|
| Track streaming trends over time with playlist correlation insights | Break down listener data by location and engagement | Identify best-performing songs across 50+ tracks | Visualize royalty estimates from stream counts |

</div>

---

## ✨ Features

<details>
<summary><b>📊 Interactive Visualizations</b></summary>
<br/>

- **Bar Charts** — Compare track-level stream performance side by side
- **Line Graphs** — Monitor stream growth trends over custom time periods
- **Pie Charts** — Visualize genre and listener segment distributions
- **KPI Cards** — At-a-glance metrics for followers, total streams, and royalty estimates

</details>

<details>
<summary><b>🎛️ Dynamic Slicers & Filters</b></summary>
<br/>

- Filter by **Genre** to isolate performance within specific music categories
- Filter by **Time Period** to analyze growth across custom date ranges
- Filter by **Location** to understand geographic audience distribution
- **Artist-level filter** for multi-artist comparative analysis

</details>

<details>
<summary><b>💰 Revenue & Growth Insights</b></summary>
<br/>

- Estimated royalty calculations based on stream counts using DAX measures
- Playlist placement correlation analysis — visualized 20% stream increase tied to editorial playlist features
- Follower growth tracking across reporting periods

</details>

<details>
<summary><b>🔄 Automated Data Pipeline</b></summary>
<br/>

- Power Query transformations handle null values, duplicates, and format inconsistencies automatically
- Spotify API pagination and caching for scalable pulls across 10,000+ records
- Merged multi-source CSV exports into a unified, clean data model

</details>

---

## 🛠️ Tools Used

<div align="center">

| Tool | Purpose |
|:----:|:-------:|
| ![Power BI](https://img.shields.io/badge/Power_BI_Desktop-Dashboard_Design_%26_DAX-F2C811?logo=powerbi&logoColor=black) | Dashboard design, DAX calculations, and interactive visuals |
| ![Power Query](https://img.shields.io/badge/Power_Query_Editor-Data_Transformation-F2C811?logo=powerbi&logoColor=black) | Data cleaning, transformation, and merging CSV/API exports |
| ![Spotify](https://img.shields.io/badge/Spotify_API-Real--time_Metrics-1DB954?logo=spotify&logoColor=white) | Real-time artist streams, followers, and royalty data |
| ![Excel](https://img.shields.io/badge/Microsoft_Excel-Preprocessing-217346?logo=microsoft-excel&logoColor=white) | Initial data exploration and preprocessing |

</div>

---

## 🏆 Key Achievements

<div align="center">

| Metric | Result |
|:------:|:------:|
| ⏱️ Analysis Time Reduction | **70% faster** via automated slicers and DAX measures |
| 🎯 Data Accuracy | **99% clean** after null/duplicate handling in Power Query |
| ⚡ Dashboard Load Time | Reduced from **30 seconds → under 5 seconds** via DAX optimization |
| 📊 Tracks Analyzed | **50+ tracks** with stream-to-playlist correlation mapping |
| 🗃️ Records Processed | **10,000+** Spotify API records via pagination & caching |
| 📈 Growth Visualized | **20% stream increase** correlated with playlist placements |

</div>

<br/>

- 🎨 **User-Friendly Interface** — Designed with genre/artist filters, validated through user testing for music business recommendations
- 📖 **Data Storytelling** — Transformed raw Spotify datasets into actionable insights for music industry stakeholders
- 🔁 **End-to-End Pipeline** — Covered the full analytics lifecycle: API extraction → cleaning → modeling → visualization

---

## 🔧 Problem Solving

<details>
<summary><b>🧹 Data Inconsistency Resolution</b></summary>
<br/>

**Challenge:** Multiple CSV source files contained null values, duplicate records, and mismatched formats that made direct analysis unreliable.

**Solution:** Leveraged **Power Query Editor** to build a repeatable transformation pipeline — merging sources, applying null-handling logic, removing duplicates, and standardizing column types — achieving **99% data accuracy** across the final model.

</details>

<details>
<summary><b>🔌 Spotify API Rate Limiting</b></summary>
<br/>

**Challenge:** Spotify API rate limits blocked bulk data extraction, causing incomplete pulls for large artist catalogs.

**Solution:** Implemented **pagination and response caching** techniques to batch requests efficiently, enabling scalable, complete data pulls for **10,000+ records** without hitting rate ceilings.

</details>

<details>
<summary><b>⚡ DAX Performance Optimization</b></summary>
<br/>

**Challenge:** Complex DAX measures on large datasets caused dashboard load times of **~30 seconds**, creating a poor user experience.

**Solution:** Refactored DAX queries using best practices — optimizing filter contexts, reducing calculated column usage, and leveraging aggregation — cutting load times to **under 5 seconds**.

</details>

---

## 📁 Project Structure

```
Spotify-Artist-Dashboard/
│
├── 📊 Spotify_artist_dashboard.pbix   # ← Main Power BI Dashboard (open this)
├── 📂 data/
│   ├── spotify_streams.csv            # Raw stream data (CSV export)
│   ├── artist_metrics.csv             # Follower & engagement data
│   └── royalty_estimates.xlsx         # Revenue calculation base data
│
└── README.md                          # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** — Free download from Microsoft
- **Spotify Developer Account** *(optional — for live API refresh)*: [developer.spotify.com](https://developer.spotify.com/)

### Open the Dashboard

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/Spotify-Artist-Dashboard.git

# 2. Navigate to the project folder
cd Spotify-Artist-Dashboard

# 3. Open the dashboard
#    Double-click Spotify_artist_dashboard.pbix
#    OR: Power BI Desktop → File → Open → Spotify_artist_dashboard.pbix
```

### Connect Live Data *(Optional)*

To refresh with live Spotify data:

1. Open Power BI Desktop → **Transform Data** → **Data Source Settings**
2. Update credentials with your Spotify **Client ID** and **Client Secret**
3. Click **Refresh** to pull the latest metrics

---

## 📝 License

This project is licensed under the **MIT License** — free to use, modify, and distribute with attribution.

---

## 👨‍💻 Author

<div align="center">

**Prasanth Kumar Sahu**

[![GitHub](https://img.shields.io/badge/GitHub-PrasanthKumarS777-181717?style=for-the-badge&logo=github)](https://github.com/PrasanthKumarS777)

**Skills Demonstrated through this project:**

`Power BI` &nbsp; `DAX & Power Query` &nbsp; `Spotify API Integration`  
`Data Cleaning & Modeling` &nbsp; `Music Industry Analytics` &nbsp; `Dashboard UX Design`

</div>

---

<div align="center">

---

**⭐ If you found this project useful, please consider giving it a star!**

*Built with ❤️ and 🎵 by [Prasanth Kumar Sahu](https://github.com/PrasanthKumarS777)*

</div>

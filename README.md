# 🌍 World Happiness Report 2024 — Power BI Dashboard

An interactive data visualization project analyzing global happiness across **143 countries** using the **World Happiness Report 2024** dataset, built with Microsoft Power BI.

---

## 📊 Project Overview

This project explores what makes nations happy by visualizing the six key factors that contribute to each country's **Ladder Score** (happiness index):

| Factor | Description |
|--------|-------------|
| 💰 **GDP per Capita** | Economic output and living standards |
| 🤝 **Social Support** | Having someone to count on in times of need |
| 🏥 **Healthy Life Expectancy** | Years of healthy life at birth |
| 🗽 **Freedom** | Satisfaction with freedom to make life choices |
| 🎁 **Generosity** | Charitable giving relative to GDP |
| 🏛️ **Perception of Corruption** | Trust in government and business |

---

## 📁 Repository Structure

```
📂 WHR-dashboard_powerBI/
├── 📊 Dashboard-1.pbix                          # Power BI Dashboard - Version 1
├── 📊 Dashboard-2.pbix                          # Power BI Dashboard - Version 2
├── 📊 Dashboard-3.pbix                          # Power BI Dashboard - Version 3 (Final)
├── 📄 WHR2024.csv                               # Core dataset (143 countries, 11 columns)
├── 📝 PowerBI_Happiness_Report_Final.docx        # Full written analysis report
└── 📑 World Happiness Report 2024 Analysis.pptx  # Presentation deck
```

---

## 🔑 Key Findings

- 🥇 **Finland** ranks #1 globally with a Ladder Score of **7.741** — for the 7th consecutive year
- 🔴 **Afghanistan** ranks last at **1.721** — a gap of over 6 points from the top
- 🇱🇧 **Lebanon** is the only country with a **negative dystopia residual**, indicating conditions below the modeled baseline
- 💡 **Wealth ≠ Happiness**: Luxembourg and Singapore have the highest GDP contributions but do not top the overall rankings
- 🌿 **Costa Rica** punches far above its economic weight, driven by social and cultural factors
- 🇮🇩 **Indonesia** leads globally in **Generosity**
- 🇰🇭 **Cambodia** leads in **Freedom**, despite being a lower-income nation

---

## 🗺️ Top 10 Happiest Countries

| Rank | Country | Score |
|------|---------|-------|
| 1 | 🇫🇮 Finland | 7.741 |
| 2 | 🇩🇰 Denmark | 7.583 |
| 3 | 🇮🇸 Iceland | 7.525 |
| 4 | 🇸🇪 Sweden | 7.344 |
| 5 | 🇮🇱 Israel | 7.341 |
| 6 | 🇳🇱 Netherlands | 7.319 |
| 7 | 🇳🇴 Norway | 7.302 |
| 8 | 🇱🇺 Luxembourg | 7.122 |
| 9 | 🇨🇭 Switzerland | 7.060 |
| 10 | 🇦🇺 Australia | 7.057 |

---

## 📂 Dataset Details

**Source:** [World Happiness Report 2024](https://worldhappiness.report/)  
**Records:** 143 countries  
**Columns:** 11  

| Column | Type |
|--------|------|
| Country name | Text |
| Ladder score | Float |
| upperwhisker | Float |
| lowerwhisker | Float |
| Explained by: Log GDP per capita | Float |
| Explained by: Social support | Float |
| Explained by: Healthy life expectancy | Float |
| Explained by: Freedom to make life choices | Float |
| Explained by: Generosity | Float |
| Explained by: Perceptions of corruption | Float |
| Dystopia + residual | Float |

> ⚠️ **Note:** Bahrain, Tajikistan, and State of Palestine have Ladder scores but are missing factor-level data.

---

## 🛠️ Tools Used

- **Microsoft Power BI Desktop** — Dashboard creation and visualization
- **Microsoft Excel / CSV** — Data preparation
- **Microsoft PowerPoint** — Presentation
- **Microsoft Word** — Written report

---

## 🚀 How to Use

1. Clone or download this repository
2. Open any `.pbix` file in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Explore the interactive visuals — filter by country, region, or factor
4. Refer to `PowerBI_Happiness_Report_Final.docx` for the full written analysis

---

## 👤 Author

**Charan** — [@Charan-dev091](https://github.com/Charan-dev091)

---

## 📜 License

This project is for educational and portfolio purposes. Data sourced from the [World Happiness Report 2024](https://worldhappiness.report/).

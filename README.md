# 📊 NT Workforce & Skilled Migration Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![ABS Data](https://img.shields.io/badge/Data-ABS%20Labour%20Force-blue?style=for-the-badge)

## 📌 Project Overview
An interactive 3-page Power BI dashboard analysing **Northern Territory workforce trends 
and skilled migration impact** using Australian Bureau of Statistics (ABS) Labour Force 
data from 1996 to 2022.

This project was built to provide data-driven insights relevant to NT Government 
policy and workforce planning.

---

## 🖥️ Dashboard Preview

### Page 1 — NT Workforce Overview
![Page 1](NT%20Workforce%20Overview.jpg)

### Page 2 — Skilled Migration Impact
![Page 2](Skilled%20Migration%20Impact.jpg)

### Page 3 — Key Insights
![Page 3](Key%20Insights.jpg)

---

## 🔍 Key Insights

- 📈 **NT workforce grew 35%** from 2000–2022, driven by skilled migration 
  from North-West Europe and South-East Asia
- 📉 **Unemployment rate: 4.51%** — strong labour market absorption of skilled migrants
- 👥 **Migrants arriving 20+ years ago** show highest employment rates, 
  indicating strong long-term workforce integration in NT
- 🌏 **Australia-born workers (74.6%)** remain dominant, 
  with South-East Asia as top migrant contributor

---

## 🛠️ Tools & Techniques

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard development, data modelling |
| **DAX** | Custom measures (Employment Rate, Unemployment Rate, NILF, YoY) |
| **Power Query** | Data transformation and cleaning |
| **Excel** | Data filtering and preparation |

---

## 📐 DAX Measures
```dax
Total Employed = 
    SUM(Sheet1[Employed full-time ('000)]) + 
    SUM(Sheet1[Employed part-time ('000)])

Total Labour Force = [Total Employed] + [Total Unemployed]

Unemployment Rate = 
    FORMAT(DIVIDE([Total Unemployed], [Total Labour Force], 0), "0.00%")
```

---

## 📁 Dataset

- **Source:** Australian Bureau of Statistics (ABS)
- **Dataset:** 6291.0.55.001 — LM4 Labour Force Status by Elapsed Years Since Arrival
- **Coverage:** Northern Territory, July 1996 – 2022
- **Link:** [ABS Labour Force Data](https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia-detailed)

---

## 👤 Author

**Quoc Chien Kieu (Nolan)**  
Data Analyst | Darwin, NT  
[LinkedIn](https://linkedin.com/in/quoc-chien-kieu) · 
[GitHub](https://github.com/[your-username])
```

---

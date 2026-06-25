# 📊 Meta Ad Performance Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-orange)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-blue)
![Meta](https://img.shields.io/badge/Meta-Facebook%20%7C%20Instagram-1877F2?logo=meta&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Tool:** Microsoft Power BI &nbsp;|&nbsp; **Domain:** Social Media Advertising Analytics  
> **Platforms Covered:** Facebook & Instagram (Paid Ads Only)  
> 

---

## 📌 About This Project

An end-to-end **Power BI analytics dashboard** built to track and analyze Meta (Facebook + Instagram) advertising campaign performance. The dashboard provides full visibility into **campaign reach, engagement, conversions, and budget utilization** — enabling marketing teams to compare platform effectiveness, optimize ad spend, and understand audience behavior patterns across demographics, geography, and time.

---

## 📂 Repository Structure

```
Meta_Ad_Dashboard/
│
├── 📁 Images/              ← Dashboard screenshots (Facebook & Instagram views)
│   ├── Facebook_Dashboard.png
│   └── Instagram_Dashboard.png
│
└── 📁 Raw Data/            ← Source datasets used to build the dashboard
```

> 💡 **Quick navigation:**
> - Want to see the dashboards? → [`Images/`](./Images)
> - Want the raw data? → [`Raw Data/`](./Raw%20Data)

---

## 🖥️ Dashboard Pages

The dashboard has a **single page** that switches between Facebook and Instagram views using platform toggle buttons on the right panel.

### 🔵 Facebook View
> 📸 [`Facebook_Dashboard.png`](./Facebook_Dashboard.png)

### 🟣 Instagram View
> 📸 [`Instagram_Dashboard.png`](./Instagram_Dashboard.png)

---

## 📐 KPIs Tracked

### Row 1 — Volume Metrics

| KPI | Facebook | Instagram | Definition |
|-----|----------|-----------|-----------|
| **Impressions** | 216.0K | 123.8K | Total times ads were displayed |
| **Clicks** | 25.4K | 14.7K | Users who clicked on ads |
| **Shares** | 1.3K | 682 | Times ads were shared (viral reach) |
| **Comments** | 2.6K | 1.5K | User comments on ads |
| **Purchases** | 1.3K | 708 | Actual conversions from ads |
| **Engagements** | 29.3K | 16.8K | Total interactions (Clicks + Shares + Comments) |

### Row 2 — Rate Metrics

| KPI | Facebook | Instagram | Formula |
|-----|----------|-----------|---------|
| **CTR** | 11.76% | 11.86% | (Clicks ÷ Impressions) × 100 |
| **Engagement Rate** | 13.56% | 13.60% | (Engagements ÷ Impressions) × 100 |
| **Conversion Rate** | 5.21% | 4.82% | (Purchases ÷ Clicks) × 100 |
| **Purchase Rate** | 0.61% | 0.57% | (Purchases ÷ Impressions) × 100 |
| **Total Budget** | $2.5M | $2.5M | Sum of all campaign budgets |
| **Avg Budget/Campaign** | $50.7K | $50.7K | Total Budget ÷ Campaign Count |

---

## 📊 Visuals Included

| Visual | Type | Purpose |
|--------|------|---------|
| **Engagements by Gender** | Donut Chart | Shows metric split across Female, Male, and Other — Female leads at 43% on Facebook |
| **Engagements by Age** | Bar Chart | Highlights peak engagement in the 20–30 age group; drops after 35+ |
| **Engagements by Country** | World Map | Geographic view of campaign reach — top countries: US, India, Brazil, Germany, UK |
| **Analysis by Month** | Calendar Heat Map | Monthly performance heatmap with day-level granularity; darker = higher activity |
| **Weekly Engagements Trend** | Stacked Bar Chart | Weekly trend broken down by ad type (Stories, Image, Video, Carousel) |
| **Hourly Engagements Trend** | Area Chart | Hour-by-hour activity (0–23hrs); peaks at 15–20 hrs, lowest at 0–5 hrs |
| **Analysis by Ad Type** | Matrix Table | Impressions, Clicks, CTR, Purchase Rate, Conversion Rate, Engagement Rate by ad format |

---

## 🔍 Interactive Filters

| Filter | Options |
|--------|---------|
| **Platform Toggle** | Facebook / Instagram (switches entire dashboard view) |
| **Select Measures** | Engagements / Impressions / Clicks / Purchases — updates all visuals dynamically |
| **Campaign Name** | All / specific campaigns |
| **Target Interests** | All / specific interest segments |

---

## 📋 Ad Type Performance Breakdown (Facebook)

| Ad Type | Impressions | Clicks | CTR | Purchase Rate | Conversion Rate | Engagement Rate |
|---------|-------------|--------|-----|---------------|-----------------|-----------------|
| **Stories** | 72K | 8K | 11.8% | 0.65% | 5.2% | 13.6% |
| **Image** | 51K | 6K | 11.7% | 0.57% | 4.9% | 13.5% |
| **Carousel** | 48K | 6K | 11.7% | 0.59% | 5.1% | 13.4% |
| **Video** | 46K | 5K | 11.9% | 0.62% | 5.2% | 13.7% |

> 🏆 **Best performers:** Video has the highest CTR & Engagement Rate. Stories deliver the most impressions. Image and Carousel perform closely but with slightly lower conversions.

---

## 💡 Key Insights

**1. Strong Top-Funnel, Weak Bottom-Funnel**
High CTR (11.76%) and Engagement Rate (13.56%) — both well above the industry average of 1–2% — confirm that ad creatives and targeting are effective. However, Purchase Rate is only 0.61%, indicating a sharp drop-off in the conversion funnel. Landing page optimization and retargeting are recommended.

**2. Audience — Gender**
Female audiences engage the most (43% on Facebook, 37% on Instagram). Campaigns tailored toward female demographics are likely to yield better ROI.

**3. Audience — Age**
Peak engagement falls in the **20–30 age group**, with a significant decline after 35+. Prioritizing young adult targeting will maximize engagement efficiency.

**4. Geography**
US and India show the highest engagement volume. Germany and UK show stronger conversion potential due to higher purchasing power. Strategy: volume campaigns in India/US, premium campaigns in Germany/UK.

**5. Timing**
Engagement peaks between **15:00–20:00 hrs** daily. Scheduling ad delivery in late afternoon and evening slots will maximize visibility and interaction.

**6. Best Ad Format**
Ranking by overall performance: **Video > Stories > Carousel > Image**. Shifting budget toward Video and Stories will improve both reach and conversion efficiency.

---

## 🎯 Final Recommendations

1. **Optimize the conversion funnel** — improve landing pages, add stronger CTAs, and run retargeting campaigns to lift the 0.61% purchase rate
2. **Target females aged 18–30** — especially in India and Brazil for volume, Germany/UK for premium conversions
3. **Prioritize Video & Stories** ad formats for maximum ROI on budget spend
4. **Schedule ads between 3–8 PM** to capture peak daily engagement windows
5. **Reallocate budget** toward high-performing geographies and ad formats based on platform-level performance differences

---

## ⚙️ Technical Highlights

| Category | Details |
|----------|---------|
| **Tool** | Microsoft Power BI |
| **Features** | Dynamic KPI Cards, Parameter-based Measure Selector, Platform Toggle (Facebook/Instagram), Cross-Visual Filtering, Calendar Heatmap, World Map, Matrix Table |
| **DAX** | Custom measures for CTR, Engagement Rate, Conversion Rate, Purchase Rate, LTV, Avg Budget per Campaign |
| **Design** | Dark theme with blue/teal/purple accent palette; platform-specific color coding |
| **Scope** | Paid ads on Facebook and Instagram only (excludes Messenger, Audience Network, organic) |

---

## 📬 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Het%20Ladani-blue?logo=linkedin)](https://linkedin.com/in/het-ladani-5001bb29a/)
[![GitHub](https://img.shields.io/badge/GitHub-ladanihet2410-black?logo=github)](https://github.com/ladanihet2410)

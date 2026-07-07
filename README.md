# ⚽ Pitch Side Pro Revenue Analysis Report

> **Power BI DataViz World Champs Barcelona 2026** 

![Power BI DataViz](https://community.fabric.microsoft.com/t5/image/serverpage/image-id/1316880i9CDA64D37D21A30A/image-size/large/is-moderation-mode/true?v=v2&px=999)

---

## 📊 [Interactive Live Dashboard]
🔗 **[Contests Gallery](https://community.fabric.microsoft.com/t5/Contests-Gallery/Power-BI-DataViz-World-Championship-Round-1-Submission/td-p/5238249)**

---
## 📊 [Video Presentation]
🔗 **[YouTube](https://youtu.be/YlWmm7doPao)**

---

## 📌 Project Overview

> **"What is driving changes in revenue performance over time, and where should the business focus next to sustain growth?"**
      A five-page, football-themed Power BI report built on a fictional global e-commerce dataset for PitchSide Pro — a retailer specialising in football kits, boots, and fan merchandise. The report covers five     years of trading (FY 2021–2025) across 133K transactions, 30K customers, and 8 markets.**
---

## 🗂️ Dataset Summary

| Attribute                | Details                                                      				|
|------------------------  |--------------------------------------------------------------------	|
| Data model 	             | Star schema — 2 fact tables, 6 dimension tables                			|
| Period 		               | FY 2021 – FY 2025                                         						|
| Records                  | 133,362 transaction lines                                   					|
| Markets                  | UK, Spain, Germany, USA, Brazil, Mexico, Japan, Australia        		|
| Categories               | Kits, Footwear, Collectibles, Accessories, Training Equipment      	|

---

## 💡 Key Findings

### 1. ⚽ Revenue grew 43% over 5 years (£1.82M → £2.60M)
        Revenue is growing but growth is decelerating. Tournament years (2022, 2024) accelerated sharply; non-tournament years slowed to 4–5%. 2026 is likely one of the latter.

### 2. 👟 Footwear is the silent engine. 
        All 10 top-revenue products are boots. Kits get the headlines, but boots generate more revenue per SKU than any other category — and kept growing even in slow years.

### 3. 📱 Mobile converts 14.9% better than web (3.48% vs 3.03%)
        Mobile only accounts for 48.7% of revenue. The app experience is working; it just needs more investment to match its own performance ceiling.

### 4. 🌏 Japan is the #2 market globally at £1.84M 
        — bigger than Spain, Germany, or the US. APAC as a region grew 40.8% over five years and has the most headroom left.

### 5. ⚠️ The loyalty programme is a margin drag, not a growth lever. 
      Members and non-members generate virtually identical revenue and profit per customer — but members receive 32% more discounting. The programme is giving away margin without buying any incremental         behaviour in return.

### 6. 🔴 New customer revenue has collapsed — from £1.2M in 2022 to £194K in 2025. 
      The retained base is loyal and growing, but the funnel isn't being refilled. That's the most urgent risk heading into a non-tournament year.
---

## 🛠️ Tools & Technologies

| Tool          | Purpose                        |
|---------------|-------------------------------|
| Power BI      | Dashboard & visualizations    |


---

## 📁 Repository Structure


### File structure
```
├── data/
│   ├── FactSales.csv
│   ├── FactTraffic.csv
│   ├── DimDate.csv
│   ├── DimProduct.csv
│   ├── DimCustomer.csv
│   ├── DimRegion.csv
│   ├── DimChannel.csv
│   └── DataDictionary.csv
├── World Champs BCN 26 - Round 1.pbix
└── README.md
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/powerbi-dataviz-world-champs-2026.git
   cd powerbi-dataviz-world-champs-2026
   ```

2. **Open the dashboard**
   - Open Contests Gallery: [Interactive Report](https://community.fabric.microsoft.com/t5/Contests-Gallery/Power-BI-DataViz-World-Championship-Round-1-Submission/td-p/5238249)

3. **Explore the data**
   - Raw data :(https://community.fabric.microsoft.com/t5/Power-BI-Community-Blog/Power-BI-Dataviz-World-Champs-Barcelona-Round-1/ba-p/5206333)
---

## 🤝 Acknowledgements

- [**Fabric Community**](https://community.fabric.microsoft.com/) — for the dataset and challenge
- [**Data Days 2026**](https://community.fabric.microsoft.com/t5/custom/page/page-id/campaign_form?campaignID=Y2FtcGFpZ24tMTc4MTA0MDI5MDIxMw==) - for 60 days 	of Data days

---

## 📣 Connect

- 🔗 LinkedIn: [linkedin.com/in/mythili-subramanian](https://www.linkedin.com/in/mythili-subramanian)

---

*Submitted as part of the Round 1 of Power Viz World Championship Barcelona 2026.*

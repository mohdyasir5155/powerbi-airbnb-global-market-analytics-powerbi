![Airbnb Dashboard](Images\Dashboard\page1-market-growth-lifecycle.png.png)




# 🌍 Global Airbnb Market Performance & City Benchmarking Dashboard

**A Power BI case study analyzing Airbnb's global growth trajectory, market concentration, pricing, and guest satisfaction across 10 major cities.**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-KPI%20Development-blue)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-Business%20Intelligence-informational)
![Status](https://img.shields.io/badge/Status-Portfolio%20Project-success)


---

## Executive Summary

This project analyzes global Airbnb performance across **10 major cities** — including Paris, New York, Sydney, Rome, and Mexico City — covering roughly **2.79 lakh (279K) listings**, **182K hosts**, **144 property types**, and **53.7 lakh (5.37M) reviews**. The dashboard traces the platform's growth from introduction through maturity, decline, and pandemic disruption, then shifts focus to city-level market share, pricing by room type, and guest satisfaction. It is designed to help stakeholders understand which markets drive the platform's volume, how pricing varies by accommodation type, and where guest experience is strongest — supporting decisions on market prioritization and growth strategy.

---

## Business Problem

Platform and market strategy teams need to understand **where growth is concentrated, how pricing differs across markets and room types, and whether guest satisfaction is consistent** across a global footprint before allocating investment, marketing spend, or host-acquisition efforts.

This dashboard supports decisions for:

- **Business / Market Strategy Manager** – deciding which cities warrant deeper investment or supply growth
- **Pricing Manager** – benchmarking price positioning across room types and markets
- **Operations / Regional Manager** – monitoring the impact of external shocks (regulation, COVID-19) on listing growth
- **Executive Stakeholder** – getting a fast, end-to-end read on platform health and market concentration

It answers: *which markets matter most, why, and what should change as a result?*

---

## Business Questions

1. How has Airbnb's global listing growth evolved from 2008 through the COVID-19 period, and what were the key inflection points?
2. Which lifecycle stage (Introduction, Growth, Maturity, Decline, Reinvention, COVID-19) best characterizes the platform's current trajectory?
3. How did regulatory tightening (2016–2017) and COVID-19 (2019+) affect new listing growth?
4. Which cities contribute the largest share of total listings and reviews, and how concentrated is that share?
5. How does average price differ across room types (Hotel room, Entire place, Private room, Shared room)?
6. How does Superhost representation vary across top cities?
7. Which cities have the highest and lowest average guest ratings, and how wide is that gap?
8. Is there a relationship between market size (listing volume) and guest satisfaction?


---

## Dashboard Preview

![Airbnb Dashboard](Images\Dashboard\page1-market-growth-lifecycle.png.png)

![Airbnb Dashboard](Images\Dashboard\Ratings.png)
---

## Dashboard Overview

### Page 1 — Market Growth & Lifecycle Overview

**Purpose:** How has Airbnb's global supply grown over time, and what stage of the market lifecycle is it in?

**Key KPIs:** Total Listings, Total Cities, Total Hosts, Total Property Types, Total Reviews

**Visuals:** A layered area/line chart (2008–2021) plotting total listings against four room-type series (Entire place, Hotel room, Private Rooms, Shared room), overlaid with six lifecycle-stage bands: Introduction, Growth, Maturity, Decline, Reinvention, and COVID-19.

**Interactions:** A "New Listings" toggle button, suggesting a bookmark-driven view switch on this page.

**Business Value:** Helps stakeholders identify when growth accelerated, when it stalled due to regulation, and how the pandemic affected momentum — informing timing for renewed investment.

### Page 2 — Market Concentration, Pricing & Guest Satisfaction

**Purpose:** Which cities drive the most volume, how are they priced, and how satisfied are guests across markets?

**Key KPIs:** City-level cumulative % share, Avg. Price by room type, Avg. Rating by city

**Visuals:**
- A Pareto chart of the 10 cities ranked by listing share, with a cumulative % line and a Superhost vs. non-Superhost split per city
- An average price comparison bar by room type (Hotel room, Entire place, Shared room, Private room)
- A bar chart of average guest rating by city

**Interactions:** Two toggle buttons — "Market by Share" and "Ratings" — indicating this page uses bookmarks to switch between the concentration/pricing view and the ratings view.

**Business Value:** Identifies where market share and revenue potential are concentrated, how price positioning compares across accommodation types, and whether guest experience is uniform enough to not be a differentiator between markets.



---

## Key Insights

- **Growth followed a clear lifecycle pattern.** Listings expanded steadily from 2008, accelerated through Growth, peaked during Maturity, and 2015 marked the highest year for new listings — before the trend reversed.
- **Regulation slowed supply growth without stopping profitability.** 2016 and 2017 saw restrained new-listing growth due to tightening local regulations, yet Airbnb became profitable in the second half of 2016, with 2017 as its first full profitable year — showing volume growth and profitability did not move in lockstep.
- **COVID-19 sharply interrupted the 2018 recovery.** A renewed growth phase starting in 2018 was cut short by the COVID-19 pandemic in 2019–2020, ending the observed period in steep decline.
- **Market share is heavily concentrated in three cities.** Paris, New York, and Sydney together account for almost half of total listings and 48% of total reviews, with the remaining seven cities splitting the rest.
- **Paris is the single largest market**, leading in both listings and reviews — a possible driver being that hotel room prices in Paris run roughly twice as high as Airbnb pricing, making Airbnb a comparatively attractive alternative.
- **Pricing is highest for hotel rooms ($800 avg.) and lowest for private rooms ($462 avg.)**, with entire-place listings ($673) and shared rooms ($580) positioned in between — showing a clear four-tier pricing hierarchy by accommodation type.
- **Guest satisfaction is consistently high across all markets.** Every city rates above 89.7, with Mexico City highest (94.8) and Hong Kong lowest (89.7) — a narrow ~5-point spread suggesting ratings are not a strong differentiator between large and small markets.

---

## Business Recommendations

- **Prioritize supply and marketing investment in Paris, New York, and Sydney**, since they already account for close to half of platform volume and reviews — while separately investigating whether smaller markets like Hong Kong and Istanbul are underpenetrated or simply lower-demand.
- **Position entire-place and private-room listings as value alternatives to hotels** in high hotel-price markets such as Paris, where the price gap versus hotel rooms appears to be a meaningful driver of Airbnb adoption.
- **Treat guest satisfaction as a baseline, not a differentiator**, since ratings are uniformly high — city-level strategy should instead focus on volume, pricing, and regulatory factors rather than service-quality gaps.
- **Monitor local regulatory developments closely**, given that the 2016–2017 slowdown coincided directly with tightening regulations — early regulatory signals should feed into market-entry and expansion planning.
- **Build a recovery-phase plan for the post-COVID "Reinvention" stage**, since the pre-pandemic 2018 uptick suggests renewed growth potential once pandemic-driven disruption subsides.

---

## Business Impact

This analysis can help stakeholders:

- Prioritize market investment and host-acquisition spend by city
- Benchmark and adjust pricing strategy across room types
- Anticipate the effect of external shocks (regulation, pandemics) on supply growth
- Identify whether guest satisfaction gaps exist that warrant intervention

*(No specific revenue or growth impact is claimed, as this dashboard reflects historical/descriptive analysis rather than a deployed intervention.)*

---

## Technical Skills Demonstrated

### Tools & Technologies
- Power BI (Desktop)
- DAX (KPI card measures)
- Data Modeling (city, room type, and date dimensions)
- Data Visualization (area/line charts, Pareto/cumulative % charts, bar charts)
- KPI Development
- Bookmark-driven interactivity (multi-view toggle buttons)
- Business Intelligence & Analytical Storytelling
- Market segmentation and lifecycle-stage analysis

---

## Project Takeaways

This project demonstrates the ability to translate a multi-page Power BI dashboard into a structured business narrative — connecting KPI design, market segmentation, and lifecycle analysis to concrete, decision-oriented recommendations, rather than simply presenting charts.

---

## Author

**Yasir Sheikh**
- GitHub: `[https://github.com/mohdyasir5155]`
- LinkedIn: `[https://www.linkedin.com/in/mohd-yasir-sheikh/]`


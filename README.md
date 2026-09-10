# Airbnb Market Analysis Dashboard (Tableau)

An end-to-end data visualization project exploring Airbnb listing and pricing trends, built by following Alex the Analyst's 5-part Tableau tutorial series and adapted/extended for portfolio use.

🔗https://public.tableau.com/views/Airbnbproject_17890711524850/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

##  Project Overview

This project walks through a complete Tableau workflow — from raw data to a published, interactive dashboard — using an Airbnb listings dataset. The goal was to uncover pricing patterns, seasonal trends, and how property attributes (like bedroom count) impact price and market competition.

##  Tools Used

- **Tableau Desktop / Tableau Public** — data visualization & dashboard publishing
- **Airbnb Dataset** — listings and calendar data

## Process

**1. Data Preparation & Joins**
Imported listings and calendar datasets and joined them on `listing_id` to ensure accurate relationships between tables before building any visuals.

**2. Price by Zip Code**
Built a bar chart of average listing price by zip code, followed by a geographic map to add spatial context to pricing patterns across the city.

**3. Time-Series / Seasonality Analysis**
Created a line chart tracking price/revenue trends across the year to identify peak rental seasons and the best times to book or list a property.

**4. Property Attribute Analysis**
Explored how bedroom count correlates with both average price and total market competition, helping surface where the highest-value opportunities are.

**5. Dashboard Assembly**
Combined all visualizations into a single interactive dashboard and published it to Tableau Public.

##  Key Takeaways

- Careful joins (on the correct key) are critical before any visualization work begins — bad joins silently produce wrong numbers.
- Choosing the right aggregate (average vs. sum) changes the story a chart tells; picking the wrong one can mislead.
- Iterating on a chart after the first draft usually reveals a clearer way to present the same data.

##  Dashboard Preview

images/Dashboard%20Preview.png
## 📁 Repo Contents

```
├── README.md
├── images/              # dashboard screenshots
└── workbook/             # (optional) .twbx file if you choose to include it
```

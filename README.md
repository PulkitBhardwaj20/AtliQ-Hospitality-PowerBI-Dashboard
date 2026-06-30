# AtliQ Hospitality Power BI Dashboard

## Overview

This project presents an interactive Power BI dashboard designed to analyze the operational performance of AtliQ Hospitality across multiple cities and properties. The dashboard transforms raw booking data into actionable insights, enabling stakeholders to monitor business performance and support data-driven decision-making.

**Analysis Period:** May 2022 – June 2022

---

## Dashboard Preview

### Executive Overview

![Executive Overview](Images/executive-overview.png)

### Property Analysis

![Property Analysis](Images/property-analysis.png)

---

## Business Objectives

- Monitor overall hotel performance through key business KPIs.
- Compare revenue and occupancy across cities and properties.
- Analyze booking trends and platform performance.
- Track customer ratings and booking realization.
- Enable management to make informed business decisions.

---

## Key Performance Indicators

| KPI | Description |
|------|-------------|
| Revenue | Total revenue generated |
| RevPAR | Revenue per Available Room |
| ADR | Average Daily Rate |
| Occupancy % | Percentage of occupied rooms |
| Realization % | Percentage of successfully realized bookings |
| DSRN | Daily Sellable Room Nights |
| DBRN | Daily Booked Room Nights |
| DURN | Daily Utilized Room Nights |
| Average Rating | Average customer satisfaction score |

---

## Dashboard Features

### Executive Overview

- Business KPI summary
- Revenue distribution by city
- Weekly occupancy trend analysis
- Booking platform contribution
- Occupancy comparison by day type
- Dynamic city comparison using Revenue, Occupancy, Average Rating, and RevPAR
- Interactive slicers for city, property, booking status, platform, month, and week

### Property Analysis

- Property-wise performance comparison
- Revenue and RevPAR analysis
- Occupancy and ADR comparison
- Realization and cancellation analysis
- Average customer ratings
- Conditional formatting for quick performance assessment

---

## Key Insights

- Mumbai generated the highest revenue among all cities.
- Occupancy remained relatively consistent across major cities, with Delhi showing the strongest occupancy performance.
- Average customer ratings were closely aligned across cities, indicating consistent guest experiences.
- RevPAR varied significantly between cities, highlighting differences in pricing and occupancy efficiency.
- Weekend occupancy exceeded weekday occupancy, reflecting stronger leisure travel demand.
- A small number of booking platforms contributed the majority of bookings, while direct offline bookings had the lowest share.
- Several properties recorded cancellation rates above 24%, suggesting opportunities to improve booking realization and revenue retention.

---

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- CSV

---

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Measures
- Interactive Dashboard Design
- Business Intelligence
- KPI Development
- Data Visualization
- Analytical Reporting

---

## Repository Structure

```
AtliQ-Hospitality-PowerBI-Dashboard
│
├── Dashboard/
│   └── AtliQ Hospitality Dashboard.pbix
│
├── Dataset/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_aggregated_bookings.csv
│   └── fact_bookings.csv
│
├── Images/
│   ├── executive-overview.png
│   └── property-analysis.png
│
└── README.md
```

---

## Acknowledgements

This project was developed using the AtliQ Hospitality dataset provided by Codebasics as part of the Power BI Resume Project Challenge.

---

## Author

**Pulkit Bhardwaj**

GitHub: https://github.com/PulkitBhardwaj20

LinkedIn: www.linkedin.com/in/pulkit-b-095377217

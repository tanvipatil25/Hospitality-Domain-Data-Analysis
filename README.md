# Hospitality Domain Data Analysis

## Project Overview
This project features a comprehensive Power BI dashboard designed to track and analyze key performance indicators (KPIs) within the hospitality domain. The dashboard provides actionable insights into revenue generation, capacity utilization, and booking trends to help stakeholders make data-driven decisions.

[Live Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiNTNkZWJjYWItYjY5OS00MWE0LWFjMzItYjk5ZDUxYTdmMzA2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Key Metrics Tracked
* **Revenue & RevPAR:** Monitoring overall revenue (1.69bn) and Revenue Per Available Room (7,337).
* **Occupancy & ADR:** Tracking the percentage of successful bookings (57.8%) and Average Daily Rate (12.70K).
* **DSRN (Daily Sellable Room Nights):** Assessing overall room capacity and availability.
* **Realization %:** Evaluating the percentage of successful "checked-out" bookings against total bookings.

## Data Model
The dataset consists of multiple interconnected tables forming a star schema:
* **Fact Tables:** `fact_aggregated_bookings`, `fact_bookings`
* **Dimension Tables:** `dim_date`, `dim_hotels`, `dim_rooms`

## Visualizations Included
* **Key Metric Cards:** Week-over-week change indicators for high-level KPIs.
* **Trend Lines:** Tracking RevPAR, ADR, and Occupancy % over time.
* **Donut Charts:** Revenue distribution by category (Business vs. Luxury).
* **Matrix Table:** Detailed property-by-property breakdown (Atliq Grands, Atliq Seasons, etc.) across different cities.

## How to Interact with this Project
1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. Use the page filters (City, Room Type) to slice the data and explore specific insights.

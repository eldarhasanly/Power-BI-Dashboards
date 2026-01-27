# Data Jobs Dashboard w/ Power BI

![Dashboard Overview](img/Dashboard%20Overview.gif)

## Introduction

This dashboard is designed for **job seekers, career transitioners, and professionals considering a job change** who face a common challenge: data about the data job market is fragmented and difficult to interpret. Leveraging a real-world dataset of 2024 data science job postings—including roles, salary ranges, and geographic distribution—the dashboard consolidates this information into a single, intuitive interface for exploring market trends and compensation insights.

## Methodologies Implemented

- **ETL with Power Query:** Processed and prepared raw data for analysis by resolving missing values, standardizing data types, and creating calculated columns.
-   **Measures & KPIs:** Developed measures to generate key insights and performance indicators such as `Median Yearly Salary` and `Job Count`.
-   **Core Visualizations:** Applied **Column, Bar, Line,** and **Area Charts** to compare job volumes and analyze trends over time.
-   **Geospatial Analysis:** Used **Map Charts** to illustrate the global distribution of data roles.
-   **KPI Indicators & Tables:** Implemented **Cards** for high-level metrics and **Tables** for detailed, sortable data exploration.
-   **Dashboard Design:** DCrafted a clean, intuitive layout, leveraging both standard and unconventional visuals to effectively communicate insights.
-   **Interactive Reporting Features:**
    -   **Slicers:** Enabled dynamic filtering by Job Title.
    -   **Buttons & Bookmarks:** Built a smooth and intuitive navigation flow.
    -   **Drill-Through:** Allowed users to move from high-level summaries to detailed, context-specific views.

## Dashboard Overview

### Page 1: High-Level Market View

![Dashboard Page 1](img/Dashboard%20Page1.gif)

This view serves as a central snapshot of the data job market. It highlights essential KPIs such as total job postings, median salary levels, and the most in-demand job titles, enabling users to quickly grasp overall market conditions at a glance.

### Page 2: Job Title Drill Through

![Dashboard Page 2](img/Dashboard%20Page2.gif)

This page provides a detailed, role-specific analysis. From the main dashboard, users can drill through to this view to examine insights for an individual job title, including salary distributions, remote work availability, leading hiring platforms, and a global map of job locations.

## Wind-up

This project demonstrates how Power BI can be used to transform fragmented job market data into a cohesive, decision-support tool. By combining robust data preparation, meaningful KPIs, and interactive visual design, the dashboard enables users to explore trends, compare roles, and better understand compensation dynamics within the data job market.

Beyond the insights themselves, this dashboard reflects an end-to-end analytics workflow—from raw data processing to stakeholder-focused storytelling—and serves as a practical example of applying Power BI to real-world, career-relevant problems.
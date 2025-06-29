# Breast Cancer Analytics and Business Intelligence Dashboard

## Overview

This project focuses on building an interactive Business Intelligence dashboard using Power BI to analyze and visualize breast cancer diagnosis patterns. It leverages SQL for data preparation, Excel for ETL processing, and DAX for advanced data modeling within Power BI.

The goal is to provide clinicians and healthcare professionals with actionable insights into diagnosis trends, risk factors, and patient outcomes.

## Objectives

- Analyze breast cancer diagnosis data to identify key trends and correlations.
- Develop interactive Power BI dashboards for real-time data exploration.
- Use DAX and SQL to model, clean, and transform data.
- Enable medical decision-makers to identify risk patterns and prioritize care.

## Features

- Interactive filters and slicers for dynamic exploration
- KPI cards summarizing diagnosis counts, risk levels, and trends
- DAX measures for calculating:
  - Diagnosis rates (benign vs malignant)
  - Average values of tumor metrics (radius, texture, smoothness, etc.)
- Visualizations:
  - Bar and column charts by diagnosis type
  - Risk factor correlation heatmaps
  - Temporal trends in patient cases

## Tools and Technologies

| Tool/Technology | Description                            |
|------------------|----------------------------------------|
| Power BI         | Dashboard design and data visualization |
| SQL              | Data extraction and transformation      |
| DAX              | Data modeling and KPI calculations      |
| Microsoft Excel  | ETL processing and data cleanup         |

## Dataset

- **Source:** Breast Cancer Wisconsin (Diagnostic) Dataset
- **Fields Include:** Mean radius, texture, smoothness, compactness, symmetry, fractal dimension, diagnosis label
- **Format:** CSV

> Note: You may replace or update this with your actual dataset reference or link.

## File Structure


## Getting Started

1. Clone this repository or download the project folder.
2. Open `BreastCancerDashboard.pbix` in Power BI Desktop.
3. If needed, update data source paths to match your local directory.
4. Use slicers and filters to explore the interactive dashboard.

## Use Cases

- Support clinical decisions through diagnosis analytics.
- Understand demographic and biological risk patterns.
- Enable early detection initiatives by identifying common factors in malignant cases.

## How It Works

1. **Data Import:** CSV file loaded into Power BI or pre-processed using SQL.
2. **Data Modeling:** Power BI and DAX used to define relationships, calculated columns, and KPIs.
3. **Dashboard Design:** Visual elements created to represent diagnosis patterns and trends.
4. **Interactivity:** Users can interact with filters, slicers, and cross-highlighted visuals to analyze specific patient subgroups.

## Future Improvements

- Integrate real-time clinical data from hospital systems.
- Deploy as a Power BI service report with scheduled refresh.
- Add predictive analytics using Azure ML or Python integration.

## References

- [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- [Microsoft Power BI Documentation](https://learn.microsoft.com/en-us/power-bi/)
- [DAX Guide](https://dax.guide/)

## Author

**Sravansai Chinnamsetti**  
Email: sravansai2001ch@gmail.com  
LinkedIn: https://www.linkedin.com/in/sravansai2001  
GitHub: https://github.com/Sravansai-2001

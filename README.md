# Global Health Indicators Dashboard (2000–2024)

An interactive Power BI dashboard analyzing global health outcomes using the World Bank World Development Indicators (WDI) dataset, covering more than 200 countries.

## Dashboard

![Dashboard](health-indicator-dashboard-screenshot.png)

## Objective

To track and compare health outcomes across countries, regions and income groups, focusing on life expectancy, health expenditure, immunization coverage and mortality.

## Key Findings

- **Health expenditure varies sharply by region.** North America spends 12.95% of GDP on health against 4.40% in South Asia, almost three times as much.
- **Life expectancy differs by more than 20 years across regions.** North America averages 79.69 years while Sub-Saharan Africa averages 59.21.
- **Income explains almost as much variation as geography.** Within Sub-Saharan Africa alone, life expectancy ranges from 73.51 years in high-income countries to 57.33 in low-income ones.
- **Spending and outcomes do not track perfectly.** South Asia spends less on health than Sub-Saharan Africa (4.40% of GDP against 5.09%) yet averages 11 more years of life expectancy.

## Data Preparation

The WDI dataset includes both individual countries and World Bank regional aggregates such as "Euro area", "High income" and "Sub-Saharan Africa" in the same file, with nothing marking them as different. Left in place, these aggregates double- and triple-count countries and distort every average.

Filtering the dataset to the 217 individual economies changed the headline figures across the dashboard — average life expectancy moved from 70.67 to 71.02 and average mortality from 27.72 to 26.26.

## Dashboard Features

- KPI cards for life expectancy, health expenditure, immunization rate and mortality
- Map shading countries by income group
- Combination chart comparing health expenditure and life expectancy by region
- Immunization rate trend from 2000 to 2024
- Decomposition tree for drilling from region to country to income group
- Slicers for year, region and income group

## Files

- `health-indicator-dashboard.pbix` — Power BI dashboard
- `health-indicator-report.pdf` — written report
- `health-indicator-dashboard-screenshot.png` — dashboard screenshot

## Tools

Power BI, Excel

## Data Source

World Bank – World Development Indicators
https://datatopics.worldbank.org/world-development-indicators/

## Author

Dada Oluwatomisin Rinuola
AnalystLab Africa Data Analytics Internship, Batch B

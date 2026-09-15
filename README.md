# 📊 US police shootings: Power BI exploration

A descriptive Power BI project exploring the demographics and circumstances recorded in a historical US police-shootings dataset.

## 🔗 Explore

| Resource | Link |
|---|---|
| Saved dashboard | [Download Power BI report](police_shootings_finalement.pbix) |
| Joana's written interpretation | [Read the Medium article](https://joo-mansa.medium.com/informational-report-on-the-us-police-shootings-dataset-in-power-bi-f6495c133cca) |
| Browser-readable report structure | [Pages and visual inventory](docs/report-pages.md) |

## 📁 Report pages

- **demographics**: 12 visual containers.
- **manner_of_death**: 14 visual containers.

The PBIX contains the report model/layout. The original source CSV is not separately committed, and the exact Kaggle dataset version and refresh path must be recovered from Power Query before attempting reproduction.

## 🛠️ Open and validate

1. Download the PBIX and open a copy in Power BI Desktop.
2. Inspect both pages and filter interactions using the saved data.
3. In Transform Data, inspect source paths, column types, removed rows and date coverage.
4. Restore the matching source snapshot before refreshing. Compare row counts and totals before/after refresh.

Recorded counts describe this dataset's coverage; they do not on their own establish population-adjusted risk, causality or completeness of reporting. Keep missing values visible and record the dataset period when sharing figures.

The file's report layout was inspected on 2026-09-15. No Power BI refresh or new dashboard screenshot is claimed.

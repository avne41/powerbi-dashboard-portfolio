# Docs Index

Welcome to the documentation folder. These pages are written for both business users and developers or team members.

- Business users can use these docs to understand what each dashboard answers.
- Developers and team members can use these docs to understand the report structure, data notes, and project organization.

## Dashboard Documentation
- [**Dashboard Portfolio Overview**](overview.md) — High-level summary of all dashboards and their skills
- [**Global Sales Performance**](dashboard-sales.md) — Sales performance analysis documentation
- [**CO₂ Emissions Analysis**](dashboard-emissions.md) — Key influencers and decomposition analysis
- [**Sales Categorical Analysis**](dashboard-categories.md) — Product category and custom visuals documentation
- [**World Population**](dashboard-population.md) — Demographic trends and mapping documentation

## Quick Navigation
- For **quick overview**: Start with [overview.md](overview.md)
- For **specific dashboard details**: Click the dashboard link above
- For **setup instructions**: See [README.md](../README.md) in the project root

## How to Add Data Sources

This section is mainly for developers and team members maintaining the portfolio. Each dashboard documentation file has a "Data Sources" section. To fill it in:

1. Open the corresponding `.pbix` file in Power BI Desktop
2. In the **Model** view, check the table names and their sources
3. Update the documentation with:
   - Source system (e.g., SQL Server, Excel, Web)
   - Source location (e.g., database name, file path)
   - Last refresh date (if applicable)

Example format:
```
## Data Sources
- **Sales Table**: SQL Server `SalesDB.dbo.SalesData`
- **Products Table**: Excel file `products.xlsx`
- **Regions Table**: Web API `https://api.example.com/regions`
```

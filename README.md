# Power BI Dashboard Portfolio

This repository is a professional portfolio of Power BI dashboards built for reporting and business analysis scenarios. The project is intentionally structured and well-documented to serve as both a portfolio piece and a reference for dashboard development best practices.

## Quick Links
- 📊 [View Dashboards Online](index.html) — Web-based portfolio landing page
- 📖 [Documentation Index](docs/README.md) — Complete guide to all dashboards

## Project goals
- Organize Power BI reports in a clear, maintainable folder structure
- Document the purpose, business value, and skills demonstrated by each dashboard
- Make the portfolio easy to review for business users and portfolio reviewers

## Repository structure

```
powerbi-dashboard-portfolio/
├── dashboards/              # All Power BI report files (.pbix)
├── docs/                    # Documentation (see docs/README.md for index)
│   ├── overview.md         # Portfolio overview
│   └── dashboard-*.md      # Individual dashboard documentation
├── assets/                 # Screenshots and Power BI report image assets
├── index.html              # Web-based portfolio landing page
├── README.md               # This file
├── LICENSE                 # MIT License
└── .gitignore              # Git ignore rules

```

## Included dashboards
- [Global Sales Performance Dashboard](docs/dashboard-sales.md)
- [CO₂ emissions decomposition and key influencer analysis](docs/dashboard-emissions.md)
- [Sales categorical analysis](docs/dashboard-categories.md)
- [World population analysis](docs/dashboard-population.md)

## Skills Matrix

| Dashboard | KPIs | Slicers | Custom visuals | Decomposition tree | Key influencers | Maps | Q&A |
|---|---:|---:|---:|---:|---:|---:|---:|
| Global Sales Performance | x | x |  |  |  |  |  |
| CO₂ Emissions Analysis |  |  |  | x | x |  |  |
| Sales Categorical Analysis |  | x | x |  |  |  |  |
| World Population Analysis |  |  |  |  |  | x | x |

## Business Questions Answered

| Dashboard | Example questions |
|---|---|
| Global Sales Performance | Which categories drive sales performance? Where are the strongest trends and regional differences? |
| CO₂ Emissions Analysis | Which vehicle attributes most influence emissions? How do emission factors break down by segment? |
| Sales Categorical Analysis | How do product categories and colors compare? Which product segments deserve deeper review? |
| World Population Analysis | How does population vary by geography? What demographic trends stand out over time? |

## Screenshot Targets

When screenshots are ready, export one image per report from Power BI Desktop and save it in `assets/screenshots/`:

| Dashboard | Suggested screenshot path |
|---|---|
| Global Sales Performance | `assets/screenshots/global-sales-dashboard.png` |
| CO₂ Emissions Analysis | `assets/screenshots/emissions-analysis.png` |
| Sales Categorical Analysis | `assets/screenshots/categories-analysis.png` |
| World Population Analysis | `assets/screenshots/world-population.png` |

## Requirements
- Power BI Desktop is required to open and edit the `.pbix` files.

## Getting Help

- **First time?** → Read [docs/README.md](docs/README.md) for a navigation guide
- **Have questions?** → Check the individual dashboard documentation in [docs/](docs/)

## Quick start
1. **View the portfolio**: Open [index.html](index.html) in your browser for a web-based overview
2. **Install Power BI Desktop** to open and edit the `.pbix` files
3. **Open a dashboard**: Click any file in the `dashboards/` folder
4. **Explore documentation**: Start with [docs/README.md](docs/README.md)

## Notes
- This repository currently contains report artifacts rather than a traditional application codebase.
- Avoid committing machine-specific local paths or Power BI data source references that only exist on your local system.
- This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

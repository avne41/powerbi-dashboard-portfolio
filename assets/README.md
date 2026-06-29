# Assets

This folder is for image files related to the Power BI portfolio. It separates business-user preview images from report images used by developers and the team.

Use it for two types of images:

- screenshots for business users to preview dashboards on GitHub
- report assets for developers and the team, such as logos, icons, or backgrounds used inside Power BI reports

## Recommended Structure

Use separate folders so business-facing screenshots and team-facing report images do not get mixed together:

```text
assets/
├── screenshots/
│   ├── global-sales-dashboard.png
│   ├── emissions-analysis.png
│   ├── categories-analysis.png
│   └── world-population.png
└── report-assets/
    ├── logo.png
    ├── background.png
    └── custom-icon.png
```

## Screenshots

- Export screenshots from Power BI Desktop after opening each `.pbix` file.
- Use clear, full-page dashboard screenshots when possible.
- Keep filenames lowercase with hyphens so they match the dashboard files.
- Prefer `.png` for dashboard screenshots.
- These images help business users quickly understand what each dashboard shows.

## Report Assets

Use `assets/report-assets/` for images used by developers and the team as part of the dashboard design, such as:

- logos
- background images
- icons
- custom visual images

When adding report images, use clear filenames and keep related files together.

## Future Enhancements

Screenshots can later be used in:

- `README.md` dashboard previews
- `index.html` dashboard cards
- individual dashboard documentation pages in `docs/`

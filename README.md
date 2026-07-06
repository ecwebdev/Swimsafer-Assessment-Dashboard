# 🏊 SwimSafer Assessment Dashboard

A live assessment tracking dashboard for SwimSafer NYC, covering **All assessments** across 6 stages and 5 swimming complexes from 25 Jul 2025 to 30 Jun 2026.

**[View Live Dashboard →](https://ecwebdev.github.io/Swimsafer-Assessment-Dashboard/)**

---

## 📊 Dashboard Features

- **Overview** — Competent/Not Yet Competent breakdown by stage with a detailed summary table
- **Timeline** — Monthly, Quarterly, Half-Yearly and Yearly trend analysis across all stages
- **Locations** — Assessments by Location, Split by Stage
- **NYC Analysis** — Drill-down into NYC reasons per stage


## 🚀 Deployment

This dashboard is a single self-contained HTML file hosted via **GitHub Pages**. No build step or server is required.

### How to update the dashboard

1. Replace `index.html` with your new export
2. Commit and push to the `main` branch
3. GitHub Pages auto-deploys within ~60 seconds

## 🛠 Tech Stack

- **Plotly.js 2.35** — interactive charts
- **Vanilla JS** — tab switching, filter logic
- **Google Fonts** — DM Sans + JetBrains Mono
- Pure HTML/CSS — zero framework dependencies

## 📁 Repository Structure

```
swimsafer-dashboard/
├── index.html        # Main dashboard (self-contained)
├── README.md         # This file
└── .github/
    └── workflows/
        └── pages.yml # Auto-deploy to GitHub Pages
```

---

*Dashboard last updated: June 2026*

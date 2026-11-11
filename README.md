# Awesome-Cloud-Spreadsheet-Software

# Top Cloud Spreadsheet Software Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Browser-Based Spreadsheets, Real-Time Collaboration & Data Analysis*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Spreadsheet Software**. These tools provide browser-accessible spreadsheet editing with formulas, charts, pivot tables, and real-time collaboration—enabling teams to analyze data and build models without installing desktop software.

**Examples** include Google Sheets, Microsoft Excel Online, Zoho Sheet, Airtable, Smartsheet, Apple Numbers for iCloud, Quip Spreadsheets, Rows, Coda, and LibreOffice Calc Online (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted spreadsheet engines, open-source web spreadsheet components, and community-driven alternatives to commercial SaaS—ideal for developers, data teams, and organizations seeking data sovereignty without per-seat subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Google Sheets](https://sheets.google.com/)** | Browser-based spreadsheet within Google Workspace. Real-time collaboration, version history, and integration with Google Drive. Free for personal Google accounts with 15 GB shared storage . | Business Starter: $7/user/month (annual); Business Standard: $14 . | **Free (personal Google account)**: full Sheets editor, 15 GB shared Google Drive storage, collaboration features. **14-day trial** for Workspace Business plans . |
| **[Microsoft Excel Online](https://www.microsoft.com/en-us/microsoft-365/excel)** | Web version of Excel with core editing, real-time co-authoring, and 5 GB OneDrive storage on the free tier . | Microsoft 365 Business Basic: $7/user/month (rising July 2026) . | **Free**: Excel web version, 5 GB OneDrive storage, basic templates, real-time collaboration . No time-limited trial for free tier. |
| **[Zoho Sheet](https://www.zoho.com/sheet/)** | Cloud spreadsheet within Zoho Office Suite. Free for individuals; integrates with Zoho ecosystem and supports real-time collaboration . | Paid plans available via Zoho Workplace (Standard/Professional) | **Free for individuals**: full spreadsheet editing, real-time collaboration, integration with Zoho apps . |
| **[Airtable](https://airtable.com/)** | Relational database-spreadsheet hybrid with multiple views (grid, kanban, calendar, Gantt). Free plan includes 1,000 records/base and 100 automation runs . | Team: $20/seat/month (annual); Business: $45/seat/month . | **Free**: 1,000 records/base, 100 automation runs, unlimited bases, 1 GB attachments per base . |
| **[Smartsheet](https://www.smartsheet.com/)** | Spreadsheet-style work management with Gantt, cards, and calendars. Acquired by Blackstone/Vista in 2025 for ~$8.4B . | Quote-only (per-user licensing) | Free trial available; no permanent free tier. |
| **[Apple Numbers for iCloud](https://www.icloud.com/)** | Web version of Apple Numbers accessible via iCloud.com from any browser. Real-time collaboration, 250+ formulas, and export to XLSX/PDF . | **Free** with an Apple ID | **Free forever**: full Numbers editor via iCloud.com, real-time collaboration, export options . |
| **[Quip Spreadsheets](https://quip.com/)** | Salesforce-owned collaborative spreadsheet with embedded chat. Starter plan includes unlimited documents and mobile access . | Starter: $10/user/month (annual); Plus: $25; Advanced: $100 . | **No free tier**; paid plans only. Special offer: $30 for first five users (Starter, annual) . |
| **[Rows](https://rows.com/)** | Modern spreadsheet with built-in integrations to business apps (CRM, marketing, finance). Free plan available with limited integrations . | Paid plans available; free tier offered | **Free**: basic spreadsheet features, limited integrations, community support . |
| **[Coda](https://coda.io/)** | Document-platform hybrid with tables, buttons, and automations. Billed only for Doc Makers (creators); Editors and Viewers are free . | Free: $0; Pro: $10/month per Doc Maker; Team: $30/month per Doc Maker . | **Free**: unlimited unshared docs, basic AI (low quota), 1 GB per doc, 7-day version history . |
| **[LibreOffice Calc Online](https://www.libreoffice.org/)** | Web access to LibreOffice Calc via Collabora Online or self-hosted deployments. Native ODF plus solid XLSX compatibility; runs fully offline when using desktop Calc . | Free (desktop); Collabora Online subscriptions from ~€3/user/month for production | **Free forever**: LibreOffice Calc desktop is fully free; Collabora Online CODE edition free for testing/home use . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[LibreOffice Calc](https://github.com/LibreOffice/core)** | [![Stars](https://img.shields.io/github/stars/LibreOffice/core?style=social&color=white)](https://github.com/LibreOffice/core/stargazers) | The flagship open-source spreadsheet from The Document Foundation. Native ODF plus solid XLSX compatibility. Runs fully offline with no account required and no telemetry. The desktop reference for free spreadsheet software [citation:5]. |
| **[o-spreadsheet (Odoo)](https://github.com/odoo/o-spreadsheet)** | [![Stars](https://img.shields.io/github/stars/odoo/o-spreadsheet?style=social&color=white)](https://github.com/odoo/o-spreadsheet/stargazers) | Standalone spreadsheet for the web, easily integrable and extendable. Real-time collaboration, Excel import/export, and all basic spreadsheet features. Built by Odoo for embedding in business applications . |
| **[Casual Sheets](https://github.com/casualoffice/sheets)** | [![Stars](https://img.shields.io/github/stars/casualoffice/sheets?style=social&color=white)](https://github.com/casualoffice/sheets/stargazers) | Self-hosted collaborative spreadsheet (Apache-2.0) built on Univer OSS. Password-gated co-editing rooms, view-only enforcement at engine layer, Docker deployment with Redis persistence, and WOPI mode support [citation:7][citation:14]. |
| **[Alephgrid](https://github.com/alephgrid/alephgrid)** | [![Stars](https://img.shields.io/github/stars/alephgrid/alephgrid?style=social&color=white)](https://github.com/alephgrid/alephgrid/stargazers) | Self-hosted spreadsheet for billions of rows with SQL and Excel-style formulas. Built on DuckDB; supports XLSX import/export, real-time collaboration, teams with roles, and MCP agent connections. Docker deployment available [citation:3][citation:8]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[GridCraft](https://github.com/storytold/gridcraft)** | [![Stars](https://img.shields.io/github/stars/storytold/gridcraft?style=social&color=white)](https://github.com/storytold/gridcraft/stargazers) | Open-source, clean-room reimplementation of Microsoft Excel in pure Rust. Covers 513 standard worksheet functions (parity inventory); XLSX, XLSB, and ODS import. Alpha stage (~50% ready for real work per project estimate) [citation:4]. |
| **[Nextcloud Spreadsheet](https://github.com/nextcloud/richdocuments)** | [![Stars](https://img.shields.io/github/stars/nextcloud/richdocuments?style=social&color=white)](https://github.com/nextcloud/richdocuments/stargazers) | Collaborative spreadsheet editor within Nextcloud Office. Opens and saves XLSX and ODS, real-time co-editing, version history, granular access controls, and federation support. Self-hosted on your own infrastructure [citation:11]. |
| **[Grist](https://github.com/gristlabs/grist-core)** | [![Stars](https://img.shields.io/github/stars/gristlabs/grist-core?style=social&color=white)](https://github.com/gristlabs/grist-core/stargazers) | Open-source spreadsheet-database hybrid with Python formulas, real-time collaboration, and cell-level security. Self-hostable or cloud; Apache-2.0 [citation:9][citation:12]. |

**Frameworks for building custom systems**: Combine **LibreOffice Calc** for offline heavy lifting, **o-spreadsheet** or **Casual Sheets** for embeddable web spreadsheet components, **Alephgrid** for billion-row analytics, and **Nextcloud Spreadsheet** for a full self-hosted collaboration suite—deployable via Docker Compose without per-seat SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud spreadsheets store potentially sensitive business and financial data; review data processing terms and access controls before uploading confidential information.
- Open-source spreadsheet engines vary significantly in XLSX fidelity; complex macros, charts, and external links may not round-trip cleanly. Validate against your actual files before migrating critical workflows [citation:5].

---

**Made for data analysts, finance teams, operations managers, and developers building spreadsheet workflows.**  
Let's make cloud spreadsheets more open, sovereign, and collaborative.

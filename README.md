# Ghostboard

**Dashboards that leave no trace.**

Ghostboard turns any CSV, Excel, or JSON file into a live, interactive business
dashboard — entirely in your browser. No file is ever uploaded to a server,
logged, or stored. Close the tab and it's gone.

Built for teams and companies that want fast, professional data insight
without the compliance risk of sending sensitive data to a third-party AI
or analytics tool.

## Features
- **Zero-upload architecture** — parsing, analysis, and rendering all run
  client-side; your data never leaves the tab
- **Auto-generated KPIs** — detects sales, profit, cost, and margin columns
  and surfaces total sales, profit, margin %, and period-over-period trend
- **Multi-slicer filtering** — filter across every categorical column at once,
  like a real BI tool
- **Pivot tables** — cross-tabulate any two fields with sum / average / count /
  min / max aggregation
- **Trend + forecast charts** — line charts with a linear-regression-based
  forecast projected forward
- **Pie, bar, and distribution charts** — auto-selected based on your data's
  shape and detected business fields
- **Editable dashboard title** — rename inline before exporting or sharing
- **Exports** — download a real `.xlsx` with computed summary stats/pivots,
  or a presentation-ready PNG snapshot

## Tech stack
Vanilla HTML/CSS/JS · PapaParse (CSV) · SheetJS (Excel) · Chart.js ·
html2canvas — no backend, no build step, no dependencies to install.

## Usage
Open `index.html` in any browser, or host it as a static file. Drop in a
spreadsheet and the dashboard builds itself.

---
Built by Harnoor Kaur Gulati

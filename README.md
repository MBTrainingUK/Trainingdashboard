# Technical Training Dashboard

An interactive report for Mercedes-Benz UK Technical Training. It reads the Technical Training Schedule Excel workbook and turns it into charts and tables showing trainer days against target, other activities, room utilisation and course fill.

**Open it here: https://mbtraininguk.github.io/Trainingdashboard/**

Everything runs in your browser. No data is uploaded anywhere, and there's nothing to install.

## How to use it

1. Open the link above in Chrome, Edge or Firefox.
2. Drag the current **Technical Training Schedule** Excel file (`.xlsx`) onto the drop zone, or click to browse for it.
3. The dashboard builds in a second or two.
4. To see the latest figures, save the workbook and load it again with **Load different file**.

## What's in it

| Tab | What it shows |
|---|---|
| **Dashboard** | Trainer overview cards, monthly and cumulative trainer days against the 12.5 days per month target, a monthly summary table and an Other Activities breakdown. Switch between YTD and Full Year |
| **Room Utilisation** | Room KPIs against the 66% target, a 52-week booking heatmap, booked vs available days, monthly utilisation % by room and booking detail |
| **Course Fill** | Drop in one or more Course Fill / Performance Report `.xlsx` files to see fill rates. Drop several years at once to compare them side by side |

Use the **User Manual** button in the dashboard for a full explanation of every figure and chart.

## Sheets it reads from the workbook

- `Dashboard (2026)`: required
- `Room Utilisation (2026)`: required
- `Trainer Utilisation (2026)`: YTD activities and annual leave
- `Schedule 2026`: weekly room heatmap, unique courses, Trainer Duties, Second Trainer and TW5

The sheet names must match exactly. If either required sheet is missing or renamed, the dashboard won't load. If one of the others is missing, the parts that depend on it will be empty.

## Files

| File | What it is |
|---|---|
| `index.html` | The live dashboard (v3), the page GitHub Pages opens |
| `Report Guide.html` | The user guide |
| `index.html.old` | Previous version (v2), kept for reference |
| `index-archive-before-v2.html` | Older archived version |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

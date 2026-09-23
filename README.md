# AMS Analysis

Interactive neon dashboard for comparing AMS data across **2024, 2025, and 2026**.

## Features

- Excel / XLS / CSV upload directly in the browser
- Filters for Molecule, Product Name, SKU, Region, and Major Doc Spec
- Year checkboxes for 2024 / 2025 / 2026
- Dynamic numeric metric selector
- KPI totals and year-over-year growth / decline
- Year comparison chart
- Regional distribution chart
- Product-level growth / decline table
- Filtered data preview
- Dark neon responsive UI
- No backend: uploaded files stay in the user's browser

## Expected data

The first worksheet should contain columns equivalent to:

- Molecule
- Product Name
- SKU
- Region
- Major Doc Spec
- Year
- One or more numeric metrics (for example Sales, Units, Value, Rx, etc.)

Column names are auto-detected for common variants. Once the production Excel file is available, the mappings can be made exact.

## GitHub Pages

This repository is intentionally a static site. Enable GitHub Pages from the repository settings and serve from the root of the `main` branch.

# AMS Analysis

Neon-style interactive dashboard for the AMS dataset, comparing **2024, 2025, and 2026**.

## Production data structure

The dashboard is mapped to the supplied AMS file containing **136,035 rows** and these columns:

- Molecule
- Product Name
- SKU
- Region
- Major Doc Spec
- 2024
- 2025
- GR% vs 2024
- 2026
- GR% vs 2025
- 2025 Market Share %
- 2026 Market Share %
- 2025 Rank
- 2026 Rank

## Features

- Excel / XLS / CSV upload in the browser
- Filters for Molecule, Product Name, SKU, Region, and Major Doc Spec
- Year checkboxes for 2024 / 2025 / 2026
- Total AMS KPI by year
- Dynamic growth and decline percentages after filtering
- Year comparison chart
- Regional distribution chart for the latest selected year
- Product-level growth / decline ranking
- Filtered raw-data preview including market share and rank
- Responsive dark neon interface
- No backend and no dataset committed to the public repository; uploaded data stays in the browser

## GitHub Pages

Serve `index.html` from the root of the `main` branch using GitHub Pages.

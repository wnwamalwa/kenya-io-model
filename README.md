# Kenya Input-Output Model for Sectoral Analysis

A prototype Leontief input-output model for Kenya's economy, constructed with official
production accounts data from the **KNBS Economic Survey 2025**.

[![GitHub Pages](https://img.shields.io/badge/View%20Report-GitHub%20Pages-blue)](https://wnwamalwa.github.io/kenya-io-model/)

## Overview

The model estimates inter-sectoral production linkages across eight aggregated sectors of the
Kenyan economy using a demand-driven input-output framework. It provides a quantitative basis
for assessing sectoral spillovers from fiscal stimulus and structural transformation strategies.

## Analytical Scope

- **Inter-sectoral linkages** — technical coefficients and Leontief inverse estimation
- **Output multipliers** — total economy-wide output per unit increase in sectoral final demand
- **Backward and forward linkages** — Rasmussen–Hirschman classification of key sectors
- **Demand shock simulation** — spillover effects of a 10% Manufacturing expansion
- **Policy-relevant insights** — implications for industrial strategy, agro-industrial linkages,
  and infrastructure investment

## Key Findings

- Manufacturing exhibits the highest intermediate consumption ratio (0.68), confirming deep
  inter-industry linkages and its potential as a driver of aggregate output growth.
- A 10% positive demand shock in Manufacturing generates measurable spillover effects across
  all sectors, with Agriculture and Transport capturing the largest indirect impacts.
- Agriculture remains the dominant GDP contributor (22.5% in 2024) and plays a critical
  upstream supply role in the production system.

## Data Source

Kenya National Bureau of Statistics (2025). *Economic Survey 2025*. Nairobi, Kenya.
Tables 2.1, 2.4, 2.6. ISBN: 978-9966-102-49-2.

## Usage

```r
# Open in RStudio and knit
rmarkdown::render("kenya_io_model.Rmd")
```

**Requirements:** `ggplot2`, `reshape2`

## Repository Structure

```
kenya-io-model/
├── kenya_io_model.Rmd    # Source R Markdown
├── docs/
│   └── index.html        # Rendered report (GitHub Pages)
├── README.md
├── .gitignore
└── IO_model.Rproj
```

## References

- Leontief, W. (1936). *Review of Economics and Statistics*, 18(3), 105–125.
- Miller, R. E. & Blair, P. D. (2009). *Input-Output Analysis*. Cambridge University Press.
- Rasmussen, P. N. (1956). *Studies in Inter-Sectoral Relations*. Copenhagen.

## Author

**Noah W. Wasike** — Econometrician

## License

This work is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

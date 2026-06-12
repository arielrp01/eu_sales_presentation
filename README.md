# EU Sales Presentation

An end-to-end interactive data presentation built in R, analyzing EU sales data across five dimensions: geographic market performance, year-over-year trends, category revenue, profitability, and customer growth. Built with live data ingestion, interactive maps, and Plotly charts and deployed as a self-contained HTML deck. 

---

## Data 

[EU Superstore dataset](https://public.tableau.com/app/sample-data/sample_-_superstore.xls) via Tableau

This presentation accesses the data via a public Google Sheet for live data ingestion. The dataset covers European regional sales transactions including order date, country, product sub-category, sales, and profit. All metrics are calculated dynamically from the source data at render time.

---

## Requirements
- R 4.0+
- RStudio (recommended)
- The following R packages (auto-installed on first run):
  `tidyverse`, `lubridate`, `janitor`, `googlesheets4`, `plotly`, `scales`, `leaflet`, `sf`, `rnaturalearth`, `rnaturalearthdata`, `htmltools`

---

## Built With
- [R](https://www.r-project.org/) 
- [R Markdown](https://rmarkdown.rstudio.com/)
- [ioslides](https://rmarkdown.rstudio.com/ioslides_presentation_format.html)
- [googlesheets4](https://googlesheets4.tidyverse.org/) 
- [tidyverse](https://www.tidyverse.org/) 
- [plotly for R](https://plotly.com/r/)
- [leaflet for R](https://rstudio.github.io/leaflet/) 
- [rnaturalearth](https://docs.ropensci.org/rnaturalearth/) 
- [sf](https://r-spatial.github.io/sf/) 
- [scales](https://scales.r-lib.org/) 
- [EU Superstore dataset](https://public.tableau.com/app/sample-data/sample_-_superstore.xls) via Tableau

# EU Sales Presentation

An end-to-end interactive presentation analyzing EU sales data.

- Built on a live data pipeline from Google Sheets, with interactive Leaflet maps and Plotly charts.
- Deployed as a self-contained HTML deck on GitHub Pages.
- All metrics are calculated dynamically from the source data at render time.

This type of interactive sales analysis is a standard business deliverable, commonly produced in Python or BI tools like Tableau. Built in R as part of [JHU's Developing Data Products course](https://www.coursera.org/learn/data-products), it demonstrates the same workflow: live data pipeline, interactive visualization, and a self-contained deployed output.

---

## Data 

[EU Superstore dataset](https://public.tableau.com/app/sample-data/sample_-_superstore.xls)

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
- [EU Superstore dataset](https://public.tableau.com/app/sample-data/sample_-_superstore.xls) 

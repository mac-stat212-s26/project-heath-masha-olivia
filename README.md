# U.S. Health Insurance Coverage Report

This repository contains a data story project exploring health insurance coverage patterns in the United States, with a focus on uninsured rates and the impact of recent Medicaid cuts.
Using national and state-level datasets, the project examines how different types of insurance coverage relate to each other, how Medicaid participation has changed over time, and which states have been most affected by recent enrollment declines.

The final project includes:
- An interactive Quarto report
- Multiple data visualizations and maps
- A presentation video
- Presentation slides

---


# Software Requirements

The project was built using:

- R version 4.4.1
- RStudio version 2024.4.2.764
- Quarto

Main R packages used include:

```r
ggplot2
dplyr
tidyr
readr
stringr
forcats
scales
ggrepel
patchwork
tibble
janitor
plotly
tidyverse
sf
leaflet
```
---

# How to Run the Project

1. Clone or download this repository

2. Open the `.Rproj` file in RStudio

3. Install required packages if needed

```r
install.packages(c(
  "ggplot2", "dplyr", "tidyr", "readr", "stringr",
  "forcats", "scales", "ggrepel", "patchwork",
  "tibble", "janitor", "plotly", "tidyverse",
  "sf", "leaflet"
))

```
5. Open `index.qmd`

6. Click **Render** in RStudio to generate the final report

---

# Expected Output

The final rendered report includes:

- National health insurance coverage visualizations
- Interactive uninsured-rate maps
- Correlation heatmaps
- Medicaid participation trend analysis
- State-level Medicaid cut analysis
- Embedded presentation video and slides

Example outputs include:
- U.S. coverage distribution charts
- Interactive state uninsured maps
- Medicaid enrollment trend visualizations
- State-level Medicaid participation decline maps

---

# Project Files

- `index.qmd` — Final Quarto report
- `Project.mp4` — Presentation video
- `Slides.pdf` — Presentation slides

---

# Authors

- Jack F
- Olivia
- Masha

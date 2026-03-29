# SPRING2026TIDYVERSE

This repository contains examples of data analysis and visualization using TidyVerse packages in R, created as part of the SPRING 2026 course assignments.

## UFO Sightings Analysis

### Dataset
The UFO sightings dataset is publicly available and included in this repository:

- **File:** `UFO sighting.csv`  
- **Source:** Kaggle / publicly shared dataset  
- **Description:** Contains observations of UFO sightings worldwide, including date/time, city, state, country, reported shape, duration, and comments.

### Vignette
A full example vignette demonstrating TidyVerse capabilities is included:

- **File:** `TidyVerse CREATE assignment.qmd`  
- **Objective:** Clean, summarize, and visualize UFO sightings by country, year, and reported shapes to uncover trends and patterns.  
- **Packages Used:**  
  - `dplyr` – Data manipulation (filtering, summarizing, grouping)  
  - `tidyr` – Data tidying (handling missing values, cleaning data)  
  - `ggplot2` – Data visualization (bar plots, line plots, multi-color charts)  

### Highlights
- Rows with missing or `"NULL"` values were cleaned or replaced with `"Unavailable"` for accurate summaries.  
- Sightings are analyzed by **country**, **year**, and **UFO shape**.  
- Visualizations include:
  - Top 10 countries by UFO sightings  
  - Top 10 reported UFO shapes with multi-color bar charts  

### How to Run
1. Install TidyVerse package if not already installed:

```r
install.packages("tidyverse")

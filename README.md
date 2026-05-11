# intermediate-elective

## General information

This repository contains data, code, and visualizations for the Intermediate Elective assignment for Spring 2026. The project explores long-term bird abundance trends at NCOS (North Campus Open Space) between 2017 and 2025 using a visualization inspired by Steven Ponce’s “Coal falls. Renewables rise.”

To work with the code in this repository, you will need the following packages:

```r
library(tidyverse)
library(janitor)
library(here)
library(lubridate)
library(ggtext)

## Data and file information

```text
.
├── README.md
├── code
│   ├── Cutner-Nina_Intermediate-elective-01.pdf
│   └── Cutner-Nina_Intermediate-elective-01.qmd
├── data
│   └── birds copy.csv
├── figures
│   ├── bird-abundance-trends.png
│   └── sketch.jpg
└── intermediate-elective.Rproj

### Data descriptions

- `birds copy.csv` contains NCOS bird monitoring observations used to calculate yearly bird abundance trends from 2017–2025.
- `bird-abundance-trends.png` contains the final rendered visualization created for the assignment.
- `sketch.jpg` contains the initial visualization planning sketch.

## Rendered output

The rendered assignment for the code in this repository can be viewed [here](code/Cutner-Nina_Intermediate-elective-01.pdf).

## Final visualization

![](figures/bird-abundance-trends.png)
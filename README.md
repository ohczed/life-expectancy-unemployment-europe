# Life Expectancy and Unemployment in Europe: A Data Science Analysis

## Overview
This project explores the relationship between life expectancy and unemployment in 27 EU countries between 2003 and 2021.

The analysis uses two independent public data sources and combines them into one merged dataset for statistical analysis and visualization.

## Research Question
Is there a relationship between unemployment rate and life expectancy in EU countries between 2003 and 2021?

## Data Sources
- **WHO** – Life expectancy at birth
- **Eurostat** – Annual unemployment rate

## Methodology
The project follows these main steps:
1. Load the WHO and Eurostat datasets
2. Clean each dataset and keep only the relevant observations
3. Match countries and merge the datasets by country and year
4. Analyze the merged data using descriptive statistics, histograms, scatter plots, trend lines, and correlation

## Main Variables
- `life_expectancy`
- `unemployment_rate`
- `year`
- `country`
- `geo_code`

## Main Findings
- Life expectancy is generally high across the dataset
- Unemployment varies more strongly across countries and years
- The overall linear relationship between unemployment and life expectancy is very weak

## Project Structure
```text
life-expectancy-unemployment-europe/
├── data/
│   └── raw/
├── notebooks/
│   └── final_project.ipynb
├── README.md
├── requirements.txt
└── .gitignore

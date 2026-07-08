# Pixar Films Exploratory Data Analysis in R

## Project Overview

This project analyzes Pixar films using R. I explored whether Pixar movies changed over time in runtime, film rating, and critic response. The analysis uses Pixar film metadata and public response scores, including Rotten Tomatoes, Metacritic, CinemaScore, and Critics Choice.

This project was completed for Applied Economics & Data Analysis in R and received a 99/100.

## Tools Used

- R
- tidyverse
- ggplot2
- lubridate
- Quarto

## Research Questions

1. Do Pixar films with more mature ratings tend to be longer or reviewed differently?
2. Has Pixar’s movie formula changed over time in terms of runtime and ratings?
3. Are critic scores consistent across platforms?

## Data

The analysis uses two datasets:

- `pixar_films.csv`
- `public_response.csv`

These datasets include Pixar film information such as release date, runtime, film rating, and public review scores.

## Key Steps

- Loaded and inspected the datasets
- Checked rows, columns, variable types, and missing values
- Joined the film metadata with public response scores
- Created `release_year`
- Created `average_critic_score`
- Built visualizations to compare runtime, film rating, release order, and critic scores

## Main Findings

- G-rated and PG-rated Pixar films had very similar average runtimes.
- G-rated and PG-rated films also had similar average critic scores.
- Pixar runtimes became more variable across later releases.
- Rotten Tomatoes scores were generally high, but later films showed more uneven review performance.
- Rotten Tomatoes and Metacritic were related, but they did not always agree. Rotten Tomatoes scores were usually higher than Metacritic scores.

## How to Run

1. Clone this repository.
2. Open `pixar_eda.qmd` in RStudio.
3. Install the required packages if needed.
4. Render the Quarto file to reproduce the report.

```r
install.packages(c("tidyverse", "lubridate"))

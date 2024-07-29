# Rams Offense & Defense Analytics
https://github.com/lqiu03/LARAMS-Performance-analytics/raw/main/download.png

This repository contains various analyses and visualizations of the LA Rams' defensive performance for the 2023 NFL season. The play-by-play data is sourced from the NFLfastR package.

## Project Structure

The project is organized into the following directories and files:

- `defense/`: Contains scripts related to defensive metrics and analyses.
- `offense/`: Contains scripts related to offensive metrics and analyses.
- Other general scripts related to offensive and defensive analyses are in the root directory.

## Getting Started

Since nflfastR is an open-source data source, feel free to take my codes as inspirations. You need to download R Studio to work on this project:

### Prerequisites

- R (version 4.0 or higher)
- The following R packages:
  - `nflfastR`
  - `dplyr`
  - `ggplot2`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/lqiu03/rams-defense-analytics.git
    cd rams-defense-analytics
    ```

2. Install the required R packages:
    ```R
    install.packages(c("nflfastR", "dplyr", "ggplot2"))
    ```

## Usage

Run the scripts in the `defense/` directory to generate various defensive metrics and visualizations. For example, to analyze the run stop percentage, run the `run-stop-percentage-by-rams-defense` script:

```R
source("defense/run-stop-percentage-by-rams-defense.R")

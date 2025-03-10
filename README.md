# Money Heist (La Casa de Papel) Episode Analysis

## Overview

This project analyzes episode-specific data from the Money Heist (La Casa de Papel) web series.  The analysis focuses on episode ratings and other characteristics obtained from a CSV file.  The goal is to explore the data and identify potential trends or patterns.

## Data

The data is stored in the `MoneyHeist.csv` file.  The CSV contains the following columns:

*   **Date:** Release date of the episode.
*   **Season:** Season number.
*   **Episode:** Episode number within the season.
*   **Title:** Episode title (original language).
*   **Title(English):** Episode title (English translation).
*   **Description:** Episode description/summary.
*   **Rate:** Episode rating (likely from IMDb).
*   **RateNumber:** Number of ratings for the episode.

## Project Structure

*   `KNN.ipynb`: Jupyter Notebook containing the data analysis.
*   `MoneyHeist.csv`: The dataset used for analysis.

## Dependencies

The project uses the following Python libraries:

*   pandas
*   matplotlib
*   seaborn

You can install these using `pip`:


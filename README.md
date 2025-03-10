# 💰 Money Heist Webseries Analysis using Machine Learning 📊

## Overview 🎬

This project analyzes the Money Heist (La Casa de Papel) web series using machine learning techniques. The analysis focuses on episode data, including ratings, descriptions, and other relevant information. The goal is to gain insights into the series' popularity, trends, and characteristics.

## Data 🗂️

The data is stored in the `MoneyHeist.csv` file and includes information about each episode. The key columns are:

*   **Date:** 📅 Release date of the episode.
*   **Season:** 🔢 Season number.
*   **Episode:** 🔢 Episode number within the season.
*   **Title:** 💬 Episode title (original language).
*   **Title(English):** 💬 Episode title (English translation).
*   **Description:** 📝 Episode description/summary.
*   **Rate:** ⭐ Episode rating (likely from IMDb).
*   **RateNumber:** 🗳️ Number of ratings for the episode.

## Project Structure 📂

*   `KNN.ipynb`: 📓 Jupyter Notebook containing the data analysis and machine learning code.
*   `MoneyHeist.csv`: 💾 The dataset used for analysis.

## Dependencies ⚙️

The project uses the following Python libraries:

*   pandas
*   matplotlib
*   seaborn
*   scikit-learn (you might need to install this if you plan to use machine learning models)

You can install these using `pip`:


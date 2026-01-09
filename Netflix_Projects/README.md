# Netflix Movies Analysis

This project analyzes a dataset of Netflix movies to investigate the claim that the average duration of movies has been declining over the years.

## Project Overview

A friend has noticed a trend of declining movie durations on Netflix and has provided the following data for the years 2011 to 2020: the average movie durations are 103, 101, 99, 100, 100, 95, 95, 96, 93, and 90 minutes, respectively.

This project aims to:
1.  Verify this trend by performing a more rigorous analysis of a larger Netflix dataset.
2.  Practice data manipulation and visualization skills using `pandas` and `matplotlib`/`seaborn`.

## The Notebook

The `Netflix_movies.ipynb` notebook contains the step-by-step analysis. The process includes:
- Creating an initial pandas DataFrame from the friend's data.
- Loading a more comprehensive Netflix dataset from a CSV file.
- Cleaning and preprocessing the data (e.g., filtering for movies, handling missing values).
- Grouping the data by year and calculating the average movie duration for each year.
- Visualizing the trend of movie durations over time to confirm or deny the initial hypothesis.

## Dataset

The project uses a CSV file containing Netflix data, which is expected to be in the `Datasets` subdirectory.

## Dependencies
- `pandas`
- `matplotlib` and/or `seaborn` (for visualization)

You can install these dependencies using pip:
```bash
pip install pandas matplotlib seaborn
```

## Usage
1. Make sure you have the required dataset in the `Datasets` folder.
2. Open and run the `Netflix_movies.ipynb` notebook in a Jupyter environment to see the analysis.

# Airbnb Data Analysis

## Overview

This project focuses on data cleaning and exploratory data analysis of an Airbnb dataset containing approximately 100,000 listings.

The analysis was performed using Python, Pandas, Matplotlib, and Seaborn to clean the dataset, handle missing values, transform data types, and identify useful patterns in Airbnb listings.

## Objectives

- Clean and preprocess the Airbnb dataset
- Identify and handle missing values
- Convert columns to appropriate data types
- Clean price and service fee columns
- Analyze room types and neighbourhood groups
- Analyze listing price distribution
- Analyze review trends over time

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning

The following data cleaning techniques were performed:

- Checked missing values using `isnull().sum()`
- Handled missing values using `fillna()`
- Removed unnecessary columns using `drop()`
- Converted date columns using `pd.to_datetime()`
- Removed `$` and `,` from price-related columns
- Converted numerical columns to appropriate data types
- Removed rows with missing values where required

## Exploratory Data Analysis

The project analyzes:

- Distribution of Airbnb listing prices
- Number of listings by room type
- Number of listings by neighbourhood group
- Price variation across room types
- Number of reviews over time

## Visualizations

The analysis uses Matplotlib and Seaborn to create:

- Histograms
- Count plots
- Box plots
- Line charts

## Dataset

The dataset contains approximately 100,000 Airbnb listings.

The raw dataset is not included in this repository.

## Conclusion

The analysis provides insights into Airbnb listing prices, room-type distribution, neighbourhood activity, and review trends.

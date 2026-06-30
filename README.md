# Film Industry Analytics and Power BI Data Preparation

An end-to-end data analytics project that cleans, transforms, and analyzes movie industry data and prepares a Power BI-ready analytical model.

## Project Overview

This project processes a movie analytics dataset containing financial, rating, release, country, genre, director, and actor information.

The notebook performs:

- Data acquisition from Kaggle
- Data quality auditing
- Data cleaning and validation
- Feature engineering
- Exploratory data analysis
- KPI generation
- Aggregated analytical summaries
- Star schema creation
- Power BI-ready data export

## Dataset

The dataset includes:

- Movie title and ID
- Genre
- Release date and year
- Country
- Budget
- US box office
- Global box office
- Opening-day and first-week sales
- IMDb rating
- Rotten Tomatoes score
- Vote counts
- Director
- Lead actor

## Data Cleaning

The workflow includes:

- Schema validation
- Missing-value analysis
- Duplicate Movie ID removal
- Text normalization
- Date conversion
- Numeric type conversion
- Invalid financial value handling
- Rating-range validation
- Vote-count validation

## Feature Engineering

The project creates:

- International box office
- Profit
- Return on investment
- Profit margin
- Release month
- Release quarter
- Release day of week
- Budget category
- Revenue category
- Profitability flag
- Success tier
- Visualization-friendly clipped values

## Analytics

The notebook analyzes:

- Annual movie performance
- Genre performance
- Country-level revenue
- Budget and revenue relationships
- Rating and box-office correlations
- Monthly release performance
- Director performance
- Lead actor performance
- Top-performing movies
- Profitability and ROI

## Power BI Data Model

The project builds a star schema containing:

### Fact Table

- `FactMovies`

### Dimension Tables

- `DimDate`
- `DimGenre`
- `DimCountry`
- `DimDirector`
- `DimActor`

The notebook also generates relationship definitions and a data dictionary.

## Exported Outputs

The workflow exports:

- Cleaned movie data
- Fact and dimension tables
- CSV files
- Parquet files
- KPI summary
- Annual summary
- Genre summary
- Country summary
- Director and actor summaries
- Top movie rankings
- Data-quality reports
- Data dictionary
- Power BI relationship guide

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- PyArrow
- KaggleHub
- Power BI
- Google Colab

## Project File

Open `Film_Industry_Analytics_PowerBI.ipynb` to view the complete data preparation, analysis, data modeling, and export workflow.

## Author

Loay Waleed

# Bank Reviews Scraper

## Overview
This project scrapes reviews from the Google Play Store for three banking apps: CBE, BOA, and Dashen. The goal is to collect and preprocess the reviews for analysis.

## Methodology

1. **Data Collection**:
   - Utilized the `google-play-scraper` library to collect 400 reviews from each bank's app, totaling 1,200 reviews.

2. **Preprocessing**:
   - Removed duplicate reviews.
   - Handled missing data by dropping rows with null values.
   - Normalized the review dates to the format YYYY-MM-DD.

3. **Output**:
   - The cleaned dataset is saved as `bank_reviews.csv`.

## KPIs
- **1,200+ reviews collected** with less than 5% missing data.
- Clean CSV dataset.
- Organized Git repository with clear commits.

## Requirements
- Python 3.x
- Pandas
- google-play-scraper
- textblob
- cx_Oracle
# COVID-19 State-wise Data Analysis using Python

## Overview

This project analyzes COVID-19 data in India to understand how confirmed cases, active cases, recoveries, and deaths vary across different states.

## Dataset

* File included in this repository: `covid_19_india.csv`
* Contains ~18,000+ rows of state-wise COVID-19 data
* Includes confirmed, cured, and death cases

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

## What I Did

* Cleaned the dataset by removing unnecessary columns
* Fixed inconsistent state names (spelling errors and special characters)
* Converted the Date column into datetime format
* Created a new column: **Active Cases = Confirmed - (Deaths + Cured)**
* Performed state-wise analysis using pivot tables
* Calculated recovery rate and mortality rate
* Visualized top states based on active cases and deaths

## Results

* Maharashtra, Karnataka, and Kerala had the highest number of active cases
* Most states showed high recovery rates
* Mortality rates varied across states

## How to Run

1. Download or clone this repository
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn
3. Open and run `covid_analysis.ipynb`

## Conclusion

This project demonstrates data cleaning, feature engineering, and visualization using real-world COVID-19 data.

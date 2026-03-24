# COVID-19 State-wise Data Analysis using Python

##  Overview

This project analyzes COVID-19 data for India to examine state-wise trends in confirmed cases, active cases, recoveries, and deaths.

##  Dataset

* COVID-19 India dataset (~18,000+ rows)
* Includes state-wise data for confirmed, cured, and death cases

##  Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

##  Key Steps

* Cleaned dataset by removing irrelevant columns and correcting inconsistent state names
* Converted the Date column into datetime format
* Created a new feature: **Active Cases = Confirmed - (Deaths + Cured)**
* Performed state-wise aggregation using pivot tables
* Calculated **Recovery Rate** and **Mortality Rate**
* Visualized top states based on active cases and deaths

##  Results

* Identified states with the highest COVID-19 cases and deaths
* Compared recovery and mortality rates across states

##  Conclusion

This project demonstrates data cleaning, feature engineering, aggregation, and visualization using real-world COVID-19 data.

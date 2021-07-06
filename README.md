# Chicago Ridership - Daily L Station Entries

## About Me

I am Emre Okcular, a data science intern at [Dictionary.com](https://www.dictionary.com/) Currently pursuing [Master of Science in Data Science](https://www.usfca.edu/arts-sciences/graduate-programs/data-science) at University of San Francisco.

## Project Goal

The main project of this project is to understand what are the characteristics of the data and to reveal key findings. In addition, various regressor and time series models were built for forecasting the daily rides for the transportation department to improve service in the next few years.

## Dataset

Dataset is downloaded from https://data.cityofchicago.org/Transportation/CTA-Ridership-L-Station-Entries-Daily-Totals/5neh-572f.

## Files

* ```CTA_-_Ridership_-__L__Station_Entries_-_Daily_Totals.csv``` : Raw Dataset
* ```chicago-train.ipynb``` : Main notebook
* ```l_map.png``` : L Train Map
* ```population_density.png``` : Chicago Population Density Map
* ```ridershipreadme.txt``` : Readme file for the dataset

## Notebook

To run the notebook in your local, you should run below command and install all required packages from requirement.txt which is located in the same folder.

```pip install -r requirements.txt```

**https://github.com/emreokcular/chicago-trains/blob/main/chicago-train.ipynb**

## Summary

In this project, Chicago L Train Ridership data is analyzed. The dataset from 2001 to 2021 loaded and explored to extract characteristics and key findings. Lessons learned from data can be found in the notebook. Different type of forescasting models were built for the transportation department to improve service by forecasting the daily rides in the next few years. The final model were selected by evaluating model performance and considering production usage.
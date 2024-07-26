# Site Energy Usage Intensity Prediction

This project aims to predict the Site EUI for each row, given the characteristics of the building and the weather data for the location of the building.

## Dataset

The WiDS Datathon 2022 focuses on a prediction task involving roughly 100k observations of building energy usage records collected over 7 years and 
a number of states within the United States. The dataset consists of building characteristics (e.g. floor area, facility type etc), weather data 
for the location of the building (e.g. annual average temperature, annual total precipitation etc) as well as the energy usage for the building and 
the given year, measured as Site Energy Usage Intensity (Site EUI). Each row in the data corresponds to the a single building observed in a given year. 
Your task is to predict the Site EUI for each row, given the characteristics of the building and the weather data for the location of the building.


## Problem Statement

You are provided with two datasets: (1) the train_dataset where the observed values of the Site EUI for each row are provided and (2) the x_test dataset the observed values of the Site EUI for each row are removed and provided separately in y_test. Your task is to predict the Site EUI for each row (using the complete training dataset), given the characteristics of the building and the weather data for the location of the building. Use the test sets for validation and testing. 
The target variable is **site_eui** and the evaluation metric is **RMSE** score.


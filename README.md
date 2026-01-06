# msc-cs-study
Codes & report for Applied AI 

Language: Python

Executive summary

This study examines the relationship between child mortality and breastfeeding rates using a dataset of yearly records from various countries. Time series analysis was employed to identify temporal patterns and predict these relationships.

A Genetic Algorithm (GA) was utilized to align differing year ranges across countries, optimising data completeness by effectively navigating complex, nonlinear search spaces and outperforming methods like simulated annealing and hill climbing. The GA identified an optimal year range of 1952-2021, achieving a high fitness score of 83,015.

To model the relationship between child mortality and breastfeeding rates, a Long Short-Term Memory (LSTM) neural network was used, selected for its ability to capture long-term dependencies in time series data. The analysis revealed that historical mortality rates are essential for predicting under-five mortality and that there is a significant correlation between breastfeeding rates and child mortality, as indicated by SHAPley values. However, the limited dataset, which only included breastfeeding and historical mortality data, restricted predictive accuracy. The LSTM model achieved a Root Mean Square Error (RMSE) of 4.937, highlighting the need for additional features to enhance accuracy.

Future research should expand the dataset by incorporating variables such as maternal health, economic status, and healthcare access to gain a more comprehensive understanding of child mortality determinants. Enhanced data collection strategies and a broader set of features are necessary to overcome current limitations and improve predictive performance.


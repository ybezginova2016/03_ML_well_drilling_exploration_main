# ML_well_drilling_exploration_main

# Mining Industry: How to Choose the Best Location to Drill a New Well?  

## Project Description
The client company: GlavRosGosNeft. We need to decide where to drill a new well.  Data of oil samples in three regions is provided: in each of 10,000 fields, where the quality of oil and the volume of its reserves have been measured. The company investigates 500 dwells, amonth those 200 best dwells are to be chosen. The budget for each dwell research is 10 bln RUB. The price for a 1 barrel is 450 RUB (profit). The profit for each piece of product is 450k RUB (1 piece of product is 1000 barrels). After the risk level calculatinos, only regions with a negative profit probability is less than 2.5$ should be chosen.

## Data
Data of oil samples in three regions is provided: in each of 10,000 fields, where the quality of oil and the volume of its reserves have been measured. Test data is given seprately.

## Project objectives

1 - Build a machine learning model to help determine the region where mining will bring the most profit.   
2 - Analyze possible profits and risks using the *Bootstrap.* technique

## Project Methodology
- 75/25 split to training and valiadation data
- For training Linear Regression fits; other ML algorithms are not predictable enough.
- Calculating MSE, RMSE for validation data to choose the best model
- Analyze possible profits and risks using Bootstrap technique

## Project Output
In the 2nd region, the probability of losses is 2.4% and is less than acceptable, the region meets the criteria of the task. The 2nd field is recommended for development within the proposed budget and conditions.

## Key Python Libraries:
- numpy, seaborn, pandas, matplotlib
- sklearn.model_selection
- sklearn.linear_mode
- sklearn.metrics

### Project Code: https://github.com/ybezginova2016/03_ML_well_drilling_exploration_main/blob/main/03_ML_well_drilling_exploration_main.ipynb

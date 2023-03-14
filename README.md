# Bike_Sharing_Assignment
## Background
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.

## Objective
The company wants to know:

- Which variables are significant in predicting the demand for shared bikes. 
- How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Business Goal
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Dataset
- Datafile - "day.csv"
- Datadictionary - "Readme.txt"

## Technologies Used
- Jupyter Notebook
- Python
- Libraries
	import numpy as np
	import pandas as pd
	import matplotlib.pyplot as plt
	import seaborn as sns
	import scipy.stats as stats
	import sweetviz as sv
	import statsmodels.api as sm

	from sklearn.model_selection import train_test_split
	from sklearn.preprocessing import MinMaxScaler
	from sklearn.feature_selection import RFE
	from sklearn.linear_model import LinearRegression
	from statsmodels.stats.outliers_influence import variance_inflation_factor
	from sklearn.metrics import r2_score


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- References 
    - https://campus.datacamp.com
    - https//geekofgeeks.com
    - https://www.wikipedia.org/
   
- This project was based on combination of the reading from various programmer friendly sites and manuals / help guide.


## Contact
Created by [@ShashankPawas] - feel free to contact me!

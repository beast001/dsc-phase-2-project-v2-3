# Phase 2 Project Description

# Boma Yangu Housing Agency House Price Prediction Model 
![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-2-project-v2-3/main/halfway-there.gif)

## Overview
This project employes the use of variouse Linear Regression modes to try and predict house prices. Linear Regression is used here due to its ability to perform inference statistic giving us more insight and relationship about the data we are working on. The data used to develop this model is the King County House Sales Dataset which is a CSV file
that contains 21597 rows and 21 columns of data.
Each column in the data set represents an atttribute about a house and the target variable Price which we will develp a model to try to predict.<br>

The other 20 colums of this dataset will therefor be used to try and develop an accurate model to help the managers of Boma Yangu Housing Agency predict the price of a house given certain parameters.<br>
We will start developing the model by using a simple liner regressor and continue to explore by incorporating multile linear regressors to increase accuracy of the base model while also adding and removing other features from the model.

## Data Used
The data used to develop this regression model contains house sale prices for King County, which includes Seattle. It includes homes sold between September 9 2014 and January 1 2015

The data set contains 21597 records and 21 attributes.<br>

We will get a better understanding on the data by investgating the column_names.md file found in the data directory which will give us more idea about the data and the attributes in each column as shown below.

### Column Names and Descriptions for King County Data Set
* `id` - Unique identifier for a house
* `date` - Date house was sold
* `price` - Sale price (prediction target)
* `bedrooms` - Number of bedrooms
* `bathrooms` - Number of bathrooms
* `sqft_living` - Square footage of living space in the home
* `sqft_lot` - Square footage of the lot
* `floors` - Number of floors (levels) in house
* `waterfront` - Whether the house is on a waterfront
  * Includes Duwamish, Elliott Bay, Puget Sound, Lake Union, Ship Canal, Lake Washington, Lake Sammamish, other lake, and river/slough waterfronts
* `view` - Quality of view from house
  * Includes views of Mt. Rainier, Olympics, Cascades, Territorial, Seattle Skyline, Puget Sound, Lake Washington, Lake Sammamish, small lake / river / creek, and other
* `condition` - How good the overall condition of the house is. Related to maintenance of house.
  * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each condition code
* `grade` - Overall grade of the house. Related to the construction and design of the house.
  * See the [King County Assessor Website](https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r) for further explanation of each building grade code
* `sqft_above` - Square footage of house apart from basement
* `sqft_basement` - Square footage of the basement
* `yr_built` - Year when house was built
* `yr_renovated` - Year when house was renovated
* `zipcode` - ZIP Code used by the United States Postal Service
* `lat` - Latitude coordinate
* `long` - Longitude coordinate
* `sqft_living15` - The square footage of interior housing living space for the nearest 15 neighbors
* `sqft_lot15` - The square footage of the land lots of the nearest 15 neighbors

## Problem Statement

he recent burst in real estate bubble in the country has made may real estate agencies run into multiple losses. This has been particulerly worsened by the inability of some real estate agencie to provide a reasonable price of a given housing unit. These problems has lead to the recent undervaluation and sometimes over valuation of houses more than the current market prices.

Boma Yangu Housing Agency therefor needs a model that  will help them predict the true value of a house not by guessing but by making data driven decissions from already available data.
This model should be accute enough to give a price prediction when certain parameters are fed into the model. This will really help the agency avoids losses by investing  in overpriced houses due to the current bubble and make profit by buying and investing in underpriced houses in the current bubblewhic have a potential of selling at high prices after the bubble burst.


## Technology Used
- Python is the base language used in this project
- Jupyter notebooks wer used to write the code and perform analysis


### Libraries
- Pandas 
- Numpy
-Matplotlib.pyplot 
- Matplotlib
- Seaborn
- Sqlite3
- ZipFile


## Expected Results
- The exxpected result from this analysis are
     - Predict house prices given some features 
     - Know which features affect house prices
     - Features with affect house prices most and those that affect house prices the list
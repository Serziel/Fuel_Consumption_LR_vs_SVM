# Fuel_Consumption_LR_vs_SVM
CO2 Emissions prediction comparison between Linear Regression and Support Vector Regression (SVR)

# Dataset
The dataset used is Fuel Consumption 2000-2022 from Kaggle, already included in this repository.
https://www.kaggle.com/datasets/ahmettyilmazz/fuel-consumption/data

# The Data
Here's an explanation of the data included in the dataset.

YEAR: Production Year

MAKE: Constructor

MODEL: car model

VEHICLE CLASS: e.g. SUV, COMPACT

ENGINE SIZE: e.g. 1.6

CYLINDERS: numbers of cylinders

TRANSMISSION: transmission type and number of gears e.g. M5  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; A = Automatic  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; AM = Automated manual  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; AS = Automatic with select shift  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; AV = Continuously variable  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; M = Manual  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  3 - 10 = Number of gears

FUEL: fuel type.  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;X = Regular gasoline  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Z = Premium gasoline  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;D = Diesel  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;E = Ethanol (E85)  
 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;N = Natural Gas

FUEL CONSUMPTION: city fuel consumption

HWY (L/100 km): highway fuel consumption

COMB (L/100 km): combinated fuel consumption (55% city, 45% highway) in liter per km

COMB (mpg): combinated fuel consumption (55% city, 45% highway) in imperial gallon per mile

EMISSIONS: estimated emission in g/km

# Evaluation Metrics
The metrics used to compare the models are Mean Squared Error (MSE) and R-squared (r2-score).
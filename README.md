# Life-Expectancy-Prediction-using-Multiple-Regression
Multiple Regression model for predicting Life Expectancy for various countries

In this dataset we predict Life expectancy of different countries. We will explore how immunization factors, mortality factors, economic factors, social factors and other health related factors affect Life expectancy of a country.  

## Dataset 
There are two data files: "LifeExpectancy_training_modified.csv" and "LifeExpectancy_test_modified.csv"  
Both files have the following fields, except Life_expectancy which is not available in "LifeExpectancy_test_modified.csv"  

### Features :

* Year : from 2002 to 2015
* Status : Developed or Developing status
* Adult_Mortality : Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)
* Alcohol : Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)
* percentage_expenditure : Expenditure on health as a percentage of Gross Domestic Product per capita(%)
* BMI: Average Body Mass Index of entire population
* Total_expenditure: General government expenditure on health as a percentage of total government expenditure (%)
* Diphtheria: Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)
* HIV_AIDS: Deaths per 1000 live births HIV/AIDS (0-4 years)
* GDP: Gross Domestic Product per capita (in USD)
* Population
* Income_composition_of_resources: Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
* Schooling: Number of years of Schooling(years)
* Health_Index: Health index
* Target: Life_expectancy: Life Expectancy in age
  
**Training dataset**, "LifeExpectancy_training_modified.csv", contains 1064 rows and 15 columns. This is the training set containing both of the features and the target.   
**Test dataset**, "LifeExpectancy_test_modified.csv", contains 458 rows and 14 columns. This is the test set which only contains the features.

Our goal is to predict Life expectancy based on the features. 

## Model

Refer this [link](https://github.com/chitransh1998/Life-Expectancy-Prediction-using-Multiple-Regression/blob/main/Life_Expectancy_Prediction.ipynb) for the model and details.

## Final Insights

The histogram of the predicted life_expectancy is a normal distribution similar to that of the training set.  
The average of the distribution is 72 - 76 range, this makes intuitive sense as the range of values are similar to life expectancy of humans - 72.6 years


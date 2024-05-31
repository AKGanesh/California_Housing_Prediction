
![Logo](https://fastly.picsum.photos/id/49/1280/792.jpg?hmac=NnUJy0O9-pXHLmY2loqVs2pJmgw9xzuixgYOk4ALCXU)


# Implementing Linear Regression on California Housing Dataset
This Project covers all the necessary steps to complete the Machine Learning Task of Predicting the Housing Prices on California Housing Dataset available on scikit-learn. 

## Implementation Details

- Dataset: [California housing dataset on sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
- Model: [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
- Input: 8 Features (Median Income, House Age, Average num of Rooms, Average num of Bedrooms, Population, Average num of household members, Latitude, Longitude)
- Output: House Price


## Dataset details
- Number of Instances: 20640

- Number of Attributes: 8 numeric, predictive attributes and the target

- Attribute Information:
    - MedInc        median income in block group
    - HouseAge      median house age in block group
    - AveRooms      average number of rooms per household
    - AveBedrms     average number of bedrooms per household
    - Population    block group population
    - AveOccup      average number of household members
    - Latitude      block group latitude
    - Longitude     block group longitude

- Missing Attribute Values: None

This dataset was obtained from the StatLib repository.
https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html

The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset are provided per household, these columns may take surprisingly large values for block groups with few households and many empty houses, such as vacation resorts.

It can be downloaded/loaded using the function
`sklearn.datasets.fetch_california_housing`

- References
Pace, R. Kelley and Ronald Barry, Sparse Spatial Autoregressions,
Statistics and Probability Letters, 33 (1997) 291-297


## Evaluation and Results


| Metric  | Value  |
| ------------- | ------------- |
| R2 Score  | 0.48  |
| MSE  |  0.68 |



## Libraries

**Language:** Python

**Packages:** Sklearn, Matplotlib


## Roadmap

- To apply other regression algorithms and check the results

- To findout the top features that is affecting the housing price

- To apply various visualization techniques




## FAQ

#### Whats is R2 Score?

An R-Squared value shows how well the model predicts the outcome of the dependent variable. R-Squared values range from 0 to 1. An R-Squared value of 0 means that the model explains or predicts 0% of the relationship between the dependent and independent variables.

#### What is MSE?

Model Evaluation is a crucial aspect in the development of a system model. When the purpose of the model is prediction, a reasonable parameter to validate the model’s quality is the mean squared error of prediction.
The value of the error ranges from zero to infinity. MSE increases exponentially with an increase in error. A good model will have an MSE value closer to zero, indicating a better goodness of fit to the data.

## Acknowledgements

- https://scikit-learn.org/
- https://picsum.photos

## Contact

For any queries, please send an email (id on github profile)


##  License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

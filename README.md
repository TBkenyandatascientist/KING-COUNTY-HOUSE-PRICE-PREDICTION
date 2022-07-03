# KING-COUNTY-HOUSE-PRICE-PREDICTION

Introduction

In the housing market, the understanding of factors that affect house prices is fundamental for construction companies and real estate investors. These investors need to understand what drives house prices up so as to ensure that they invest in the kind of homes that would fetch higher prices and ensure higher returns for their investments. In this analysis, I create a regression analysis model that is focused on the KC area that would predict house prices for homes in the area depending on the most relevant features that affect home prices and therefore provide a confident model for real estate investors and construction companies to determine their potential returns.


## Screenshots

![App Screenshot](https://miro.medium.com/max/630/1*3Psu7nDr2LvhWH4R6-Tqeg.jpeg)


## Authors

- [@viviankingasia](https://github.com/TBkenyandatascientist/)


## Data Understanding
The dataset used in this analysis is the KC housing data set which contains data for 21597 properties in KC and 21 variables.
We perfomed a multiple linear regression and find the relationship between the predictor variables
and the target variable (price). The analysis will help determine which variables impact the price
significantly and hence provide knowledge for real estate investors on what features to invest on in
the real estate market. The first step is to clean the dataset and prepare it for analysis. This will involve tackling the missing
values.
## Conclusions

From the regression analysis conducted, the following observations were made:

The best predictors for home prices in King County are sqft_living, grade and bathrooms.

The model's findings sometimes goes against real world assumptions such as bedrooms and
geographical locations being huge factors in influencing price. In this model findings
real estate investors can use use predictors such as sqft_living to determine price of future investments. 

This model however, cannot be applied in 
different geographical locations due to varying situations and differences across
different regions.

Additionally, although grade and bathrooms show high correlation with price, visualizations of their
count across the dataset showed variations in the bathrooms and grades with 2.5 bathrooms houses being the most sold houses and grade 7 houses being the most sold.




## Recommendations

For real estate investors, if they are looking to make money in the real estate market, you have to invest in homes that will achieve grade 7 in the King County area, meeting grading requirements for the region. This is the optimal grade level to sell more houses in the area.

Secondly, real estate investors have to invest well in the bathrooms with the optimal number of 2.5 to make a lot of returns. This is the optimal number of bedrooms to sell more houses in the area.

Lastly, investors should invest in larger sqft_living space, that is, a higher square footage of the home to ensure that they sell the homes for higher prices. The higher the square foot space, the higher the prices of the homes.
## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

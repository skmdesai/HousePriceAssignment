# House Price Assignment
> House Price Assignment tends to identify variables in predicting the price of a house and understand how well those variabled describe the price of a house


## Table of Contents
* [Problem statement and Goal](#general-information)
* [Overview of Data Analysis Approach](#technologies-used)
* [Summary of Analysis](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market.
- So, Required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- Goal : To build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Dataset: train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Based on the Ridge and Lasso Regression Model analysis, Final model was choosen to be Ridge Regression model because of better R2 Score on test dataset as compared to Lasso Regression model.
- Although Ridge Regression Models covers almost all the features and provides coefficients for all features which are pushed towards 0 , have compared the coeffcients for lasso also and we observe the features pattern w.r.t positive and negative impact on SalePrice is similar in Ridge and Lasso regression model coefficients.
- Top 20 Variables affecting Positively on Price of House are, 'RoofMatl_WdShngl', 'GrLivArea', '1stFlrSF', 'OverallQual','RoofMatl_CompShg', 'LotArea', 'RoofMatl_Tar&Grv', 'RoofMatl_Membran', 'RoofMatl_Metal', 'RoofMatl_WdShake', '2ndFlrSF', 'BsmtFinSF1', 'RoofMatl_Roll', 'Neighborhood_NoRidge', 'OverallCond', 'GarageArea', 'YearBuilt', 'BsmtQual', 'SaleType_Con', 'Neighborhood_NridgHt'
- Top 10 Variables affecting Negatively on Price of House are, 'Functional_Mod', 'Exterior1st_CemntBd', 'PoolArea', 'LotFrontage', 'BedroomAbvGr', 'BsmtCond', 'Heating_OthW', 'MSSubClass', 'Functional_Sev', 'Condition2_PosN'

- Postive Impact on House Price
-  House price is higher if it has Wood Shingles in the Roof > roof material with Standard (Composite) Shingle > Gravel & Tar Roof Material
-  Basically bigger house more price. More space in square feet for above grade living area, 1st Floor, 2nd Floor, Garage Area and lotArea.
-  Best material used and finishing of house fetches higher price - OverallQual, BsmtQual
-  Buyer's prefer Sale type which has Contract 15% down payment and Regular Term .
-  Higher price in Northridge neighborhood locatily .

-  Negative Impact on House Price
-  Lesser price for Houses which has "Second" (condition2 variable) proximity to near Positive off-site features = park, greenbelt etc .
-  Other worlds, lesser price if property has promixity to more than 1 near positive off-site features, which can also mean outside the city.
-  Lesser price for Severly Damaged Home functionallity
-  General condition of Basement doesn't matter much.
-  Older building will cost lesser (MSSubClass)
-  Lesser price if Type of heating is Hot water or steam heat other than gas
-  Bigger Pool Area fetches less price

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Anaconda3 jupyter Notebook
- python 3.9

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- Thanks to Upgrad Instructors and Live Sessions

## Contact
Created by [@skmdesai] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

# Surpise-House-Price-Prediction

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Technologies Used
Numpy
Pandas
Seaborn
MatPlotLib
ScikitLearn


## Conclusions
The RMSE values of RIDGE is better than LASSO, but in order to have a more robust and generalised model, it is important to keep the complexity of the model to minimum. As you can see from our modelling exerise, RIDGE results in 220 predictor variabls making the model highly comples, where as LASSO results in 20 predictor variables making the model simple in nature. 

We will go ahead and use LASSO as it is a simpler model. LASSO brings makes the model simpler by assigning a zero value to insignificant features, enabling us to choosethe predictive variables.

Based on our modelling, we come to the conclusion the below predictor variables are the ones the company needs to focus on for predicting the price of houses: 
- The below variables are significant in predicting the price: 
- OverallQual - Rates the overall material and finish of the house
- GarageCars - Size of garage in car capacity
- Fireplaces - Number of fireplaces
- TotRmsAbvGrd - Total rooms above grade (does not include bathrooms)	
- CentralAir_Y - Central air conditioning (YES)
- MSZoning_RL	- Identifies the general zoning classification of the sale (Residential Low Density)
- 2ndFlrSF - Second floor square feet
- BsmtFinType1_GLQ - Rating of basement finished area (Good Living Quarters)
- Foundation_PConc - Type of foundation (Poured Contrete)
- BsmtExposure_Gd	- Refers to walkout or garden level walls(Good Exposure)
- MasVnrType_None	- Masonry veneer type (None)
- LotShape_Reg - General shape of property (Regular)	
- BsmtExposure_No	- Refers to walkout or garden level walls (No Exposure)
- RoofStyle_Gable	- Type of roof (Gable)
- MSZoning_RM	- MSZoning (Residential Medium Density)
- BsmtFinType1_Unf - 	Rating of basement finished area (Unfinshed)
- BsmtQual_TA - Evaluates the height of the basement (Typical (80-89 inches))	
- ExterQual_TA - Evaluates the present condition of the material on the exterior (Average/Typical)	
- KitchenQual_TA - Kitchen quality (TA)	
- GarageFinish_Unf - Interior finish of the garage (Unfinished)



## Contact
sreejith-rajashekaran


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
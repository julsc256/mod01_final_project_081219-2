
# King's County Data Set
____

## The Problem: 
### Predict the sale prices of houses as accurately as possible.
#### Why? Because we to be able to sell houses that people will want to buy and make money.
___

## The dataset -- King's County Data Set
### What I needed to do:
* Clean the dataset of all the null values and make sure that there were no datatypes did not match up correctly
* Continue going through the data and clearing outliers and checking for multicollinearity.
* Focused on features that will sell like:
    * Price/Sqft
    * 3 bedrooms/ 2 baths
    * Quality of homes
* Variables used for the model were:
    * Continuous variables
        * price_per_sqft
        * sqft_living
        * sqft_lot15
    * Categorical variables
        * quality
        * bathrooms
        * bedrooms
        * view
        * condition
        * floors
        * waterfront
* After determining the values that were categorical and continuous I ran an OLS stats model to check for how well the variables will fit to the model.
    * 0.974
___

## Recommendations:
 * Houses with 3 bedrooms and 2 bathrooms are being sold at a high quality mark of 8.
 * The average condition of a house is 3, which is the middle of the way of best condition.
 * Houses can be sold for an average price of 450,000 at midway condition and descent quality.
 * The zipcodes that adhere to these conditions are: 
    * 98125 
    * 98059
    * 98028
    * 98034
    * 98144
    * 98011
    * 98136 
    * 98072
    * 98065

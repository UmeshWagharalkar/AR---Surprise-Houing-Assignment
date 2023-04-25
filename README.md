# AdvancedRegression-SurpriseHousing
 Surprise housing dataset using lasso and ridge regression

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

### The company wants to know:
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.

 Also, determine the optimal value of lambda for ridge and lasso regression.

## Content Covered:
- Importing Necessary Libraries
- Step 1: Reading and Understanding the Data
- Step 2: Visualizing the Data
- Step 3: Data Preparation
- Step 4: Splitting the Data into Training and Testing Sets
- Step 5: Building a linear model
- Step 6: Model Evaluation
- Step 7: Comparison between Training and Testing dataset for Ridge & Lasso
- Conclusion:

## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn:
    LinearRegression
    Ridge
    Lasso
    GridSearchCV
    cross_val_score
    scale
    StandardScaler
    train_test_split
    r2_score
  
## Conclusion from the Assignment:
- We got a decent score for both Ridge and Lasso regression.
- Ridge : Train :90.9    Test :87.4
- Lasso : Train :89.8    Test :86.4

#### Top 5 most significant variables in Ridge are:

- ('SaleCondition_Partial', 0.143)
- ('SaleCondition_Others', 0.105)
- ('SaleCondition_Normal', 0.099)
- ('GarageFinish_Unf', 0.094)
- ('GarageFinish_RFn', 0.092)

#### Top 5 most significant variables in Lasso are:

- ('SaleCondition_Partial', 0.198)
- ('SaleCondition_Others', 0.12)
- ('SaleCondition_Normal', 0.098)
- ('GarageFinish_Unf', 0.084)
- ('GarageFinish_RFn', 0.079)


#### These Varaiables are directly proportional to each other.

- Optimal Value of lamda for ridge : 10
- Optimal Value of lamda for Lasso : 0.001

### Because of Feature selection as well we can choose Lasso regression in this case.

## Acknowledgements
- This project was inspired by upGrad
- This project was based on https://www.lendingclub.com/.


## Contact
Created by [UmeshWagharalkar] - feel free to contact me!
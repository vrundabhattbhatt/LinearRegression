# Multiple Linear Regression Assignment

## Car Price Case Study

#### Problem Statement:

A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. 

Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

   - Which variables are significant in predicting the price of a car
   - How well those variables describe the price of a car

Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the Americal market. 


### **The interpretation is important!**


## Goal

Model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 


## Approaches Used & Conclusion on Approach

### There are two things tried in approach
### 1. For CompanyName: Create dummy variables for all CompanyNames or Use Standard Deviation of Prices of Company's cars
### 2. For Step by Step approach: 
 1) Drop variables using high p-values and then high VIF 
 2) drop variables with high VIF and then high p-values 
 3) drop variables looking at both VIF and high p-values.

### For CompanyName : 
finalized the approach for using stadard deviation and group companies into four groups using median of standard deviation. more details are there in below steps

### For step by step approach: 
used VIF and p-values both on each step to decide which variable should be removed.

### Note: 
All above approaches total: 6 are tried and then the code with approach  that showed best results is uploaded here.

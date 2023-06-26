# CAPSTONE-PROJECT-CLASSIFICATION-Mobile-Price-Range-Prediction-

## Problem Statement
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is

## Attribute Information
 1) Battery_power - Total energy a battery can store in one time measured in mAh
2) Blue - Has bluetooth or not
3) Clock_speed - speed at which microprocessor executes instructions
4) Dual_sim - Has dual sim support or not
5) Fc - Front Camera mega pixels
6) Four_g - Has 4G or not
7) Int_memory - Internal Memory in Gigabytes
8) M_dep - Mobile Depth in cm
9) Mobile_wt - Weight of mobile phone
10) N_cores - Number of cores of processor
11) Pc - Primary Camera mega pixels
12) Px_height - Pixel Resolution Height
13) Px_width - Pixel Resolution Width
14) Ram - Random Access Memory in Mega
15) Touch_screen - Has touch screen or not
16) Wifi - Has wifi or not
17) Sc_h - Screen Height of mobile in cm
18) Sc_w - Screen Width of mobile in cm
19) Talk_time - longest time that a single battery charge will last when you are
20) Three_g - Has 3G or not
21) Wifi - Has wifi or not
22) Price_range - This is the target variable with value of 0(low cost), 1(medium cost),

# About dataset :
This dataset has 2000 rows and 21 columns. This dataset of 21 columns has 0 values ​​in 2 columns. I want to replace the 0 values ​​with the mean of the same column. There are no null values ​​and duplicate values ​​in this dataset. The target column of this dataset has four classes.

# In this project : 
1. Introduction
2. Exploratory Data Analysis./Reviwing Our Dataset
3. Data Preprocessing.
4. Model Training- MULTICLASS AND BINARY.
5. Evaluation.
6. Conclusion

# EDA Final Conclusion
1) In low cost mobile most of the mobile battery is from 500 to 1000 and in medium and high cost mobile the mobile battery is stable but in very high cost mobile most of the mobile battery is from 1500 to 2000
2) Talk time is less due to low battery life in low cost mobile
3) Screen width and screen height are less affecting mobile price, screen height and screen width have increased slightly in very high price mobile phones.
4) Pixel height is showing less difference. Pixel width is increasing with mobile price.
5) Pixel of front camera is showing less difference and Pixel of rear camera is increasing with mobile price.
7) Around 76% datapoints are 3G supported, rest 23% datapoints are not 3G supported
8) Around 52% datapoints are 4G supported, rest 47% datapoints are not 4G supported
9) The internal memory of low cost, medium cost and high cost mobiles is almost same but the internal memory of very high cost mobiles is increased
10) As the price of mobile is increasing, similarly the RAM of mobile is also increasing.

# Final Conclusion
From EDA we can see that here are mobile phones in 4 price ranges. All classes have the same amount of datapoints
Class is not unbalanced and every class is important so training and test score is important
Logestic regression and XGBoost model gives better results compared to other models

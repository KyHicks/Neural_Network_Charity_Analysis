# Neural_Network_Charity_Analysis

## Overview

Using machine learning and neural networks help the company Alphabet Soup determine which applicants with be sucessful if
funded by Alphabet Soup. To make sure the donations made by Alphabet Soup will be effective and beneficial we will create a binary
classifier to help predict if an organization will be sucessful if they are funded.  

## Results

A CSV file containing over 34,000 organizations that had received donations in the past was used to help determine the results.
The data set contained the following information:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

Optimization #1:

![This is an image](https://github.com/KyHicks/Neural_Network_Charity_Analysis/blob/main/Images/optimization_1.PNG)

* Binned INCOME_AMT column
* Created 5,821 total parameters, an decrease of 160 from the original of 5,981
* Accuracy improved 0.13% from 72.33% to 72.42%
* Loss was reduced by 2.10% from 58.08% to 56.86%


Optimization #2:

![This is an image](https://github.com/KyHicks/Neural_Network_Charity_Analysis/blob/main/Images/optimization_2.PNG)

* Created 8,801 total parameters, an increase of 2,820 from the original of 5,981
* Accuracy decreased 0.11% from 72.33% to 72.24%
* Loss increased by 1.75% from 58.08% to 59.10%

Optimization  #3:

![This is an image](https://github.com/KyHicks/Neural_Network_Charity_Analysis/blob/main/Images/optimization_3.PNG)

* Created 11,101 total parameters, an increase of 5,120 from the original of 5,981
* Accuracy increased 0.19% from 72.33% to 72.47%
* Loss decreased by 1.82% from 58.08% to 57.02%



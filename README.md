# Kharagpur-data-science-hackathon
Kharagpur Data Analytics Group presents  Kharagpur Data Science Hackathon sponsored by Airtel

 # Mengary Revenue Prediction



![image]("https://github.com/Thushar-marvel/Kharagpur-data-science-hackathon/blob/main/images/image1.png")
 
 # Problem Statement

Mengary is an online E-Commerce company that delivers goods to its customers all over the U.S.A (similar to Amazon). The 3 subsidiary companies under it namely Kariox, Fynota, and Qexty sell products in the Electronics, Food & Beverage, and Clothing Industry segment, respectively. The CEO and the board of directors of the parent company have been excessively worried about the profits for the present year considering their profits were not great last financial year. They wish to predict the profits on each product of the subsidiary companies so that they can adjust the discount given on the loss-making products. But since they don’t know which products are going to produce loss, the management has decided to hire you and your team to help predict the profit for the upcoming financial year. It's almost the end of the financial year 2020-2021 and the data of all the order placement dates and delivery dates(including other features) are known to the company beforehand.
# Objective

Your task is to predict the profits for the remainder of the year 2021 (April to December). The board members have put in a lot of trust in you to accurately predict the profits for the remainder of this year so that they can increase their revenue. 


# Dataset
 The data set is available in kaggle. It can be downloaded ![here](https://www.kaggle.com/c/mengary-revenue-prediction/data)
 
#  Performed data exploration
 Performed univariate, bivariate and multi variate analysis for extracting the realtionship between the indepedent as well as dependent variables
 Data pre-processing was done to create dummy variables and to treat outliers.
 
 # Model
 The pre-processed data was trained with linear regression, L1 and L2 regularization, KNN,ensemble algorithms.
 It was found Xg boost performed well.
 
 # Model evaluation
 The evaluation of the predicted outcomes is done on the basis of the R^2 score. The formula for the same is as follows:

R^2 = 1 - (RSS / TSS)

where,
R^2 = coefficient of determination
RSS = sum of squares of residuals
TSS = total sum of squares

![image](https://github.com/Thushar-marvel/Kharagpur-data-science-hackathon/blob/main/images/image2.png)
![image](https://github.com/Thushar-marvel/Kharagpur-data-science-hackathon/blob/main/images/image3.png)

Top 10% for the submission 1
Top 5th for submission 2 with r2_score 0.95 for test dataset.





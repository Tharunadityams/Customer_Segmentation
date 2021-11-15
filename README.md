# Customer Segmentation - Python

The goal of the project is to find and group customers of an online convenience store based on their purchase behaviour.
The data used for the analysis is from a convenience store called Ulabox based in Spain. 

We will be using wide range of functions for,

1. Exploratory Data Analysis
2. Visualization using PCA
3. Checking for Dependable variables
4. Outliner detection and handling
5. Clustering 

## Dataset

The dataset holds details about 30k anaonymized orders with 14 different features. 
1. customer, is the unique customer id
2. order, is the unique order id
3. total_items, is the number of products bought in the order
4. discount%, is the amount of discount provided during the purchase, the negative value in discount stands for extra amount the customer paid to ulabox as delivery charge or any other mode of fee 
5. weekday, is the day of the week in which the order was placed
6. hour, is the time in which the order is placed
7. Food%, is the amount of money spent on non-fresh food in the purchase, it may include grocery products like sugar, coffee powder, oats etc
8. Fresh%, is the amount of money spent on fresh food like milk, fruits, vegetables etc
9. Drinks%, is most probably the percentage of amount spent on alchohol like wine, vodka, scotch etc. There is a teeny tiny chance that these also include soft drinks
10. Home%, is the percentage of money spent in home accessories
11. Beauty%, is the percentage of amount spent in beauty products
12. Health%, is the percentage of amount spent in medicine or health products like protein supplement, carb supplement etc
13. Baby%, is the percentage spent in baby products
14. Pets%, is the percentage spent in pet products like pedigree

## What was concluded?

The dataset was sucessfully divided into 10 categories based on customer purchsae behaviour,
Fresh&Frozen          6162
Health_Conscious      5534
Beauty                5006
New_Parents           3378
Non_Pershable_Food    2813
Drinks                2541
Monthly_Supplies      1105
Home_Decor             689
Loyalty_Customers      508
Pet_Supplies           365

The most sold items are the the fresh and frozen ones, where as pet supplies are not in much demand. It is adviced to stock less of pet supplies and more of fresha and packed foods.
There are group of customers whom seems to be shopping only items on discounts most of the time but they are just 124 customers of the total crowd. 





 






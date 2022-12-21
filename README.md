# Amazon_Vine_Analysis

## Overview of the analysis
I was tasked to analyze Amazon reviews written by members of the paid Amazon Vine club. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

As part of this project, I reviewed Sports product dataset and used PySpark (Colabs) to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset. The complete analysis was done which was submitted to Jennifer for SellBy Stakeholder's review. 

## Results

After carrying out the analysis the following results were obtained:

![Paid Vine reviews](https://github.com/Manishthapa2022/Amazon_Vine_Analysis/blob/main/Images/Paid_Vine_reviews.png)


![Unpaid Vine reviews](https://github.com/Manishthapa2022/Amazon_Vine_Analysis/blob/main/Images/Unpaid_Vine_reviews.png)


* There were 334 no of Vine reviews and 61614 number of non-Vine reviews. 

* 139 no of Vine reviews were five stars and 32665 no of non-Vine reviews were five stars

* Approx 41.62 % of vine reviews were 5 stars and Approx 53.01 % of non-Vine reviews were 5stars.

## Summary
After filtering and analyzing the data, it can be seen that the five star percentage of the vine review (paid) is approx 41.62% whereas the five star percentage for non vine reviews (unpaid) is approx 53.01%. This proves that there is no positive bias for the vine reviews. Moreover, the number of vine reviews (334) is considerably less than the non-Vine reviews (61614).

I would recommed to carry out the following to further consider whether there is bias:
* We can carry out a qualitive test: A visual assessment of the distribution of data for both the unpaid and paid reviews to check te mean and the see if there is any skew. A left skew would show that ther are extreme negative values in the data set and a right skew will show extreme postive values in the data set. 
* We can also do an analysis on the reviews temselves to understand if there is any sarcasim. Using Machine Learning, we can process the reviews and check for the accuracy. 

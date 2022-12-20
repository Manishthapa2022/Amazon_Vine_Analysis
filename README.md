# Amazon_Vine_Analysis

## Overview of the analysis
I was tasked to analyze Amazon reviews written by members of the paid Amazon Vine club. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

As part of this project, I reviewed Sports product dataset and used PySpark (Colabs) to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset. The complete analysis was done which was submitted to Jennifer for SellBy Stakeholder's review. 

## Results

After carrying out the analysis the following results were obtained:

!(Paid Vine reviews)[]

!(Unpaid Vine reviews)[]

* There were 334 no of Vine reviews and 61614 number of non-Vine reviews. 

* 139 no of Vine reviews were five stars and 32665 no of non-Vine reviews were five stars

* Approx 41.62 % of vine reviews were 5 stars and Approx 53.01 % of non-Vine reviews were 5stars.

## Summary
Upon careful evaulation of the database, we can summarize that the total number of reviews were XX out of which XX no were Vine reviews and XX no were non-Vine reviews. 


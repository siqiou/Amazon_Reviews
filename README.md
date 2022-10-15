# Amazon_Reviews
## Overview of the Analysis
This project is to help business make right business decisions to support marketing strategies. We are going to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

We will be using pySpark to extract and analyze the data from the reviews, and find out is there are any bias towards Vine member reviews, we will also compare the results between paid and unpaid members.

PySparka, AWS RDS database, and pgAdmin are used in this project. Dataset: Video games.

## Results

-How many Vine reviews and non-Vine reviews were there?
 For the dataset chosen, there was only 94 Vine member review and 40471 non-Vine member reviews.
 
-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 48 Vine member rated 5 stars, 15663 non-Vine member rated 5 stars.
 
-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
51% of Vine reviews were 5 stars, 38% non-Vine reviews were 5 stars

![img1](https://github.com/siqiou/Amazon_Reviews/blob/167c83bc0edba9cbc54a2cc661de10242b55a0df/images/paid_members.png)
![img2](https://github.com/siqiou/Amazon_Reviews/blob/167c83bc0edba9cbc54a2cc661de10242b55a0df/images/unpaid_members.png)

## Summary
The percentage of 5 star reviews are 13% higher among Vine members, there seems to be bias for the reviews. However the sample size of Vine members are quite small comparing to the total number of non-Vinew reviews, we are going to test if the same pattern exists in 4 star reviews to get a bigger picture.

![img3](https://github.com/siqiou/Amazon_Reviews/blob/167c83bc0edba9cbc54a2cc661de10242b55a0df/images/four_star_reviews.png)

The percentage of 4 star reviews dropped for both groups, 25% in Vine members and 16% in non-Vine members. This number indicates that bias still exists in Vine members.


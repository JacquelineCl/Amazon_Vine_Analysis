# Amazon_Vine_Analysis
Module16, analyzing Amazon Vine reviews for bias

## Overview
This analysis will check the Amazon Grocery reviews, available at https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Grocery_v1_00.tsv.gz, to determine if there is any favorable bias in the ratings given by reviewers in the Vine progarm. The analyis will compare the percentage of 5 start reviews left by Vine program participants vs the percentage left by those who did not participate in the Vine program. 

The analysis will answer:
* How many Vine reviews and non-Vine reviews were there?
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

## Results
* The Vine program had 2,829 total reviews and there were 1,574,578 non-Vine reviews.
![vine program total reviews](https://github.com/JacquelineCl/Amazon_Vine_Analysis/blob/1c8f81244b281e98c1762c3119b5941ed6731c23/Resources/vine_program_total_reviews.png)
![non-vine program total reviews](https://github.com/JacquelineCl/Amazon_Vine_Analysis/blob/1c8f81244b281e98c1762c3119b5941ed6731c23/Resources/not_vine_program_total_reviews.png)
* The Vine program had 1,044 5-star reviews and there were 895,551 non-Vine 5-star reviews. 
![vine program total 5-star reviews](https://github.com/JacquelineCl/Amazon_Vine_Analysis/blob/1c8f81244b281e98c1762c3119b5941ed6731c23/Resources/vine_program_total_5_star_reviews.png)
![non-vine program total reviews](https://github.com/JacquelineCl/Amazon_Vine_Analysis/blob/1c8f81244b281e98c1762c3119b5941ed6731c23/Resources/not_vine_program_total_5_star_reviews.png)
* 37% of the Vine program reviews were 5-star and 57% of the non-Vine reviews were 5-star.

## Summary
There is not favorable bias in the Grocery reviews given by Vine participants as the non-Vine reviewers were more likely to give a 5-star review. Additional analysis could be to perform this analysis on multiple Amazon Review datasets to see if this is true for different product categories. 


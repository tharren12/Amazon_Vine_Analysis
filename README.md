# Amazon Vine Analysis

## Overview of Project

Through this project we will be analyzing Amazon reviews written by members of the paid Amazon Vine program and understand if there is a bias towards 5 star ratings for those that were paid vs. unpaid. The analysis was performed on Video Game reviews, which is one of 50 review datasets.

## Resources

Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz
Data Tools: Google Colab, Pyspark, AWS, PostgreSQL


## Results

## Vine Reviews vs. Non-Vine Reviews

**Number of Vine Reviews**

|  count|                90|

**Number of Non-Vine Reviews**

|  count|            37,385|

For video game reviews there were 90 Vine reviews and 37,385 Non-Vine reviews.

## How Many and Percentage 5 Star Reviews

**Vine Review Breakdown**

![Vine_5Star](https://user-images.githubusercontent.com/92001105/154822774-ad19b92f-cae5-452c-8437-90804374ade1.png)

**Non-Vine Review Breakdown**

![Non_Vine_5Star](https://user-images.githubusercontent.com/92001105/154822781-526f8abd-5a65-4646-af52-1319ae8726e6.png)

For Vine Reviews there were 44 of 90 reviews that were rated 5 stars or 49% of total. For Non-Vine Reviews there were 14,626 5 star reviews of 37,385 total reviews or 39% of total.

## Summary

There appears to be some positive bias for reviews in the Vine program as 49% were rated 5 star vs. 39% of non-Vine reviews, however, it should be noted there was only 90 total Vine reviews so the sample size is quite small. A couple of other analyses that could be conducted is to look at other review datasets that may have more volume of data, especially for Vine reviews, which could confirm or deny whether there is a positive bias with Vine reviews. An additional analysis could also be to do a Paired t-test to compare the two groups to understand if there is a statistical difference between the two groups.



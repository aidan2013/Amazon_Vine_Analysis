# Amazon_Vine_Analysis

## Overview of Analysis

The purpose of this project is to analyze the Amazon Pet Product reviews and determine if reviews in the Vine program have a bias in the percentage of 5-star reviews. 
In order to review this data, a database is created in Amazon RDS, then tables are created within a pgAdmin database. The Amazon Review dataset is then extracted, transformed and loaded into the pgAdmin tables. For this analysis, Google Collaboratory and PySpark was used to analyze the data.  

## Results

- There were a total of 170 Vine Reviews and a total of 37,840 non-Vine reviews

![image](https://user-images.githubusercontent.com/91445591/163740828-8f11ca14-71ed-452d-aaea-9ef41bb294b1.png)

- Out of the total reviews, 65 were 5-star Vine reviews and 20,612 were non-Vine reviews

![image](https://user-images.githubusercontent.com/91445591/163740889-41a5ea72-1bab-4dfb-96c2-6d401b50731e.png)

- 38.24% of the Vine reviews were 5-stars and 54.47% of the non-Vine reviews were 5-stars.

![image](https://user-images.githubusercontent.com/91445591/163740973-f9788f25-6b6b-4809-9112-9107eb45df41.png)

## Summary

There does not appear to be a positivity bias for reviews in the Vine program. On the contrart, there is a lower percentage of 5 star reviews that fall under the Vine program compared to the non-Vine reviews. 

It would be helpful to dive deeper into the Vine vs non-Vine reviews by comparing the count and percentages of 1 through 4 star reviews. There may not be a positivity bias for 5-star reviews however there may be an impact or change in behavior for lower star reviews. 

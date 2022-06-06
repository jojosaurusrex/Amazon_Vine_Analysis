# Amazon_Vine_Analysis

## Overview
The purpose of this analysis was to see if we could connect to an AWS database to postgres on our own, after doing together as a class. As well as, exposing us to some practice within google collab notebooks.

## Results

![products_table](https://user-images.githubusercontent.com/98374315/172095862-086a1def-cdfb-45bb-be3a-794396ce9f98.PNG)
Figure 1. Products table from deliverable 1

![review_id_table](https://user-images.githubusercontent.com/98374315/172095910-aecfe67f-a43a-4970-8b4d-79550813a826.PNG)
Figure 2. Review ID Table from deliverable 1

![customer_table](https://user-images.githubusercontent.com/98374315/172095949-87b67d97-913d-4a9c-a032-1e2f453e4783.PNG)
Figure 3. Customer Table from deliverable 1

![vine_table](https://user-images.githubusercontent.com/98374315/172095975-631c1eb4-fd7d-42c0-8b83-7dfdde2076cd.PNG)
Figure 4. Vine Table from deliverable 1, used for deliverable 2

There were only 20 vine reviews, meaning only 20 people got paid to review certain products, and out of those 20, 12 of them left a 5 star review (60%). There were 25,124 people that did not get paid for a review, and out of that sample size 13,491 people left a 5 star review (53.69%).

## Summary
All in all, we calculated total number of reviews, number of 5 star reviews, and percentage of 5 star reviews for vine and non-Vine reviews. Looking at the numbers, there is definitely a positive bias towards 4 and 5 star reviews through the vine program, but not by very much. Another analysis we could to prove our point is calculate the same variables for the whole dataframe to see if the spread is any larger. If it is, it proves our point, and if not, it might just be encouraging a larger sample size of people to review products.

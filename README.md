# Amazon_Vine_Analysis

## Purpose: 
The purpose of this analysis is to choose an Amazon dataset amongst the list given to analyze in PySpark in Google Colab, connect to an RDS Instance to populate 
the tables in pgAdmin and the use of pandas, to do additional analysis using the vine_table exported dataset, which was exported from pgAdmin. 

## Results: 
1. How many Vine reviews and non-Vine reviews were there? 
662 for Yes
![image](https://user-images.githubusercontent.com/116187123/226488621-75f7c235-e0f0-4ecc-8721-7e0ddcad9467.png)
2534418 for No
![image](https://user-images.githubusercontent.com/116187123/226488659-c8fd5d9e-8b65-43e9-800a-ab44fbce902f.png)

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
When filtering, unable to output filtered data with multiple conditions. Results are shown below: 
![image](https://user-images.githubusercontent.com/116187123/226489317-2b56f8ba-587e-4fd8-8478-a41523c18f99.png)


## Summary: 
I think that a positivity bias for any review could potentially be caused by a star_rating above a 4. An additional analysis that could be performed is the comparison of the helpful_votes, star_rating, paid vs. unpaid conditions. 

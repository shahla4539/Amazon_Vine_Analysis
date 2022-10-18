# Amazon_Vine_Analysis
Module-16


## Overview of the analysis: 
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. My task for this project is by using my knowledge of PySpark, Pandas, or SQL, I’ll determine if there is any bias towards reviews that were written as part of the Vine program. Also if having a paid Vine review makes a difference in the percentage of 5-star reviews.

## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions:

# Total_volte>20
The data is filtered to create a DataFrame or table where there are 20 or more total votes to pick reviews that are more likely to be helpful and to avoid having division by zero errors later on.

![image](https://user-images.githubusercontent.com/105535250/196331430-74acfa26-2dcc-4f3f-995b-4d52a65ac494.png)

# Percentage of helpful_vote
The data is further filtered to create a DataFrame or table where the percentage of helpful_votes is equal to or greater than 50%.

![image](https://user-images.githubusercontent.com/105535250/196331716-aa048dad-8880-44cb-a1c4-d04b5c70dfaf.png)

# Paid vine reviews  
The data is filtered to create a DataFrame or table that retrieves all the rows where a review was written as part of the Vine program (paid), vine == 'Y'.

![image](https://user-images.githubusercontent.com/105535250/196333277-1caabb1b-6bf9-40a5-a89a-5fb043cececf.png)

# Unpaid vine reviews 
Similarly, the data is filtered to create a DataFrame or table that retrieves all the rows where the review was not part of the Vine program (unpaid), vine == 'N'.

![image](https://user-images.githubusercontent.com/105535250/196333724-084cc928-1f11-48e4-b140-de6b1b9cfcf1.png)

# 5 stars paid Vine reviews 

Another dataframe or table is created to show particularly 5 star paid vine data and counted the total number of 5 star paid vine reviews as well.

![image](https://user-images.githubusercontent.com/105535250/196334042-7c3747a3-8549-4612-b24f-3517f0f9fd3d.png)

![image](https://user-images.githubusercontent.com/105535250/196334485-083e4c74-2924-43a8-af99-b0a611046345.png)

# 5 stars unpaid Vine reviews 
The data is filtered to create a DataFrame or table to show particularly 5 star unpaid vine data and counted the total number of 5 star unpaid vine reviews as well.

![image](https://user-images.githubusercontent.com/105535250/196334872-fa28846c-b49b-4664-8482-d3dc5154bca8.png)

![image](https://user-images.githubusercontent.com/105535250/196334932-e6af6372-dc09-414a-b29f-749e54dd35bf.png)

# Percentage of 5 stars Vine reviews  


# Percentage of unpaid 5 stars Vine reviews 

# Summary:
Based on the analysis we did, we did not find any bias reviews in the Vine program. If that have been the case then there will be too many paid vine reviews which is not true in this data. The number of paid reviews is very lower than the number of unpaid reviews. 



Then, provide one additional analysis that you could do with the dataset to support your statement.

An additional analysis is recommended to support the statement (2 pt)

The total number of reviews, the number of 5-star reviews, and the percentage 5-star reviews are calculated for all Vine and non-Vine reviews (15 pt)






# Amazon_Vine_Analysis

**Overview of the analysis of the Vine program:**

The purpose of this analysis is to analyize Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and   publishers to receive reviews for their products.In this project, we analysied amazon dataset that contained reviews related to watches. To perform this analysis, we used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then we used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.


**Results:**

For deliverable 1 four tables were created and loaded into postgres as below:

* customers_table

![alt text](https://github.com/Asmaamkawi/-Amazon_Vine_Analysis/blob/main/Images/customers_table.PNG)



* products_table

![alt text](https://github.com/Asmaamkawi/-Amazon_Vine_Analysis/blob/main/Images/products_table.PNG)



* review_id_table


![alt text](https://github.com/Asmaamkawi/-Amazon_Vine_Analysis/blob/main/Images/review_id_table.PNG)



* vine_table

![alt text](https://github.com/Asmaamkawi/-Amazon_Vine_Analysis/blob/main/Images/vine_table.PNG)



For deliverable 2 we answered the following questions:

* How many Vine reviews and non-Vine reviews were there?
 The analysis results indicates that there was a 47 vine reviews while there was a 8362 non vine reviews.
 
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
The analysis results indicates thatthere 15 vine five stars reviews while there was a total of 4332 non-vine five stars reviews.

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
The analysis shows that the percentage of Vine reviews were 5 stars was 0.3191489361702128 while the percentage of the non Vine reviews was 0.5180578808897393

**Summary:**
The conclution of the analysis is that the number of the unpaid reviews is much higher than the Vine program. Which indicates that the reviews are not biased according to the vine program (paid reviews).

 

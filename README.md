# Amazon_Vine_Analysis

**Overview of the analysis of the Vine program:**

The purpose of this analysis is to analyize Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and   publishers to receive reviews for their products.In this project, we analysied amazon dataset that contained reviews related to watches. To perform this analysis, we used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then we used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.


**Results:**

For deliverable 1 four tables were created and loaded into postgres as below:

* customers_table


* products_table


* review_id_table


* vine_table



For deliverable 2 we answered the following questions:

* How many Vine reviews and non-Vine reviews were there?
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

**Summary:**

 

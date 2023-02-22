# Amazon_Vine_Analysis

## Analysis Overview

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Resources

* Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt
* Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS


## Results

### Total number of reviews
  * Vine Reviews
  ![]<img width="434" alt="Screen Shot 2023-02-22 at 01 27 30" src="https://user-images.githubusercontent.com/78386151/220541264-a0b953ce-ecf5-4625-a082-282821e4a984.png">
  * Non-Vine Reviews
  
### Total number of 5-star reviews
  * Vine Reviews
  
  * Non-Vine Reviews
  
 ### Percentage of 5-star reviews
  * Vine Reviews
  
  * Non-Vine Reviews
  
## Summary
  
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

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
  ![]<img width="448" alt="Screen Shot 2023-02-22 at 01 37 16" src="https://user-images.githubusercontent.com/78386151/220542241-e3163081-e0dd-45d0-b89d-c1d11fa6c2e4.png">
  
### Total number of 5-star reviews
  * Vine Reviews
  ![]<img width="528" alt="Screen Shot 2023-02-22 at 01 38 21" src="https://user-images.githubusercontent.com/78386151/220542449-eb814aed-2528-4223-b557-c48f6bf14514.png">
  * Non-Vine Reviews
  ![]<img width="565" alt="Screen Shot 2023-02-22 at 01 39 02" src="https://user-images.githubusercontent.com/78386151/220542868-8528a481-0629-4f96-a564-3f2575ff78ac.png">
 
  
## Summary
  
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.

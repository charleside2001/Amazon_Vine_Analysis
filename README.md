 ![amazon.png](https://github.com/charleside2001/Amazon_Vine_Analysis/blob/main/images/amazon.png) 
# Overview of Amazon Vine Analysis
Apache Spark (`Pyspark`) was used to perform `ETL` process to extract amazon US grocery review  dataset, transform the data, connect to an `AWS` `RDS` instance, and load the transformed data into `PostgreSQL` database, then perform an analysis to determine if there is any bias towards reviews that were written as part of the Amazon vine program

  #### Customer Table
  ![customers_table.png](https://github.com/charleside2001/Amazon_Vine_Analysis/blob/main/images/customers_table.png) 
  
  
  #### Products Table
  ![products_table.png](https://github.com/charleside2001/Amazon_Vine_Analysis/blob/main/images/products_table.png) 
  
  
  #### Review ID Table
  ![review_id_table.png](https://github.com/charleside2001/Amazon_Vine_Analysis/blob/main/images/review_id_table.png) 
  
    
  #### Vine Table
  ![vine_table.png](https://github.com/charleside2001/Amazon_Vine_Analysis/blob/main/images/vine_table.png) 
  
  

## Results
  *1.*  There are a total of  `61` Vine reviews and `28174` non-Vine reviews 

  *2.*  There are a total of `20` `5-stars` Vine reviews and `15672` `5-stars` non-Vine reviews 

  *3.*  There are a total of `33%` `5-stars` Vine reviews and `56%` `5-stars` non-Vine reviews
  
  #### Vine Reviews
  ![vine_reviewa.png](https://github.com/charleside2001/Amazon_Vine_Analysis/blob/main/images/vine_reviewa.png) 

  
## Summary
 *1.* With just a total of `61` paid Vine reviewers, it is recommended that more datasets be analysed to better conclude  if there is any bias toward favorable reviews from Vine members.
 
 *2.* It is recommended that further analysis be performed using the Product Title  and Customer Review ID to determine the reviews customers have on the products.
 

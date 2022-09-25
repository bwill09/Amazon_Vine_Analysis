## Amazon_Vine_Analysis

## Amazon Vine Review – Furniture Products 

### Project Overview

This project with Jennifer comparatively a bigger project, where we’ll review Amazon reviews written by members the Vine program. The Vine Program by Amazon is a service the lets publishers and manufactures get earnest feedback on their products. There are companies that pay Amazon Vine members, to assess / review their product and publish a review.

This project open access to multiple database, where each of them contain review about specific product, for gargets, food, clothing apparel etc. The requirement is to select one among those dataset and use PySpark to perform the ETL (Extract Transform and Load) process with the data, connect to AWS RDS instance, then load the transformed data into pdAdmin. Secondly, utilize PySpark, Pandas or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Lastly, write a review for Jennifer to present to the SellBy stakeholders. ¬

### Data Source: 

SQL table schema.CSV and Amazon ETL starter code.csv
Data Tools: Amazon_Reviews_ETL.ipynb and Vine_Review_Analysis.ipynb
Software: Python 3.9 , VS Code Version: 1.67.2 , Google Collaboratory 

### Output:

Customer_df

<img width="1044" alt="Customer_df" src="https://user-images.githubusercontent.com/106555873/192150298-8eac8e12-0b12-4ee4-84a2-1cf19e1b4f1f.png">


Product_df

<img width="1034" alt="Product_df" src="https://user-images.githubusercontent.com/106555873/192150308-ba1a9250-32dd-4533-80bc-6e0bbe57a632.png">


Review_id>

<img width="1026" alt="Review_id" src="https://user-images.githubusercontent.com/106555873/192150318-daffbc15-4ca6-422b-88c8-afafc930a47d.png">


Vine_table

<img width="995" alt="vine_df" src="https://user-images.githubusercontent.com/106555873/192150324-378b7e22-bbe4-45f3-9962-89e13050779a.png">


### Summary 

*	Most reviews pertaining to furniture product are low from Vine members : over 90% are Non-Vine
*	5 Star reviews are about the as furniture, they are all Vine members: 99.8% 5-Star reviews are Non-Vine

### Suggestions:

*	Amazon Vine Analysis provide a conducive dataset on the 5-star rating.
*	Also, this analysis suggest that much data is not Vine reviews over specific products, there’s a possibility to reduce the outcome and set a separate dataset to focus solely on Vine products 

[Anazon_Review_ETL](https://colab.research.google.com/drive/1qP1ZMYUCcLgiopu3dcJNdBJJgZgpMYBz#scrollTo=V58rxea0HqSa) , [Vine_Review]

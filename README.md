# Data_Warehousing

## What is a data warehouse?

A data warehouse, or enterprise data warehouse (EDW), is a system to aggregate your data from multiple sources so it’s easy to access and analyze. Data warehouses typically store large amounts of historical data that can be queried by data engineers and business analysts for the purpose of business intelligence.

Instead of only having access to your data in individual sources, a data warehouse will funnel all your data from disparate sources (like transactional systems, relational databases, and operational databases) into one place. Once it’s in the warehouse, it’s accessible and usable across the business to get a holistic view of your customers. When your data is in one place, you can analyze related data from different sources, make better predictions, and ultimately make better business decisions.

## Data warehouse vs. database: how they're different

Databases and data warehouses are related but not the same.

A database is a way to record and access information from a single source. A database is often handling real-time data to support day-to-day business processes like transaction processing.

A data warehouse is a way to store historical information from multiple sources to allow you to analyze and report on related data (e.g., your sales transaction data, mobile app data, and CRM data). Unlike a database, the information isn’t updated in real-time and is better for data analysis of broader trends.

## How do data warehouses, databases, and data lakes work together?
Typically, businesses use a combination of a database, a data lake, and a data warehouse to store and analyze data. Amazon Redshift’s lake house architecture makes such an integration easy.
As the volume and variety of data increases, it’s advantageous to follow one or more common patterns for working with data across your database, datalake, and data warehouse:

![Screenshot from 2022-08-07 11-13-58](https://user-images.githubusercontent.com/99721045/183277121-50726995-ec1c-4499-9f97-9bc85599222e.png)
     Image (above): Land data in a database or datalake, prepare the data, move selected data into a data warehouse, then perform reporting.

![Screenshot from 2022-08-07 11-15-30](https://user-images.githubusercontent.com/99721045/183277166-00dd4015-55c1-42c9-96c7-c7f4eab736eb.png)Image (above): Land data in a data warehouse, analyze the data, then share data to use with other analytics and machine learning services

A data warehouse is specially designed for data analytics, which involves reading large amounts of data to understand relationships and trends across the data. A database is used to capture and store data, such as recording details of a transaction.

Unlike a data warehouse, a data lake is a centralized repository for all data, including structured, semi-structured, and unstructured. A data warehouse requires that the data be organized in a tabular format, which is where the schema comes into play. The tabular format is needed so that SQL can be used to query the data. But not all applications require data to be in tabular format. Some applications, like big data analytics, full text search, and machine learning, can access data even if it is ‘semi-structured’ or completely unstructured.

## What are the benefits of using a data warehouse?

Benefits of a data warehouse include the following:
  Informed decision making
  Consolidated data from many sources
  Historical data analysis
  Data quality, consistency, and accuracy
  Separation of analytics processing from transactional databases, which improves performance of both systems
  
## 6 factors to consider when choosing a data warehouse
Now you know the benefits of a data warehouse—but how do you go about picking one? Consider these factors when figuring out which data warehouse will best suit your business needs.
1. Data types
2. Scaling for data storage
3. Scaling for performance
4. Maintenance
5. Ecosystem
6. Cost

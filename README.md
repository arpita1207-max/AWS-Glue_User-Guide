# AWS-Glue_User-Guide

What is AWS GLue and Why AWS Glue is Used ?

Fully Managed ETL Service managed by AWS

Main Component of AWS Glue

1.Data Catalog:-

1.Has metadata information(Scheman Info,Connection Info,etc) about Data Stores(AWS S3,DyanoDB,JDBC,ODBC ,etc)
2.Can connect up to 70 data sources and manage your data in a centralized data catalog.

ETL Engine:-

1.Run,Mointor and Extract,Transform and Load  (ETL pipelines) to load your data into data lake ,Spark inbuilt.

AWS Glue Components:-

1.DataBase:-

1. Logical Containers with in the AWS Data Catalog that stores metadata table.
2. These tables contain metadata information about the data stored in Amazon RDS,S3,DyanmoDB,Amazon Redshift.
3. Helps to manage and organize metadata ,it is easier to catalog,search and query data assets.
4. Not a phyiscal database.
   
2.Tables:-

1. Contains schema and Properties details about the dataset.
2. Metadta about the data stores such as AWS S3,DynamoDB,RedShift ,etc.
3. Crucical role in managing ,organzing and querying and transforming data by providing a structured way to describe and access data.
   
3.Connections:-

1.It is configuration object that enables AWS GLue to connect to the data store.
2. Contains neccessary database connection details such as database endpoints,username,password which causes the connection from AWS Glue to the data store.
4.Crawlers
1. Connects to the data store and scans the data and infer the schema details and store metadata tables in the Data Catalog.

AWS ETL:-

1.Triggers:-

1.Event to start the job.Event-Based or Scheduled Trigger

2.ETL Jobs:-

1. ETL Job to transform your data.
3. Leverage the power of spark.
4. Serverless
5. Create ETL Job visually or bring your script with business logic.
   
3.Workflows





# DataEngineering project using AWS

End to end data engineering project on AWS

Steps performed-
Used Kaggle to download a dataset and loaded it into an S3 bucket and then created a data lake which consisted of a landing area, a cleansed db and a reporting/ analytical db.
Created a crawler to populate the AWS Glue catalog with tables to understand the metadata.
Wrote a script on AWS Lambda to process the data and convert the json files to Parquet files and used Glue studio to create a pipeline to transfer clean data into a reporting/ analytical database.
Used triggers to automate the transfer of data to an existing S3 bucket.
Lastly used AWS Athena to query the analytical database.

![DataArchitecture](https://user-images.githubusercontent.com/97470708/185236470-ff06dc70-42aa-4873-ba2b-0b95f1d03528.png)

Data Cleansing Process

![Screenshot (285)](https://user-images.githubusercontent.com/97470708/185236862-7db4f070-7840-47c7-aee6-9c41e03da710.png)

Glue Studio pipeline

![Screenshot (287)](https://user-images.githubusercontent.com/97470708/185238407-179bc560-a446-4691-abd9-9f6af78c62e4.png)

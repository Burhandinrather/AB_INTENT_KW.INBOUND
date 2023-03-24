# AB_INTENT_KW.INBOUND
This folder contains the SQL Script which has been used to create table and import the data in INBOUND Schema.
The Schema contains AB_RAW table in which we are importing the data.
We have created a stage in the Script which has been used to get the data from AWS S3 bucket.
Also, a Snow Pipe has been created which loads the data from S3 Bucket in an automated manner i.e., whenever the client uploads the new data files in the S3 Bucket, the Snow Pipe automatically loads it into the Snowflake data table by appending data to the existing table.

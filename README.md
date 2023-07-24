# Covid_19 End To End Data Pipeline Using AWS Data Services

### Introduction
This Project basically demonstrates how to build a robust scalable end to end data pipeline that extracts Covid data from S3 storage using AWS Glue,  transform the data and creat a Dimensional data model using python before loading it into Redshift for analysis and visualization.

### Project Objective
We want Our Data Analysts and Data Scientists to have the capability to easily analyze the data and use data mining to find patterns, trends, and risk factors for COVID-19 infection which will be used to make informed data driven decisons.

### AWS Services 
* Amazon S3
* Glue Crawler
* Glue Catalog
* AWS Athena
* Redshift

### About the Dataset
The Covid_19 dataset is a harmonized collection of the core data pertaining to COVID-19 reported cases by geography, in a format prepared for analysis.

### Project Architecture
<img src = "https://github.com/jaykay04/Covid_19_End_to_End_Data_Pipeline_Using_AWS_Data_Services/blob/main/images/covid-19-de-architecture.drawio.png" >

### Project Implementation
The first approach to implementing this project was to create a Dimensional Model from the relational model we have  as shown below.   

<img src = "https://github.com/jaykay04/Covid_19_End_to_End_Data_Pipeline_Using_AWS_Data_Services/blob/main/images/CovidDimenisonModel.drawio.png" >

Next, we take the following steps
1. Connect to Athena and Query Data using Jupyter Notebook
2. Write the ETL Job in python
3. Save the result to s3
4. Build tables on redshift
5. Then copy the data to redshift


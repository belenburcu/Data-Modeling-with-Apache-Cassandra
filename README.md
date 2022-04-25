<h1 align="center"> Data Modeling with Apache Cassandra  </h1> 
<p align="center"> Data Engineering Nanodegree - Udacity </>

## Project Description
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results since the data reside in a directory of CSV files on user activity on the app.

In this project, I created an Apache Cassandra database that can query song play data to answer the questions. I completed an ETL pipeline using Python that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

## Dataset
There is one dataset **event_data** as CSV file partitioned by date. Here are examples of filepaths:
```
 event_data/2018-11-08-events.csv
 event_data/2018-11-09-events.csv
```
Sample Data:

<img src="./image_event_datafile.png" alt="Logo">


## Project Template 

- Process the event_datafile_new.csv dataset to create a denormalized dataset
- Model the data tables keeping in mind the queries you need to run
- Load the data into tables you create in Apache Cassandra and run your queries


## Project Structure

|      File / Folder     |                         Description                    |
| :--------------------: | :----------------------------------------------------: |
|  data_modeling.ipynb   |    Data modeling notebook which contains all steps     |
|       data.zip         |                     All song data - CSV                |
|image_event_datafile.png|                     Sample data image                  |


## :star:Contact
Burcu Belen - [Linkedin](https://www.linkedin.com/in/burcu-belen/) 

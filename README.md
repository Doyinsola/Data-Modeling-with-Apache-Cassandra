# Data-Modeling-with-Apache-Cassandra
Project to help master data modeling with Apache Cassandra and complete an ETL pipeline using Python.

## Project Description

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

### Project Overview

This project applies learnings from data modeling with Apache Cassandra coursework to complete an ETL pipeline using Python. 
 
Create queries to ask the following three questions of the data
 1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
 2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
 3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'
 
 To complete the project:  
 * Model the data by creating tables in Apache Cassandra to run queries. 
 * Complete the ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra table.
 * Project template that takes care of all the imports and provides a structure for ETL pipeline needed to process the data has been provided.

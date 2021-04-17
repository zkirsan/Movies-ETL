# Movies-ETL

The project consists of the process of extracting, transforming and loading. The movie database was prepared for a fictional 
Amazing Prime. It was created a function that takes in three files- Wikipedia data, Kaggle metadata, and the MovieLens rating data-
and performed the ETL process by adding the data to a PostgreSQL database.

## Overview

The project aims to create an automated pipeline that extracts, transforms and loads data. This process has four stages. The first stage starts from cleaning the data to the loading process. The whole process can be executed
with a single function, which is extract_transform_load in the final stage ETL_cretae_database file. 

## ETL_function_test

	- Reading data and converting them into the Pandas DataFrame

## ETL_clean_wiki_movies

	- The ETL process begins with the wikipedia-movies data
	- Using Python, apply() and map() methods in the lambda 
	- using RegEx

## ETL_clean_kaggle_data

	- The cleaning Kaggle metadata process;
		- changing datatypes, 
		- filling missing values and filtering unwanted columns
		- merging data frames 

## ETL_create_database

This function defines the final stage of the pipeline process. This process includes a connection between Pandas(Python Library) and PostgreSQL database.

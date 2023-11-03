# spotify-etl-pipeline
Author - Sarthak Hans

## Description
This repository contains the code and documentation for an end-to-end data engineering project, which aims to implement a complete data pipeline using the Spotify API to extract data, process it, and analyze it for insights.

## Project Overview

The project encompasses the following stages:

- **Data Extraction**: Integration with the Spotify API to fetch data.
- **Data Transformation**: Writing and applying transformation functions to the data.
- **Data Loading**: Storing the transformed data on AWS S3.
- **Automation**: Deploying the code on AWS Lambda for automatic data extraction and transformation.
- **Trigger Setup**: Adding triggers to run the extraction and transformation functions automatically.
- **Analytics**: Building analytics tables on the data files using AWS Glue and Athena for easy querying and insights generation.

## Files Description
1. spotify_api_data_extract.py: Contains the code for extracting data from Spotify API.
2. spotify_transformation_load_function.py: Contains the code for transforming and loading the data to S3.

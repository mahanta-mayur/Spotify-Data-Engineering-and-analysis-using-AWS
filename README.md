# Spotify Data Engineering and Analysis Using AWS

This project demonstrates a complete data engineering lifecycle using AWS to process and analyze Spotify's 2023 dataset. From initial data preparation in Python to interactive visual analytics in AWS QuickSight, this project utilizes a variety of AWS services to uncover insights into Spotify's vast music dataset.

## Overview

The journey begins with cleaning and preprocessing the Spotify dataset using Python, followed by loading the refined data into Amazon S3. AWS Glue's ETL jobs are utilized for data transformation, enriching the dataset for analytical purposes. AWS Glue crawlers then automate the schema detection, facilitating SQL-based explorations via Amazon Athena. The project culminates with the construction of analytical dashboards in AWS QuickSight, providing a comprehensive view of music trends and patterns.

## Project Workflow

- **Data Preparation**: Initial data cleaning and preprocessing with Python.
- **Data Staging and Warehousing**: Leveraging S3 for data storage, followed by transformation and loading into a data warehouse.
- **ETL Processing**: Employing AWS Glue for robust ETL workflows.
- **Data Analysis**: Utilizing Amazon Athena for detailed SQL-based data analysis.
- **Visualization and Reporting**: Creating dynamic dashboards in AWS QuickSight for data visualization.

## Services Used

- **Amazon S3**: For data storage and management.
- **AWS Glue**: For data cataloging and ETL processing.
- **Amazon Athena**: For querying and analyzing data.
- **AWS QuickSight**: For data visualization and business intelligence.
- **Python**: For initial data cleaning and preprocessing.

## Dataset Overview

The dataset includes a comprehensive collection of Spotify tracks, including metadata such as track popularity, artist details, and album information, aiming to explore musical preferences and streaming trends.

Dataset Link - https://www.kaggle.com/datasets/tonygordonjr/spotify-dataset-2023

## Architecture Diagram

![Architecture Diagram](./architecture.png)

## Detailed Insights Through Screenshots

### AWS Glue and ETL

- **AWS Glue Crawlers**: ![AWS Glue Crawlers](./Screenshots/all_crawlers.png)
- **ETL Jobs in AWS Glue**: ![ETL Jobs in AWS Glue](./Screenshots/all_job_runs_in_GLUE.png)

### S3 Buckets and Data Staging

- **S3 Buckets for Data Staging and Warehousing**: ![S3 Buckets](./Screenshots/all_s3_buckets.png)
- **Staging Data in S3**: ![Staging Data](./Screenshots/staging_data.png)

### Athena Queries

#### SQL Queries Analysis

- **Total Tracks Analysis**: ![Total Tracks](./Screenshots/query_1_getting_total_tracks.png)
- **Most Popular Tracks Analysis**: 
  - ![Part A](./Screenshots/query_2_top_10_most_popular_tracks_A.png)
  - ![Part B](./Screenshots/query_2_top_10_most_popular_tracks_B.png)
- **Albums with Highest Popularity**: 
  - ![Part A](./Screenshots/query_3_top_5_albums_with_highest_popularity_A.png)
  - ![Part B](./Screenshots/query_3_top_5_albums_with_highest_popularity_B.png)
- **Genre Popularity Analysis**: 
  - ![Part A](./Screenshots/query_4_most_popular_genre_by_average_track_popularity_A.png)
  - ![Part B](./Screenshots/query_4_most_popular_genre_by_average_track_popularity_B.png)
- **Track Popularity Over Time**: 
  - ![Part A](./Screenshots/query_5_popularity_of_tracks_changing_over_time_A.png)
  - ![Part B](./Screenshots/query_5_popularity_of_tracks_changing_over_time_B.png)

### Other Significant Screenshots

- **Data Warehouse Data**: ![Data Warehouse](./Screenshots/data_warehouse_data.png)
- **Visual ETL Job and Pipeline**: ![Visual ETL Pipeline](./Screenshots/Visual_ETL_job_and_pipeline.png)
- **Table in Athena Query Editor**: ![Athena Table](./Screenshots/table_in_ATHENA_query_editor.png)

## Additional Resources

- Detailed project documentation and data models are available upon request.

## Conclusion

This project encapsulates the essence of modern data engineering, illustrating the potential of AWS cloud services combined with Python's processing power to analyze and visualize Spotify's expansive dataset. The insights derived not only reveal current music trends but also pave the way for predictive analytics in the music industry.

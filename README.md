# Data-analyst-vinuthna

Project Title: "Data Analytics for the City of Vancouver: Unlocking Urban Insights Using AWS Cloud Solutions"

Objective
The aim is to design and implement a Data Analytics Platform (DAP) to analyze and visualize the geographic distribution of VAHEF (Vancouver Affordable Housing Endowment Fund) properties. Specifically, this work focuses on:

Identifying the count of properties in each neighborhood (Geo Local Area).
Highlighting regions with more than 15 properties.
Visualizing property concentration to support decision-making for resource allocation.


Dataset

1) Source: Dataset includes details on properties owned by VAHEF, such as:
Building Number: Unique identifier for each property.
Geo Local Area: Indicates the neighborhood where the property is located.
Other attributes (omitted in this analysis for relevance).

2) Data Characteristics:
Complete dataset with no missing values (as identified in the profiling step).
Focus on Building Number and Geo Local Area for the analysis.

Methodology
The analysis was conducted in four systematic steps: data ingestion, profiling, cleaning, and pipeline design.



1. Data Ingestion

Objective: Load raw data into AWS S3 for centralized storage and future processing.

Steps:
Created two S3 buckets:

Raw Data Bucket: For unprocessed data.

Transformed Data Bucket: For cleaned and structured data.



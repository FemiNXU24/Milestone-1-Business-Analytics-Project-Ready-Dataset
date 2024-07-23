README: Internet Service Churn Dataset
Overview
This dataset contains information on customer subscriptions and service usage for an internet service provider. It is used to analyze factors affecting customer churn and improve service offerings. The dataset has been cleaned and transformed to facilitate further analysis and modeling.

Data Details
Total Entries: 72,274
Columns:
id: Unique identifier for each record
is_tv_subscriber: Indicates if the customer has a TV subscription (1 for yes, 0 for no)
is_movie_package_subscriber: Indicates if the customer has a movie package subscription (1 for yes, 0 for no)
subscription_age: Age of the subscription in years
bill_avg: Average monthly bill amount
reamining_contract: Remaining contract duration in months
service_failure_count: Number of service failures experienced
download_avg: Average download speed in Mbps
upload_avg: Average upload speed in Mbps
download_over_limit: Indicates if the download limit is exceeded (1 for yes, 0 for no)
churn: Indicates if the customer has churned (1 for yes, 0 for no)
is_heavy_user: Indicates if the customer is a heavy user based on download and upload averages (True/False)
has_service_issues: Indicates if the customer has experienced service issues (True/False)
subscription_age_group_1-2 years: Boolean indicator for subscription age between 1 and 2 years
subscription_age_group_2-3 years: Boolean indicator for subscription age between 2 and 3 years
subscription_age_group_3-4 years: Boolean indicator for subscription age between 3 and 4 years
subscription_age_group_4-5 years: Boolean indicator for subscription age between 4 and 5 years
subscription_age_group_5+ years: Boolean indicator for subscription age greater than 5 years
Data Preparation
Cleaning: Handled missing values, removed duplicates, and corrected inconsistencies.
Transformation: Added new features such as is_heavy_user and has_service_issues to enrich the dataset.
Integration: No data combination was necessary as the dataset is self-contained.
Usage
This dataset is intended for analysis related to customer churn, including:

Identifying factors influencing churn
Analyzing subscription patterns
Developing predictive models
Accessing the Data

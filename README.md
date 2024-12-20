# data-analyst-Jaya Vivek Reddy B

# Data Crawler for Vancouver Rental Standards Current Issue. Phase 2

## Project Description

This project involves creating a data crawler to analyze the Vancouver Rental Standards Current Issues dataset. The primary goal is to identify and understand patterns and trends in unresolved by-law issues across different geographic areas within Vancouver. By leveraging data analytics and cloud computing tools, this project aims to provide actionable insights that can help improve rental standards and address compliance challenges in the city.

## Data Analytical Platform

![1](https://github.com/user-attachments/assets/a0a496a1-7ca1-4abe-9419-0cbbcbb55042)

## Objective
The main objective of this project is to conduct a thorough analysis of the unresolved by-law issues reported in Vancouver's rental properties. This involves cleaning, transforming, and analyzing the dataset to uncover insights related to the geographic distribution of these issues.

## Methodology
### Data Collection

The dataset was sourced from Vancouver's open data portal and ingested into an Amazon S3 bucket for further processing.

### Data Profiling and Cleaning

Data profiling was performed using AWS Glue DataBrew to understand the structure, content, and quality of the data. Issues such as missing values, outliers, and inconsistencies were identified and addressed. The cleaned data was stored in a separate S3 bucket.

### Data Transformation

Data transformation involved converting data types, standardizing formats, and deriving new features. AWS Glue was used to perform these transformations and create a structured dataset suitable for analysis.

### Data Enriching

AWS Glue was used for data enrichment, involving data transformation, cleansing, and augmenting raw data with additional context. DynamoDB was utilized for its scalability and NoSQL data service capabilities. A data crawler was implemented to perform large-scale data enrichment automatically.

### Data Protection

Data protection involved securing data through encryption, access control, and backup strategies using AWS Key Management Service (KMS) and IAM for user permissions.

### Data Observability

Data observability was performed using Amazon CloudWatch, enabling real-time monitoring and visualization of key metrics related to the data pipeline's performance and health.

## Tools and Technologies

- **Amazon S3**: Storage service for raw, transformed, and curated data.
- **AWS Glue DataBrew**: Data preparation tool for profiling and cleaning data.
- **AWS Glue**: ETL service for data transformation and loading.
- **DynamoDB**: NoSQL data service for scalable data management.
- **Amazon Athena**: Query service for running SQL queries on data stored in S3.
- **Amazon CloudWatch**: Monitoring and observability service.
- **AWS Key Management Service (KMS)**: Encryption and key management service.
- **Python**: Programming language for data manipulation and analysis.
- **Pandas**: Python library for data manipulation and analysis.

### Data Pipeline Design

The data pipeline was designed using AWS Glue's Visual ETL tool to automate the process of data extraction, transformation, and loading (ETL). The pipeline included steps for data enrichment, data protection, data governance, and data observation.

![2](https://github.com/user-attachments/assets/45d58bed-cd52-4dd1-a367-6dd8606a2a6b)

### Data Observability

![3](https://github.com/user-attachments/assets/258bf31b-8346-4af2-8115-7f661fd5952b)

## Conclusion

This project successfully demonstrated the use of cloud computing and data analytics tools to perform an exploratory analysis of the Vancouver Rental Standards Current Issues dataset. The insights gained from this analysis can help inform policy decisions and resource allocation to address rental compliance issues in Vancouver.

## Future Work

Future work could involve extending the analysis to include additional datasets, such as demographic information or historical data on by-law compliance. Further, predictive analytics could be employed to forecast trends and identify potential areas of concern before they become significant issues.

## Acknowledgments
This project was completed as part of a cloud computing class assignment. Special thanks to **Professor Mahmood Mortazavi Dehkordi** for the guidance and resources provided.

## Contact
For any questions or further information, please contact Jaya Vivek Reddy at [jayavivek123@gmail.com](mailto:jayavivek123@gmail.com).


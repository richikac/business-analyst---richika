My AWS Data Analytics Platform Projects Portfolio
Welcome to my GitHub portfolio! This Portfolio is to showcase the projects that demonstrate my skills and expertise in creating Data Analytics Platform (DAP) using Amazon Web Services (AWS) cloud services. My project work focuses on two procedures - Council Voting records for the City of Vancouver and Academic Integrity Procedure for University Canada West (UCW). DAP created for both the procedures leverages a range of AWS services such as Amazon S3, Amazon Glue, Amazon Athena, KMS etc. for data storing, querying, data cleaning, transforming data, and quality control. By working on these projects, I have covered various aspects of analysis like exploratory data analysis , descriptive analysis, implementing ETL Pipelines, and data quality control. 
Section 1: Council Voting Records for the City of Vancouver
Project 1: Exploratory Data Analysis Using Amazon Athena
This project involves exploratory data analysis of council voting records for the City of Vancouver to generate insights on the number of votes based for Year 2023 and 2024 to generate insights on the curated zone.
Project Title: "Exploring Council Voting Patterns with Amazon Athena"
Objective: To perform an exploratory data analysis on council voting records using Amazon Athena, identifying trends and participation rates.
Dataset: Council Voting Records for Year 2023 and 2024 which are stored in the Raw Zone of Amazon S3.
Methodology:
Using Amazon Athena to query for generatory voting summary for two years 2023 and 2024 and generating statistics.
Using Chart function in the excel to explore the patterns and outcomes of voting.
Tools and Technologies:
   Amazon Athena for querying the council voting database.
   Amazon S3 for storing the dataset for council voting records.
Deliverables:
     A report generated from Athena queries summarizing key insights into council voting patterns.
 Project 2: Descriptive Analysis of Council Voting Outcomes with Amazon Athena
Project Description: Conducting a comprehensive descriptive analysis of council voting outcomes using Amazon Athena.
2. Project Title: "Descriptive Analysis of Council Voting Outcomes with Amazon Athena"
3. Objective: To leverage Amazon Athena for performing descriptive analysis on council voting outcomes and participation rates, providing valuable insights into voting trends.
4. Dataset: Council Voting Records from Amazon S3, including vote details and participation information.
Methodology
Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
Data Analysis
Query Execution: Write and execute SQL queries in Athena to extract key metrics.
Insight Generation: Analyze voting outcomes and participation rates.
Data Aggregation:
Metric Calculation: Aggregate data to calculate total votes and participation rates.
Statistical Summaries: Generate statistical summaries and visualizations.
Tools and Technologies:
 Amazon Athena for executing SQL queries and analysis.
Amazon S3 for storing the council voting datasets.
Deliverables:
Analysis Report: Aggregated data and statistical insights of voting patterns.
Visualizations: Charts and graphs illustrating key findings.
Query Documentation: SQL queries and process overview.

 Project 3: ETL Pipeline for Council Voting Records of the City of Vancouver with AWS Glue
1. Project Description: Developing a robust ETL pipeline to process council voting records using AWS Glue.
2. Project Title: "Data Wrangling for Council Voting Records Using AWS Glue"
3. Objective: To design and implement an ETL pipeline using AWS Glue that efficiently cleans, transforms, and prepares council voting records.
4. Background: Ensuring data consistency and removing inaccuracies from council voting records for meaningful analysis.
5. Dataset: Council Voting Records stored in Amazon S3.
6. Methodology:
     Data Extraction: Use AWS Glue Crawlers to catalog the source data in Amazon S3.
     Data Cleaning:
         Duplicate Removal: Identify and remove duplicates.
         Handling Missing Values: Implement strategies to manage incomplete data.
         Standardization: Ensure data formats are consistent.
     Data Transformation:
         Field Derivation: Create new fields for analysis.
         Normalization: Standardize data values and structures.
     Data Loading: Store the cleaned and transformed data back into Amazon S3.
7. Tools and Technologies:
     AWS Glue for data cleaning and transformation.
     Amazon S3 for storing the structured dataset.
8. Deliverables:
     Cleaned and structured dataset in Amazon S3.
     ETL Pipeline Documentation: Process flow, scripts, and data quality report.

 Project 4: Ensuring Data Quality and Privacy Control with AWS Glue and Amazon S3
1. Project Description: Implementing data quality control measures on council voting records using AWS Glue.
2. Project Title: "Ensuring Data Quality in Council Voting Records Using AWS Glue"
3. Objective: To establish and enforce data quality control measures using AWS Glue to ensure data accuracy.
4. Background: The necessity of highquality data in council voting records for accurate analysis and reporting.
5. Scope: Data Profiling, Cleansing, and Validation for council voting records.
6. Methodology:
     Data Cleansing and Validation: Use AWS Glue to apply data quality rules.
     Data Quality Checks: Validate data against predefined quality metrics.
7. Tools and Technologies:
     AWS Glue for data cleansing and validation.
     Amazon S3 for storing validated datasets.
8. Deliverables:
     Validated dataset in the Trusted Zone.
     Data Quality Report: Summary of quality improvements.



 Section 2: UCW Academic Integrity Procedure

 Project 1: Exploratory Data Analysis Using Amazon Athena
1. Project Description: Analyzing academic integrity records to uncover patterns using Amazon Athena for querying data stored in Amazon S3.
2. Project Title: "Exploring Academic Integrity Patterns with Amazon Athena"
3. Objective: To perform an exploratory data analysis on academic integrity cases using Amazon Athena, identifying trends and patterns.
4. Dataset: UCW Academic Integrity Records stored in Amazon S3.
5. Methodology:
     Data Querying: Use Amazon Athena to run SQL queries for summarizing data and generating descriptive statistics.
     Data Exploration: Explore the dataset to understand academic integrity trends.
6. Tools and Technologies:
     Amazon Athena for data querying and analysis.
     Amazon S3 for storing academic integrity records.
7. Deliverables:
     A report generated from Athena queries summarizing insights into academic integrity patterns.

 Project 2: Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena
1. Project Description: Conducting a comprehensive descriptive analysis of academic integrity outcomes using Amazon Athena.
2. Project Title: "Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena"
3. Objective: To leverage Amazon Athena for performing descriptive analysis on academic integrity cases, providing insights into patterns and outcomes.
4. Dataset: UCW Academic Integrity Records from Amazon S3.
5. Methodology:
     Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
     Data Analysis:
         Query Execution: Write and execute SQL queries to extract metrics.
         Insight Generation: Analyze outcomes and trends.
     Data Aggregation:
         Metric Calculation: Aggregate data to calculate key metrics.
         Statistical Summaries: Generate summaries and visualizations.
6. Tools and Technologies:
     Amazon Athena for querying and analysis.
     Amazon S3 for storing academic integrity datasets.
7. Deliverables:
     Analysis Report: Aggregated data and statistical insights.
     Visualizations: Charts and graphs illustrating findings.
     Query Documentation: SQL queries and process overview.

 Project 3: ETL Pipeline for UCW Academic Integrity Records with AWS Glue
1. Project Description: Developing an ETL pipeline to process academic integrity records using AWS Glue.
2. Project Title: "Data Wrangling for Academic Integrity Records Using AWS Glue"
3. Objective: To design and implement an ETL pipeline using AWS Glue to clean, transform, and prepare academic integrity records.
4. Background: Ensuring data consistency and accuracy in academic integrity records for meaningful analysis.
5. Dataset: UCW Academic Integrity Records stored in Amazon S3.
6. Methodology:
     Data Extraction: Use AWS Glue Crawlers to catalog data in Amazon S3.
     Data Cleaning:
         Duplicate Removal: Identify and remove duplicates.
         Handling Missing Values: Implement strategies for incomplete data.
         Standardization: Ensure consistent data formats.
     Data Transformation:
         Field Derivation: Create metrics for analysis.
         Normalization: Standardize values and structures.
     Data Loading: Store the processed data back into Amazon S3.
7. Tools and Technologies:
     AWS Glue for data cleaning and transformation.
     Amazon S3 for storing structured datasets.
8. Deliverables:
     Cleaned dataset in Amazon S3.
     ETL Pipeline Documentation: Process details and scripts.
     Data Quality Report: Summary of quality improvements.

 Project 4: Ensuring Data Quality and Privacy Control with AWS Glue and Amazon S3
1. Project Description: Implementing data quality control measures on academic integrity records using AWS Glue.
2. Project Title: "Ensuring Data Quality in Academic Integrity Records Using AWS Glue"
3. Objective: To establish and enforce data quality control measures using AWS

 Glue for academic integrity records.
4. Background: Ensuring highquality data in academic integrity records for accurate analysis.
5. Scope: Data Profiling, Cleansing, and Validation for academic integrity records.
6. Methodology:
     Data Cleansing and Validation: Apply data quality rules using AWS Glue.
     Data Quality Checks: Validate data against predefined metrics.
7. Tools and Technologies:
     AWS Glue for data cleansing and validation.
     Amazon S3 for storing validated datasets.
8. Deliverables:
     Validated dataset in the Trusted Zone.
     Data Quality Report: Summary of quality improvements.



This portfolio showcases the comprehensive use of AWS services for two different datasets: Council Voting Records and UCW Academic Integrity Records. Both sets of projects employ Amazon Athena for exploratory and descriptive analysis, AWS Glue for ETL processes and data quality control, and Amazon S3 for secure data storage. The consistent approach across these projects highlights the versatility and efficiency of AWS tools in managing and analyzing complex datasets while ensuring data quality, privacy, and compliance.



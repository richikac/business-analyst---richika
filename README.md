#**My AWS Data Analytics Platform Projects Portfolio**
</br></br> Welcome to my GitHub portfolio! This Portfolio is to showcase the projects that demonstrate my skills and expertise in creating Data Analytics Platform (DAP) using Amazon Web Services (AWS) cloud services. My project work focuses on two procedures - Council Voting records for the City of Vancouver and Academic Integrity Procedure for University Canada West (UCW). DAP created for both the procedures leverages a range of AWS services such as Amazon S3, Amazon Glue, Amazon Athena, KMS etc. for data storing, querying, data cleaning, transforming data, and quality control. By working on these projects, I have covered various aspects of analysis like exploratory data analysis , descriptive analysis, implementing ETL Pipelines, and data quality control. </br>
##**Section 1: Council Voting Records for the City of Vancouver**
</br>##**Project 1: Exploratory Data Analysis Using Amazon Athena**
</br>This project involves exploratory data analysis of council voting records for the City of Vancouver to generate insights on the number of votes based for Year 2023 and 2024 to generate insights on the curated zone.
</br>**Project Title:** "Exploring Council Voting Patterns with Amazon Athena"
</br>**Objective:** To perform an exploratory data analysis on council voting records using Amazon Athena, identifying trends and participation rates.
</br>**Dataset:** Council Voting Records for Year 2023 and 2024 which are stored in the Raw Zone of Amazon S3.
</br>Dataset has these fields : Meeting Type, Vote Date, Vote Number, Agenda Description, Vote Start Date Time, Council Member Names, Vote (whether in Favour, Abstain or in opposition), Decision (Lost, carried or Carried Unanimously), Vote Detail Id
</br>**Methodology:**
</br>Methodolgy involves using Amazon Athena to run SQL query on the curated data stored in the Amazon S3 for the council voting memebers to generate statistical insights on the percentage votes in the favour for two years 2023 and 2024. Then, using Chart function in the excel to explore the patterns of votes in favour.
</br>**Tools and Technologies:**
</br>Amazon Athena for querying the council voting database.
</br>Amazon S3 for storing the dataset for council voting records.
</br>**Deliverables:** To generate a report showing bar graph of percentage number of council votes in favour for the years 2023 and 2024.
 
**Project 2: Descriptive Analysis of Council Voting Outcomes with Amazon Athena**
**Project Description:** Conducting a comprehensive descriptive analysis of council voting outcomes using Amazon Athena.
 **Project Title:** "Descriptive Analysis of Council Voting Outcomes with Amazon Athena"
**Objective:** To leverage Amazon Athena for performing descriptive analysis on council voting outcomes and participation rates, providing valuable insights into voting trends.
**Dataset:** Council Voting Records from Amazon S3, including vote details and participation information.
**Methodology**
Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
Data Analysis
Query Execution: Write and execute SQL queries in Athena to extract key metrics.
Insight Generation: Analyze voting outcomes and participation rates.
Data Aggregation:
Metric Calculation: Aggregate data to calculate total votes and participation rates.
Statistical Summaries: Generate statistical summaries and visualizations.
**Tools and Technologies:**
 Amazon Athena for executing SQL queries and analysis.
Amazon S3 for storing the council voting datasets.
**Deliverables:**
Analysis Report: Aggregated data and statistical insights of voting patterns.
Visualizations: Charts and graphs illustrating key findings.
Query Documentation: SQL queries and process overview.

 **Project 3: ETL Pipeline for Council Voting Records of the City of Vancouver with AWS Glue**
**Project Description**: Developing a robust ETL pipeline to process council voting records using AWS Glue.
**Project Title:** "Data Wrangling for Council Voting Records Using AWS Glue"
**Objective:** To design and implement an ETL pipeline using AWS Glue that efficiently cleans, transforms, and prepares council voting records.
**Background:** Ensuring data consistency and removing inaccuracies from council voting records for meaningful analysis.
**Dataset:** Council Voting Records stored in Amazon S3.
**Methodology:**
Data Extraction: Use AWS Glue Crawlers to catalog the source data in Amazon S3.
Data Cleaning:
Duplicate Removal: Identify and remove duplicates.
Handling Missing Values: Implement strategies to manage incomplete data.
Standardization: Ensure data formats are consistent.
Data Transformation:
Field Derivation: Create new fields for analysis.
Normalization: Standardize data values and structures.
Data Loading: Store the cleaned and transformed data back into Amazon S3.
**Tools and Technologies:**
     AWS Glue for data cleaning and transformation.
     Amazon S3 for storing the structured dataset.
**Deliverables:**
     Cleaned and structured dataset in Amazon S3.
     ETL Pipeline Documentation: Process flow, scripts, and data quality report.
** Project 4: Ensuring Data Quality and Privacy Control with AWS Glue and Amazon S3**
**Project Description:** Implementing data quality control measures on council voting records using AWS Glue.
**Project Title:** "Ensuring Data Quality in Council Voting Records Using AWS Glue"
**Objective:** To establish and enforce data quality control measures using AWS Glue to ensure data accuracy.
**Background:** The necessity of highquality data in council voting records for accurate analysis and reporting.
**Scope:** Data Profiling, Cleansing, and Validation for council voting records.
**Methodology:**
     Data Cleansing and Validation: Use AWS Glue to apply data quality rules.
     Data Quality Checks: Validate data against predefined quality metrics.
**Tools and Technologies:**
     AWS Glue for data cleansing and validation.
     Amazon S3 for storing validated datasets.
**Deliverables:**
     Validated dataset in the Trusted Zone.
     Data Quality Report: Summary of quality improvements.
**Section 2: UCW Academic Integrity Procedure**
**Project 1: Exploratory Data Analysis for UCW Academic Integrity Using Amazon Athena**
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

**Project 2: Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena**
**Project Description:** Conducting a comprehensive descriptive analysis of academic integrity outcomes using Amazon Athena.
**Project Title:** "Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena"
**Objective:** To leverage Amazon Athena for performing descriptive analysis on academic integrity cases, providing insights into patterns and outcomes.
**Dataset:** UCW Academic Integrity Records from Amazon S3.
**Methodology:**
     Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
     Data Analysis:
         Query Execution: Write and execute SQL queries to extract metrics.
         Insight Generation: Analyze outcomes and trends.
     Data Aggregation:
         Metric Calculation: Aggregate data to calculate key metrics.
         Statistical Summaries: Generate summaries and visualizations.
**Tools and Technologies:**
     Amazon Athena for querying and analysis.
     Amazon S3 for storing academic integrity datasets.
**Deliverables:**
     Analysis Report: Aggregated data and statistical insights.
     Visualizations: Charts and graphs illustrating findings.
     Query Documentation: SQL queries and process overview.

**Project 3: ETL Pipeline for UCW Academic Integrity Records with AWS Glue**
**Project Description:** Developing an ETL pipeline to process academic integrity records using AWS Glue.
**Project Title:** "Data Wrangling for Academic Integrity Records Using AWS Glue"
**Objective:** To design and implement an ETL pipeline using AWS Glue to clean, transform, and prepare academic integrity records.
**Background:** Ensuring data consistency and accuracy in academic integrity records for meaningful analysis.
**Dataset:** UCW Academic Integrity Records stored in Amazon S3.
**Methodology:**
Data Extraction: Use AWS Glue Crawlers to catalog data in Amazon S3.
Data Cleaning:
         Duplicate Removal: Identify and remove duplicates.
         Handling Missing Values: Implement strategies for incomplete data.
         Standardization: Ensure consistent data formats.
Data Transformation:
         Field Derivation: Create metrics for analysis.
         Normalization: Standardize values and structures.
     Data Loading: Store the processed data back into Amazon S3.
**Tools and Technologies:**
AWS Glue for data cleaning and transformation.
Amazon S3 for storing structured datasets.
**Deliverables:**
Cleaned dataset in Amazon S3.
ETL Pipeline Documentation: Process details and scripts.
Data Quality Report: Summary of quality improvements.


**Project 4: Ensuring Data Quality Control for UCW Academic Integrity with AWS Glue and Amazon S3**
**Project Description:** Implementing data quality control measures on academic integrity records using AWS Glue.
**Project Title:** "Ensuring Data Quality in Academic Integrity Records Using AWS Glue"
**Objective:** To establish and enforce data quality control measures using AWS
Glue for academic integrity records.
Background: Ensuring highquality data in academic integrity records for accurate analysis.
Scope: Data Profiling, Cleansing, and Validation for academic integrity records.
**Methodology:**
Data Cleansing and Validation: Apply data quality rules using AWS Glue.
Data Quality Checks: Validate data against predefined metrics.
**Tools and Technologies:**
AWS Glue for data cleansing and validation.
Amazon S3 for storing validated datasets.
**Deliverables:**
Validated dataset in the Trusted Zone.
Data Quality Report: Summary of quality improvements.



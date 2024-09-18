<h1>My AWS Data Analytics Platform Projects Portfolio</h1>
</br></br> Welcome to my GitHub portfolio! This Portfolio is to showcase the projects that demonstrate my skills and expertise in creating Data Analytics Platform (DAP) using Amazon Web Services (AWS) cloud services. My project work focuses on two procedures - Council Voting records for the City of Vancouver and Academic Integrity Procedure for University Canada West (UCW). DAP created for both the procedures leverages a range of AWS services such as Amazon S3, Amazon Glue, Amazon Athena, KMS etc. for data storing, querying, data cleaning, transforming data, and quality control. By working on these projects, I have covered various aspects of analysis like exploratory data analysis , descriptive analysis, implementing ETL Pipelines, and data quality control. </br>
</br></br><h2> DAP for Council Voting Records for the City of Vancouver</h2>
</br> This section involves the data management and analysis process to explain how to enhance several aspects of the government and finance departments in the City of Vancouver using AWS Cloud services to explore the patters, check data quality, descriptive analysis and to extract, transform and load the council voting records.The overall approach towards handling data as used affirms to the significance of cloud computing in improving the sector’s performance, in terms of embracing transparency and efficient resource utilization.
</br>Attached is the data pipeline design for DAP for the City of Vancover for Council Voting Records.
</br>![image](https://github.com/user-attachments/assets/14c78245-f7e5-488b-9830-ef4d1d2e2bd8)
</br>![image](https://github.com/user-attachments/assets/6f683d3e-0378-432f-aa56-91228660dafc)
</br>![image](https://github.com/user-attachments/assets/4ed002f1-f9ac-4481-9e51-f553ef54bcae)
</br>Below are the analysis perfomed on this dataset.
</br></br> <strong> Exploratory Data Analysis Using Amazon Athena </strong></br>
</br> <strong>Project Description:</strong></br> This project involves exploratory data analysis of council voting records for the City of Vancouver to generate insights on the number of votes based for Year 2023 and 2024 to generate insights on the curated zone.</br>
</br><strong>Project Title:</strong> "Exploring Council Voting Patterns with Amazon Athena"</br>
</br><strong>Objective:</strong> </br>To perform an exploratory data analysis on council voting records using Amazon Athena, identifying trends and participation rates.</br>
</br><strong>Dataset:</strong>  Council Voting Records for Year 2023 and 2024 which are stored in the Raw Zone of Amazon S3.
</br>Dataset has these fields : Meeting Type, Vote Date, Vote Number, Agenda Description, Vote Start Date Time, Council Member Names, Vote (whether in Favour, Abstain or in opposition), Decision (Lost, carried or Carried Unanimously), Vote Detail Id</br>
</br><strong>Methodology:</strong>
</br>Methodolgy involves using Amazon Athena to run SQL query on the curated data stored in the Amazon S3 for the council voting memebers to generate statistical insights on the percentage votes in the favour for two years 2023 and 2024. Then, using Chart function in the excel to explore the patterns of votes in favour.</br>
</br><strong>Tools and Technologies:</strong>
</br> - Amazon Athena for querying the council voting database.
</br> - Amazon S3 for storing the dataset for council voting records.</br>
</br><strong>Deliverables:</strong>  To generate a report showing bar graph of percentage number of council votes in favour for the years 2023 and 2024.</br>
</br></br><strong> Descriptive Analysis of Council Voting Outcomes with Amazon Athena</strong></br>
</br><strong>Project Description:</strong> </br>  This project involves a comprehensive descriptive analysis of council voting outcomes using Amazon Athena.</br>
</br><strong>Project Title:</strong>  "Descriptive Analysis of Council Voting Outcomes with Amazon Athena"</br>
</br><strong>Objective:</strong> </br> To leverage Amazon Athena for performing descriptive analysis on council voting outcomes and participation rates, providing valuable insights into voting trends.</br>
</br><strong>Dataset:</strong> Council Voting Records from Amazon S3, including vote details and participation information.</br>
</br><strong>Methodology</strong>
</br>Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
</br>Data Analysis
</br>Query Execution: Write and execute SQL queries in Athena to extract key metrics.
</br>Insight Generation: Analyze voting outcomes and participation rates.
</br>Data Aggregation:
</br>Metric Calculation: Aggregate data to calculate total votes and participation rates.
</br>Statistical Summaries: Generate statistical summaries and visualizations.</br>
</br><strong>Tools and Technologies:</strong>
</br> - Amazon Athena for executing SQL queries and analysis.
</br> - Amazon S3 for storing the council voting datasets.</br>
</br><strong>Deliverables:</strong>
</br>Analysis Report: Aggregated data and statistical insights of voting patterns.
</br>Visualizations: Charts and graphs illustrating key findings.
</br>Query Documentation: SQL queries and process overview.</br>
</br></br> <strong> Data Wrangling and ETL Pipeline for City of Vancouver with AWS Glue and Databrew </strong></br>
</br><strong>Project Description</strong>: This project involves data cleaning, structuring and developing a ETL pipeline to extract, transform and load the council voting records using AWS Glue and Databrew.</br>
</br><strong>Project Title:</strong>"Data Wrangling and ETL Pipeline for Council Voting Records Using AWS Glue"</br>
</br><strong>Objective:</strong> To clean and structure the data using databrew design and implement an ETL pipeline using AWS Glue that efficiently cleans, transforms, and prepares council voting records.</br>
</br><strong>Background:</strong> Ensuring data consistency and removing inaccuracies from council voting records for meaningful analysis.</br>
</br><strong>Dataset:</strong> Council Voting Records stored in Amazon S3.</br>
</br><strong>Methodology:</strong>
</br>Data Extraction: Use AWS Glue Crawlers to catalog the source data in Amazon S3.
</br>Data Cleaning:
</br>Duplicate Removal: Identify and remove duplicates.
</br>Handling Missing Values: Implement strategies to manage incomplete data.
</br>Standardization: Ensure data formats are consistent.
</br>Data Transformation:
</br>Field Derivation: Create new fields for analysis.
</br>Normalization: Standardize data values and structures.
</br>Data Loading: Store the cleaned and transformed data back into Amazon S3.</br>
</br><strong>Tools and Technologies:</strong>
 </br> - AWS Glue for data cleaning and transformation.
 </br> - Amazon S3 for storing the structured dataset.</br>
</br><strong>Deliverables:</strong>
 </br>Cleaned and structured dataset in Amazon S3.
 </br>ETL Pipeline Documentation: Process flow, scripts, and data quality report.</br>
</br></br> <strong> </strong> Ensuring Data Quality Control with AWS Glue and Amazon S3 </strong></br>
</br><strong>Project Description:</strong> This project involves implementing data quality control rules on council voting records using AWS Glue.</br>
</br><strong>Project Title:</strong> "Ensuring Data Quality in Council Voting Records Using AWS Glue"</br>
</br><strong>Objective:</strong>To establish and enforce data quality control measures using AWS Glue to ensure data accuracy.</br>
</br><strong>Background:</strong>The necessity of highquality data in council voting records for accurate analysis and reporting.</br>
</br><strong>Scope:</strong> Data Cleansing,Transformation and Validation for council voting records.</br>
</br><strong>Methodology:</strong>
AWS Glue service is used to implement ETL pipleine for data quality rules and the completeness rule on the "Member Vote" for threshold >95% using AWS Glue. Then data is routed with conditional router rules and stored in the Amazon S3 trusted zone.
</br><strong>Tools and Technologies:</strong>
</br> - Useing AWS Glue for data cleansing and validation.
</br> - Using Amazon S3 for storing validated datasets.</br>
</br><strong>Deliverables:</strong>
</br> To store the validated dataset in the Trusted Zone.
</br></br><h2> DAP for UCW Academic Integrity Procedure</h2></br>
</br>This project involves implementing Data Analytic platform for ademic integrity procedure for academic department of University Canada West (UCW). The purpose of doing the analysis is to improve the performance of academic integrity procedure for academic department of University Canada West (UCW) using AWS Cloud services such as explore the patterns, check data quality, descriptive analysis and to extract, transform and load the academic case records.
</br>Attached is the data pipeline design for DAP for the Academic Integrity Procedure.
</br>Below is the data pipeline design for DAP for Academic Integrity procedure for UCW.
</br>![image](https://github.com/user-attachments/assets/87bff4f3-e79d-4755-8078-c90e560c7a08)
</br>![image](https://github.com/user-attachments/assets/11aaa4a5-b1a3-4f55-957f-e1fdaf16495f)
</br></br><strong> Exploratory Data Analysis for UCW Academic Integrity Using Amazon Athena</strong></br>
</br><strong>Project Description:</strong> This project involves analyzing academic integrity records to uncover patterns using Amazon Athena for querying data stored in Amazon S3.</br>
</br><strong>Project Title:</strong> "Exploring Academic Integrity Patterns with Amazon Athena"</br>
</br><strong>Objective:</strong> To perform an exploratory data analysis on academic integrity cases using Amazon Athena, identifying trends and patterns.</br>
</br><strong>Dataset:</strong> UCW Academic Integrity Records stored in Amazon S3.</br>
</br><strong>Methodology:</strong>
</br> - Using Amazon Athena to run SQL queries for summarizing data and generating descriptive statistics.
</br> - Using excel to explore the dataset to understand academic integrity trends.
</br><strong>Tools and Technologies:</strong>
</br> - Using Amazon Athena for data querying and analysis.
</br> - Using Excel to generate the bar chart graph for Number of reported cases for year 2023 and 2024.
</br><strong>Deliverables:</strong>
</br>A report generated from Athena queries summarizing insights into academic integrity patterns.</br>
</br></br><strong> Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena</strong></br>
</br><strong>Project Description:</strong> This project involves comprehensive descriptive analysis of academic integrity outcomes using Amazon Athena.</br>
</br><strong>Project Title:</strong> "Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena"</br>
</br><strong>Objective:</strong>To leverage Amazon Athena for performing descriptive analysis on academic integrity cases, providing insights into patterns and outcomes.</br>
</br><strong>Dataset:</strong> UCW Academic Integrity Records from Amazon S3.</br>
</br><strong>Methodology:</strong>
</br>Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
</br>Data Analysis:
</br>Query Execution: Write and execute SQL queries to extract metrics.
</br>Insight Generation: Analyze outcomes and trends.
</br>Data Aggregation:
</br>Metric Calculation: Aggregate data to calculate key metrics.
</br>Statistical Summaries: Generate summaries and visualizations.
</br><strong>Tools and Technologies:</strong>
</br> - Amazon Athena for querying and analysis.
</br> - Amazon S3 for storing academic integrity datasets.
</br><strong>Deliverables:</strong>
</br>Analysis Report: Aggregated data and statistical insights.
</br>Visualizations: Charts and graphs illustrating findings.
</br>Query Documentation: SQL queries and process overview.</br>
</br></br><strong> ETL Pipeline for UCW Academic Integrity Records with AWS Glue</strong></br>
</br><strong>Project Description:</strong> This project involves designing an ETL pipeline to extract, transform and load academic integrity records using AWS Glue.</br>
</br><strong>Project Title:</strong> "Data Wrangling for Academic Integrity Records Using AWS Glue"</br>
</br><strong>Objective:</strong>To design and implement an ETL pipeline using AWS Glue to clean, transform, and prepare academic integrity records.</br>
</br><strong>Background:</strong> Ensuring data consistency and accuracy in academic integrity records for meaningful analysis.</br>
</br><strong>Dataset:</strong> UCW Academic Integrity Records stored in Amazon S3.</br>
</br><strong>Methodology:</strong>
</br>First step is using AWS Glue Databrew to extract data in Amazon S3. Then, using glue 
</br>Handling Missing Values: Implement strategies for incomplete data.
</br>Standardization: Ensure consistent data formats.
</br>Data Transformation:
</br>Field Derivation: Create metrics for analysis.
</br>Normalization: Standardize values and structures.
</br>Finally, data is stored in the S3 Bucket "Raw Zone".</br>
</br><strong>Tools and Technologies:</strong>
</br> - AWS Glue for data cleaning and transformation.
</br> - Amazon S3 for storing structured datasets.</br>
</br><strong>Deliverables:</strong>
</br>Cleaned dataset in Amazon S3.
</br>ETL Pipeline Documentation: Process details and scripts.
</br>Data Quality Report: Summary of quality improvements.</br>
</br></br><strong> Ensuring Data Quality Control for UCW Academic Integrity with AWS Glue and Amazon S3</strong></br>
</br><strong>Project Description:</strong> This project focuses on implementing data quality check rules on academic integrity data using AWS Glue.</br>
</br><strong>Project Title:</strong>"Ensuring Data Quality in Academic Integrity Records Using AWS Glue"</br>
</br><strong>Objective:</strong>To establish and enforce data quality control measures using AWS Glue for academic integrity records.</br>
</br><strong>Background:</strong> Ensuring high quality and error-free data in academic integrity records for accurate analysis.</br>
</br><strong>Scope:</strong>strong> Data Profiling, Cleansing, and Validation for academic integrity records.</br>
</br><strong>Methodology:</strong>
</br> AWS Glue service is used to implement ETL pipleine for data quality rules and the completeness rule on the "incident vote" for threshold >95% using AWS Glue. 
</br><strong>Tools and Technologies:</strong>
</br> - AWS Glue for data cleansing, implementing quality rules for validation.
</br> - Amazon S3 for storing validated datasets under Trusted zone.</br>
</br><strong>Deliverables:</strong>
</br> To create a error free and validated dataset in the Trusted Zone under Amazon S3 Bucket.

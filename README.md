# DATA-ANALYST-JOB-POSTINGS-ANALYSIS

# Introduction
This project is focused on analyzing job market data to derive valuable insights using SQL queries. The dataset used in this analysis is from a database named "job" and contains information about various job postings, including attributes such as company name, job title, job posting platform, salary-related information, and work from home availability. The primary objective of this project is to answer several key questions related to the job market, such as identifying the companies with the most Data Analyst job postings, finding salary-related attributes for a specific company with the highest job postings, determining the most common job posting platforms, and calculating the number of companies allowing work from home.

# Objectives:
1. Identify the Company with the Highest Number of Data Analyst Job Postings: This analysis aims to determine the company that has the most job postings for the position of Data Analyst. The query considers only job titles containing "Data Analyst."

2. Find Salary-Related Attributes for the Top Company: The goal is to extract salary-related attributes for the company with the highest Data Analyst job postings and sort them by the highest average salary. The query ensures that null or 'none' values are excluded.

3. Determine the Most Common Job Posting Platforms: This analysis identifies the two most common platforms used by companies to list job postings. It provides a count of job postings on each platform.

4. Calculate the Number of Companies Allowing Work From Home: This query counts the distinct companies that offer work-from-home options to their employees.

5. Analyze Job Postings of the Big 4 Firms: The final objective is to count the job postings for the four major accounting firms (KPMG, Amazon, EY, and Deloitte) across different job posting platforms.


# Procedure:
1. The project begins by loading the necessary Python libraries (NumPy, Pandas) and defining a database connection engine.

2. The dataset, named "gsearch_jobs," is read into a Pandas DataFrame, and its basic information is displayed.

3. SQL queries are executed to achieve the project objectives, which involve filtering, grouping, counting, and ordering data based on specific criteria.

4. The results of each query are displayed, providing the desired insights and answers to the project's key questions.

5. The project follows a structured approach, starting with identifying the company with the highest Data Analyst job postings and progressing to other job market insights, concluding with an analysis of job postings by the Big 4 firms.

6. The project utilizes SQL's capabilities to extract, transform, and present data in a meaningful format, making it useful for job market analysis and decision-making.

# Conclusion:
This project leverages SQL queries to extract valuable insights from the job market dataset. It reveals which companies are actively hiring Data Analysts, provides insights into salary attributes for the top company, identifies popular job posting platforms, and quantifies the number of companies offering work-from-home opportunities. Additionally, it offers an overview of job postings from the Big 4 accounting firms across various platforms. These insights can be valuable for job seekers, companies, and analysts interested in the job market trends.

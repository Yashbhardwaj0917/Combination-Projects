# Analyst Job Web Scrape

## Introduction

This project focuses on data related to Data Analyst jobs, comprising two parts: web scraping using Python and data exploration/cleaning using SQL. Additionally, a Word Cloud visualization is included. The primary goal is to gain insights into the Data Analyst job market.

### Project Overview

This project is divided into the following sections:

1. **Web Scraping in Python:** In this part, a job posting portal, [ai-jobs.net](https://ai-jobs.net), is scraped for Data Analyst jobs using BeautifulSoup. The following details are extracted from the website:
    - Job Title
    - Company Name
    - Location
    - Level (Junior, Mid, Senior)
    - Job Type (Full-time, Internship)
    - Salary Range
    - Required Skills
    - Benefits

2. **Exploration/Cleaning in SQL:** The SQL portion of the project explores and cleans the scraped data. It includes SQL queries to:
    - Check the data.
    - Identify distinct job levels.
    - Group salary ranges by job levels.
    - Determine if jobs are onsite or remote based on location.
    - Remove non-alphanumeric characters from necessary columns (Skills and Benefits).

### Getting Started

To use this project, follow these steps:

1. Clone the repository to your local machine:

2. Install the required libraries specified in the Jupyter Notebooks.

3. Run the "Web Scraping in Python" notebook to scrape Data Analyst job data from [ai-jobs.net](https://ai-jobs.net).

4. Run the SQL queries in your preferred SQL environment to explore and clean the data.

5. Customize the SQL queries as needed for your analysis.

6. Utilize the cleaned data for further analysis or visualization.

### Note

Ensure you have Python, Jupyter Notebook, and a SQL database installed to run this project successfully.

This project provides valuable insights into the Data Analyst job market and serves as a practical example of web scraping and data cleaning.


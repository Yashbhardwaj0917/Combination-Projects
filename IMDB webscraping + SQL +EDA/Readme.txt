# MySQL Queries with Pandas and Visualization

This project involves querying a MySQL database containing data related to the top 250 movies and performing data analysis and visualization using Python with Pandas, NumPy, Matplotlib, Seaborn, and MySQL Connector. The project answers various questions about the movies and explores their genres, directors, and box office performance.

## Table of Contents

1. [Introduction](#introduction)
2. [MySQL Queries](#mysql-queries)
3. [Data Analysis with Pandas](#data-analysis-with-pandas)
4. [Data Visualization](#data-visualization)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

The goal of this project is to demonstrate the power of combining SQL and Python for data analysis and visualization. It involves the following steps:

1. Connecting to a MySQL database containing data on the top 250 movies.
2. Executing SQL queries to answer specific questions about the movies.
3. Loading the query results into Pandas DataFrames for further analysis.
4. Exploring the data, including genres, directors, and box office performance.
5. Visualizing the data using various Python libraries.

## MySQL Queries

The project begins with executing SQL queries to retrieve relevant data from the MySQL database. The queries answer questions such as:

- How many movies were made each year over the past 30 years?
- List all directors who directed a 'Drama' movie.
- How many directors have directed a movie more than twice?
- What is the average rating of the Star Wars movie series?
- What is the highest-rated movie in the Lord of the Rings sequel?
- List the top 10 highest-grossing movies with their ratings and release years.
- Find movies made between 1950 and 1960, including their gross total, number of reviews, and ratings.

## Data Analysis with Pandas

Once the SQL queries are executed, the project proceeds with data analysis using Pandas. Key tasks include:

- Loading data from the MySQL query results into Pandas DataFrames.
- Exploring the data, including genres, actors, and directors.
- Calculating statistics, such as the total number of movies by genre, directors with the most movies, and directors with the highest-grossing movies.
- Combining and cleaning data for analysis and visualization.

## Data Visualization

The final part of the project focuses on data visualization using Matplotlib and Seaborn. Visualization tasks include:

- Creating bar charts to visualize the distribution of movie genres and box office totals by genre.
- Generating scatter plots to explore the relationship between box office totals and movie ratings.
- Visualizing the top 20 directors by the number of movies and by their movies' gross total.
- Plotting a line chart to show the total number of movies by release year.

## Installation

To run this project, you'll need the following dependencies:

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- MySQL Connector

You can install the required Python packages using pip:

## Usage
1. Clone this repository to your local machine:

2. Ensure you have a MySQL database set up with the necessary tables and data.

3. Update the MySQL connection parameters in the code to match your database configuration.

4. Execute the Jupyter Notebook or Python script to run the SQL queries, analyze the data with Pandas, and create visualizations.

5. Customize the code and queries for your specific analysis or questions.

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or additional features to add to this project, please create a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


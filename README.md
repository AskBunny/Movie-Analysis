# Movie-Analysis

## Introduction

- Understand the trend in average ratings for different movie genres over years (from 1975 to 2016) and Correlation between the trends for different genres (8 different genres are considered:
Animation, Comedy, Romance, Thriller, Horror, Sci-Fi and Musical).

- This will give us an insight about how the people’s liking for the different movie genres change over time and about the strength of association between trends in between different movie genres,
insights possibly useful for the critics.

## Method

### Approaches

- Downloading CSV files directly from the available source like Kaggle, GitHub.

- Getting data using API

### Data Source

- IMDB’s API

- movie_metadata.csv

### Flow Diagram

This is the flow diagram of the project. First, we’ve decided on the website for analysis which is IMDB.

There are certain steps that we have followed

- After deciding the website, we have used Jupyter notebook IDE and API for data extraction

- Some part of data downloaded in CSV format and some part of data is called using API and the library which we have used in python is requested.

- The called data is in HTML form and we have converted that into JSON using JSON library in python

- Now, the JSON data is further extracted to use it for analysis using python functions.

- Final step is the analysis and visualization, for that we’ve used tableau.

### Resources Required for the Project

The below mentioned are the tools and resources required to complete the project

- Language used: Python

- Libraries (Python) used:

  o JSON: JavaScript Object Notation is a format for structuring data, mainly used for storing and it’s a custom bases library in python
  
  o and transferring data between the browser and the server.

  o Openpyxl: It is for reading and writing Excel (with extension xlsx/xlsm/xltx/xltm) files.

  o Requests: The requests module allows sending HTTP requests using Python.

- Interpreter: Jupyter Notebook

- Visualization: Tableau

- Software: Microsoft Excel, Slack, Word

## List of Analysis

To understand trend in average ratings for different movie genres over years (from 1975 to 2016) and Correlation between the trends for different genres and insight about how the people’s liking for the
different movie genres change over time, we’ve performed below mentioned analysis

1) Overall Distribution by Country

2) Distribution of Movies by Genre & Avg Duration

3) Top 5 genres Analysis

  a) Total Movies Count for Top 5 Genres

  b) Top 5 Genres IMDB Score vs Revenue vs Budget

4) Top 10 Movies Detail Analysis

  a) Top 10 Highest Grossing Movies

  b) Top 10 Highest Grossing Color and B/W Movies

5) 250 Movies Information

  a) Number of blockbuster movies in last three decades

  b) Top Movies Trend Distribution

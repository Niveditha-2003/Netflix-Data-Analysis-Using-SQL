# Netflix-Data-Analysis-Using-SQL


##Introduction

This project analyzes Netflix's content library using SQL to gain insights into various aspects such as content type distribution, rating trends, genre classification, and regional content availability. The dataset includes information on movies and TV shows available on Netflix, including details like release year, duration, country, director, and description.

##Dataset Information

The dataset contains the following columns:

show_id

type (Movie or TV Show)

title

director

casts

country

date_added

release_year

rating

duration

listed_in (Genres)

description


##Business Problems Solved

Count the number of movies vs TV shows

Identify the most common ratings

List movies released in a specific year

Find the top 5 countries with the most content

Identify the longest movie

Find content added in the last 5 years

List movies and TV shows by a specific director

Identify TV shows with more than 5 seasons

Count content items in each genre

Analyze India's content release trends

List all documentary movies

Identify content without a director

Find movies featuring specific actors in the last 10 years

Identify the top 10 actors appearing in the most Indian movies

Categorize content based on keywords like kill and violence


##SQL Techniques Used

Aggregate functions like count and max

String functions like string_to_array and split_part

Window functions like rank() over()

Date functions like to_date() and extract()

Filtering with where and ilike


##How to Use

1. Load the dataset into a SQL database


2. Run the provided queries to extract insights


3. Modify the queries to explore additional patterns



##Tools Used

PostgreSQL for SQL queries and analysis

Data manipulation and extraction using SQL functions


Conclusion

This project provides key insights into Netflix’s content distribution and trends using SQL. The queries help understand content availability, genre trends, and actor participation, making it useful for business and entertainment analytics.

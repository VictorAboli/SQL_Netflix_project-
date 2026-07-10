# SQL Netflix Movie and TV Shows project Data Analysis

## Project Overview

This project focuses on analyzing Netflix's content catalog to identify trends, patterns, and business insights using SQL.

The objective of this analysis is to explore Netflix movies and TV shows, understand content distribution across countries and genres, analyze ratings, identify popular contributors, and solve real-world business questions using SQL techniques.

This project demonstrates data transformation, aggregation, and analytical skills required for a Data Analyst role.

---

# Business Problem

Netflix contains thousands of movies and TV shows across different countries, genres, ratings, and release years. 

The goal of this project is to answer important business questions such as:

1. Count the number of Movies vs TV Shows
2. Find the most common rating for movies and TV shows
3. List all movies released in a specific year (e.g., 2020)
4. Find the top 5 countries with the most content on Netflix
5. Identify the longest movie
6. Find content added in the last 5 years
7. Find all the movies/TV shows by director 'Rajiv Chilaka'!
8. List all TV shows with more than 5 seasons
9. Count the number of content items in each genre
10. Find each year and the average numbers of content release in India on Netflix. return top 5 year with highest avg content release!
11. List all movies that are documentaries
12. Find all content without a director
13. Find how many movies actor 'Salman Khan' appeared in last 10 years!
14. Find the top 10 actors who have appeared in the highest number of movies produced in India.
15. Categorize the content based on the presence of the keywords 'kill' and 'violence' inthe description field. Label content containing these keywords as 'Bad' and all other content as 'Good'. Count how many items fall into each category.
---

# Dataset Information

**Dataset Name:** Netflix Titles Dataset

**Source:** Kaggle - Netflix Movies and TV Shows Dataset

The dataset contains information about Netflix titles including:

| Column | Description |
|---|---|
| show_id | Unique identifier for each title |
| type | Content type (Movie/TV Show) |
| title | Name of the content |
| director | Director information |
| cast | Actors appearing in the title |
| country | Country of production |
| date_added | Date added to Netflix |
| release_year | Original release year |
| rating | Content rating |
| duration | Movie length or TV show seasons |
| listed_in | Genre/category |
| description | Content summary |

---

# Tools & Technologies Used

### Database
- Microsoft SQL Server

### Programming Language
- SQL

### SQL Concepts Used

- SELECT statements
- Filtering using WHERE
- Aggregations
    - COUNT()
    - GROUP BY
    - ORDER BY
- Window Functions
    - RANK()
    - PARTITION BY
- String Functions
    - STRING_SPLIT()
    - TRIM()
    - LEFT()
    - CHARINDEX()
- Conditional Logic
    - CASE WHEN
- Subqueries
- Data Type Conversion
    - TRY_CAST()

# Key Insights

Based on the analysis:

- Netflix contains significantly more Movies compared to TV Shows.
- Mature audience ratings represent a large portion of Netflix content.
- The United States is one of the largest contributors of Netflix titles.
- India represents a significant international content market.
- Genre and country fields require transformation because of multiple values stored in a single column.
- SQL string functions are essential for analyzing real-world datasets.

Netflix-SQL-Analysis/
│
├── Dataset/
│ └── netflix_titles.csv
│
├── SQL Queries/
│ └── netflix_analysis.sql
│
├── Documentation/
│ └── Netflix_Project_Report.docx
│
└── README.md




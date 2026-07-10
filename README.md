# SQL Netflix Movie and TV Shows project Data Analysis

## Project Overview

This project focuses on analyzing Netflix's content catalog to identify trends, patterns, and business insights using SQL.

The objective of this analysis is to explore Netflix movies and TV shows, understand content distribution across countries and genres, analyze ratings, identify popular contributors, and solve real-world business questions using SQL techniques.

This project demonstrates data cleaning, transformation, aggregation, and analytical skills required for a Data Analyst role.

---

# Business Problem

Netflix contains thousands of movies and TV shows across different countries, genres, ratings, and release years. 

The goal of this project is to answer important business questions such as:

- How many movies and TV shows are available on Netflix?
- What are the most common ratings across different content types?
- Which countries contribute the most Netflix content?
- Which genres dominate Netflix's catalog?
- Which actors and directors contribute the most content?
- How has Netflix content changed over time?

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




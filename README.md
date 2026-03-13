# Spotify Streaming Intelligence Analysis

## Project Overview

This project performs an end-to-end data analytics workflow on Spotify streaming data to uncover insights about music popularity, genre trends, user subscription behavior, and streaming distribution across countries.

The analysis integrates multiple tools commonly used in the data analytics industry, including Excel for data preparation, SQL for querying and aggregation, Python for exploratory data analysis (EDA), and Power BI for interactive dashboard development.

The objective of the project is to demonstrate how raw music streaming data can be transformed into meaningful insights that support data-driven decision-making.


## Business Problem

Music streaming platforms need to understand:

* Which genres attract the most listeners
* What factors influence song popularity
* Which countries generate the highest streaming activity
* How subscription plans impact revenue
* The relationship between song popularity and streaming counts

This project analyzes these questions using real-world data analytics techniques.


## Tools & Technologies Used

| Tool                                 | Purpose                                                       |
| ------------------------------------ | ------------------------------------------------------------- |
| Excel                                | Data cleaning and preprocessing                               |
| SQL                                  | Data querying, aggregation, and business analysis             |
| Python (Pandas, Matplotlib, Seaborn) | Exploratory Data Analysis and visualization                   |
| Power BI                             | Interactive dashboard and business intelligence visualization |
| GitHub                               | Project documentation and version control                     |


## Dataset Description

The dataset contains information about **5000 songs** including audio characteristics, popularity metrics, streaming counts, and user subscription information.

### Key Features

* `track_id` – Unique song identifier
* `track_name` – Song title
* `artist` – Artist name
* `genre` – Music genre category
* `danceability` – Danceability score of the song
* `energy` – Energy intensity level
* `tempo` – Beats per minute (BPM)
* `loudness` – Loudness level of the track
* `valence` – Musical positivity score
* `duration_ms` – Song duration in milliseconds
* `popularity` – Spotify popularity score
* `streams` – Total number of streams
* `country` – Listener country
* `subscription_plan` – Free or Premium user
* `payment_method` – Payment method used by subscribers
* `revenue_usd` – Revenue generated


## Project Workflow

### 1. Data Cleaning (Excel)

Initial preprocessing and cleaning were performed in Excel:

* Removed duplicate records
* Checked for missing values
* Standardized column formats
* Converted duration values
* Created cleaned dataset for analysis


### 2. SQL Data Analysis

SQL was used to perform business-focused queries and aggregations.

Key analyses included:

* Average popularity by genre
* Total streams by country
* Revenue by subscription plan
* Top streamed songs
* Song distribution by popularity category
* Average song duration by genre
* Payment method distribution
* Average revenue per premium user


### 3. Python Exploratory Data Analysis

Python was used to perform deeper statistical analysis and data visualization.

Libraries used:

* Pandas
* Matplotlib
* Seaborn

Key tasks:

* Dataset inspection
* Missing value analysis
* Correlation analysis between audio features
* Distribution visualization
* Feature relationship exploration

Example Python code:


### 4. Power BI Dashboard

An interactive dashboard was developed in Power BI to visualize the insights and allow dynamic exploration of the dataset.

### Dashboard Features

Key Performance Indicators:

* Total Streams
* Total Revenue
* Total Songs

Interactive Filters:

* Genre
* Country
* Subscription Plan
* Payment Method

Visualizations Included:

* Total Streams by Country
* User Distribution by Subscription Plan
* Average Song Popularity by Genre
* Top 10 Most Streamed Songs
* Popularity vs Streams Relationship (Scatter Plot)
* Number of Songs by Genre


## Power BI Dashboard Preview



## Key Insights

* Certain genres consistently show higher average popularity scores.
* Streaming activity varies significantly across different countries.
* Premium users contribute significantly to platform revenue.
* Song popularity shows a measurable relationship with streaming counts.
* Some genres produce a larger number of songs but not necessarily higher streams.


## Project Structure

```
Spotify-Streaming-Intelligence-Analysis
│
├── data
│   └── spotify_cleaned_dataset.csv
│
├── excel
│   └── spotify_analysis.xlsx
│
├── sql
│   └── spotify_queries.sql
│
├── python
│   └── spotify_analysis.ipynb
│
├── powerbi
│   └── spotify_dashboard.pbix
│
├── images
│   └── dashboard_preview.png
│
└── README.md
```


## Learning Outcomes

Through this project I developed practical experience in:

* Data cleaning and preprocessing
* Writing analytical SQL queries
* Performing exploratory data analysis with Python
* Building interactive dashboards with Power BI
* Communicating insights through data visualization


## Future Improvements

Potential future enhancements include:

* Time-series analysis of streaming trends
* Machine learning models for popularity prediction
* Advanced feature engineering using audio characteristics
* Deployment of interactive dashboards for real-time analytics


## Author

Nagendra V Sagar

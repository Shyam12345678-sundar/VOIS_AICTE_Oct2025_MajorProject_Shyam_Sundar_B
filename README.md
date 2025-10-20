🎯 Project Title

Netflix Data Analysis

🧩 Introduction

This project analyzes the Netflix dataset, which contains information about Movies and TV Shows available on the platform between 2008 and 2021. The dataset includes 7,789 records and 11 attributes, providing rich details such as title, director, cast, country, release date, rating, duration, and genre type.

The goal of this project is to explore content trends, country-wise distributions, and popular genres to identify strategic insights into Netflix’s global content strategy.

🧠 Problem Statement

Netflix is one of the largest global OTT platforms, offering a diverse range of movies and TV shows. With increasing competition from platforms like Amazon Prime Video, Disney+, and regional streaming services, Netflix needs to understand:

How its content library has evolved over time,

Which countries and genres dominate, and

What trends can guide future content strategy.

This project focuses on analyzing Netflix’s content catalog to uncover such patterns and insights.

📊 Dataset Information

File: netflix_titles.csv Total Records: 7,789 Columns (Attributes):

Show_Id

Category (Movie / TV Show)

Title

Director

Cast

Country

Release_Date

Rating

Duration

Type (Genre)

Description

⚙ Steps Performed

1️⃣ Data Loading

Loaded the dataset using Pandas.

Displayed basic structure, column names, and first few records.

2️⃣ Data Cleaning

Removed duplicate records.

Handled missing values in key columns (Director, Cast, Country, Rating, Duration).

Extracted release year from Release_Date column.

Created a clean dataset (netflix_cleaned.csv).

3️⃣ Exploratory Data Analysis (EDA)

Visualizations created using Matplotlib and Seaborn:

📈 Movies vs TV Shows Over the Years

🌍 Top 10 Countries by Number of Titles

🎭 Top 10 Genres on Netflix

⭐ Ratings Distribution

☁ Word Cloud of Descriptions

🧩 Libraries Used

pandas numpy matplotlib seaborn wordcloud

💡 Key Insights (So Far)

Netflix’s content has grown significantly between 2008 and 2021.

Movies dominate the catalog compared to TV Shows.

The United States and India are among the top content-producing countries.

Popular genres include Drama, Comedy, and Documentaries.

Ratings vary across countries, showing Netflix’s focus on diverse audiences.

🧾 Output

A cleaned dataset (netflix_cleaned.csv).

Multiple visualizations explaining Netflix’s content trends.

Insights that help understand Netflix’s global expansion strategy.

🚀 Future Scope

Build an interactive dashboard using Plotly or Power BI.

Perform genre-based popularity prediction using machine learning.

Explore content diversity and inclusion metrics (country/genre balance).

👨‍💻 Author

Shyam Sundar B

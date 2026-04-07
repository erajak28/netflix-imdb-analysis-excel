## 📌 Overview
This project analyzes movie and TV shows data over the last 50 years using Excel. 

The project includes data cleaning, handling missing values, and creating new derived columns to improve analysis. Using this refined dataset, trends in ratings, audience engagement, runtime, and content characteristics were explored through pivot tables and interactive dashboards.
![Dashboard](https://github.com/user-attachments/assets/0f617788-013b-40ab-9949-b4e07bb91c77)
  
## 🛠️ Tools Used

- Microsoft Excel  
- Pivot Tables & Pivot Charts  
- Data Cleaning & Transformation  
- Dashboard Design

## 📊 Dataset Information
- Source: Netflix Movies & TV Shows dataset enriched with IMDb data
- Time Period: 1953 – 2022
- Content Types: Movies and TV Shows

### Key Columns Used
- `id` – Unique identifier for each title  
- `title` – Name of the movie or TV show  
- `type` – Movie or TV Show  
- `release_year` – Year of release  
- `age_certification` – Audience age rating (PG, PG-13, R, TV-MA, etc.)  
- `runtime` – Duration in minutes  
- `imdb_score` – Average IMDb rating  
- `imdb_votes` – Number of IMDb votes  

## 🧹 Data Cleaning & Preparation

- Handled missing values in age certification by categorizing them as "Not Rated."
- Cleaned and standardized text fields (titles), Removed Unwanted Characters and symbols.
- Created new columns:
  - `Last_50_Years` → to filter the relevant time period of 50 years.
  - `age_certification_clean` → for better categorization
  - `votes_category` → to differentiate popular vs non-popular content.
- Removed inconsistencies to ensure accurate analysis
  
## 📊 Key Analysis Performed

- Identified top-rated movies and TV shows
- Analyzed content distribution over time
- Studied IMDb rating trends
- Examined audience engagement (votes)
- Evaluated runtime patterns
- Analyzed impact of age certification on ratings.

## 📈 Key Insights
- Content production has increased significantly in recent years
- IMDb ratings have slightly declined over time
- Audience engagement has grown rapidly
- Movie runtime has remained consistent
- Broader audience content tends to have higher ratings

## 🚀 Conclusion

This project demonstrates end-to-end data analysis using Excel, including data cleaning, feature engineering, visualization, and insight generation. It highlights how raw data can be transformed into meaningful insights through structured analysis.

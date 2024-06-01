
# <h1 align="center" style="color:blue;" id="heading">DSC540 Data Preparation</h1>
# <h1 align="center" style="color:blue;" id="heading">Final Project</h1>

![GitHub contributors](https://img.shields.io/github/contributors/saboye/DSC540-Data-Preparation?color=blue&logo=github&style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/saboye/DSC540-Data-Preparation?logo=github&style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues-raw/saboye/DSC540-Data-Preparation?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/saboye/DSC540-Data-Preparation?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/saboye/DSC540-Data-Preparation?style=for-the-badge)
![Bellevue University](https://img.shields.io/badge/Bellevue%20University-blue?style=for-the-badge&logo=university)


## Project Overview

This project aims to analyze and uncover factors contributing to movies' commercial success and audience reception by integrating and examining data from The Movie Database (TMDB), The Open Movie Database (OMDb) API, and IMDb. The analysis leverages detailed movie credits, financial metrics, audience ratings, and other relevant data to provide insights into industry trends, patterns, and predictors of movie performance.

### Data Sources

### 1. TMDB Movie Metadata
- **Description:** Detailed information on movie credits and various movie attributes, including cast, crew, budgets, revenues, genres, and more.
- **Link:** [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

### 2. OMDb API
- **Description:** RESTful web service providing detailed data, including titles, year, ratings, plot descriptions, and poster images for movies and TV series. The OMDb API was used to expand the dataset using movie titles extracted from the TMDB dataset.
- **Link:** [OMDb API](https://www.omdbapi.com/)

### 3. IMDb
- **Description:** Comprehensive database and ratings for movies, TV shows, and celebrities. Source for movie ratings, reviews, and detailed cast and crew information.
- **Link:** [IMDb](https://datasets.imdbws.com/)

## Project Approach

1. **Data Cleaning and Preprocessing:** Ensuring consistency and accuracy in movie titles, handling missing values, and resolving discrepancies in movie identifiers across the datasets.
2. **Data Integration:** Merging datasets on the common key of movie titles to create a unified dataset.
3. **Database Management:** Loading the cleaned and merged dataset into an SQLite database to facilitate efficient querying and analysis.

## Visualizations

1. **Detailed Histogram of Movie Budgets**
2. **Distribution of Vote Averages**
3. **Count of Movies by Original Language**
4. **Pie Chart of Movie Status**
5. **Bar Plot of Revenue by Genre**
6. **Total Revenue Over the Years**
7. **Count of Movies Released Each Year**
8. **Count of Movies by Decade**
9. **Revenue by Genre**
10. **Scatter Plot of Budget vs. Revenue**
11. **Heatmap of Genre vs. Status**
12. **Top 10 Production Companies**
13. **Pairplot of Budget, Revenue, Popularity, and Vote Average**

## Key Takeaways: Data Preparation from Different Sources

1. **Data Integration:** Successfully combining data from flat files, APIs, and web scraping requires careful planning and execution. Ensuring consistency across different datasets is crucial for accurate analysis.
2. **Handling Missing Values:** Managing missing data is a critical step in preparing datasets for analysis. Techniques such as imputation or exclusion must be applied based on the context and availability of data.
3. **Standardization:** Standardizing data formats, such as date formats and numerical values, ensures uniformity and reduces the risk of errors during the merging process.
4. **Data Cleaning:** Identifying and correcting discrepancies, such as duplicate entries or inconsistent naming conventions, is essential for creating a reliable and cohesive dataset.
5. **Merging Strategies:** Choosing appropriate keys for merging datasets, such as movie titles or unique identifiers, is vital. Ensuring these keys are clean and standardized across datasets facilitates successful integration.
6. **Ethical Considerations:** Throughout the data preparation process, ethical considerations such as data privacy, bias, and representation must be taken into account to ensure responsible and fair analysis.

## References

1. **TMDB Movie Metadata**  
   Description: The provided flat files `tmdb_5000_credits.csv` and `tmdb_5000_movies.csv` contain detailed information on movie credits and various movie attributes from TMDB.  
   Link: [TMDB Movie Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

2. **OMDb API**  
   Description: The OMDb API (The Open Movie Database) is a RESTful web service for obtaining movie information. It offers detailed data, including titles, year, ratings, plot descriptions, and poster images for movies and TV series. In this project, movie titles extracted from the `tmdb_5000_credits.csv` file were used as search queries for the OMDb API to expand the dataset.  
   Link: [OMDb API](https://www.omdbapi.com/)

3. **IMDb**  
   Description: IMDb (Internet Movie Database) offers a comprehensive database and ratings for movies, TV shows, and celebrities. It's a crucial source for movie ratings, reviews, and detailed cast and crew information.  
   Link: [IMDb](https://datasets.imdbws.com/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


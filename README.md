# DSC540 Data Preparation

![GitHub contributors](https://img.shields.io/github/contributors/saboye/DSC540-Data-Preparation?color=blue&logo=github&style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/saboye/DSC540-Data-Preparation?logo=github&style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues-raw/saboye/DSC540-Data-Preparation?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/saboye/DSC540-Data-Preparation?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/saboye/DSC540-Data-Preparation?style=for-the-badge)

## Project Overview

This project aims to prepare and analyze movie data from various sources, including flat files, APIs, and web data. The final goal is to merge the datasets, load them into a SQLite database, and create visualizations to uncover insights about the movie industry.

## Data Sources

### Flat File
- **Description**: Contains detailed information on movie credits and various movie attributes from The Movie Database (TMDB).
- **Files**: `tmdb_5000_credits.csv`, `tmdb_5000_movies.csv`

### API
- **Description**: The OMDb API provides detailed data on movies and TV series.
- **Link**: [OMDb API](https://www.omdbapi.com/)

### Website
- **Description**: IMDb offers comprehensive data and ratings for movies, TV shows, and celebrities.
- **Link**: [IMDb](https://www.imdb.com/)

## Project Approach

1. **Data Cleaning and Preprocessing**: Standardize movie titles, handle missing values, and resolve discrepancies.
2. **Data Integration**: Merge datasets on common keys (e.g., movie titles, IMDb IDs) to create a unified dataset.
3. **Analysis**: Conduct exploratory data analysis (EDA) to identify trends, patterns, and outliers.
4. **Modeling** (if applicable): Apply statistical or machine learning models to predict movie success metrics.

## Visualizations

1. **Detailed Histogram of Movie Budgets**
2. **Distribution of Vote Averages**
3. **Count of Movies by Original Language**
4. **Pie Chart of Movie Status**
5. **Bar Plot of Revenue by Genre**
6. **Total Revenue Over the Years**
7. **Count of Movies Released Each Year**

## Key Takeaways

1. **Data Preparation**: Combining data from flat files, APIs, and web data requires careful preprocessing and cleaning.
2. **Integration Challenges**: Ensuring consistency across datasets is crucial for accurate analysis.
3. **Visualization**: Effective visualizations help uncover insights and trends in the data.

## Ethical Considerations

1. **Privacy Concerns**: Handle individual data responsibly, respecting privacy.
2. **Bias and Representation**: Be aware of inherent biases in the data.
3. **Impact on Perception**: Ensure a balanced and fair approach to data analysis.

## References

- TMDB Movie Metadata. Retrieved from [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- OMDb API. Retrieved from [OMDb](https://www.omdbapi.com/)
- IMDb. Retrieved from [IMDb](https://www.imdb.com/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


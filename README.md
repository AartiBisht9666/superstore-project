 Netflix_Titles-project



## Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Netflix Titles dataset to uncover patterns, trends, and insights related to content distribution, release years, genres, countries, ratings, and content growth over time.

The analysis includes data cleaning, missing value treatment, feature engineering, univariate analysis, bivariate analysis, and multivariate analysis to better understand Netflix's content strategy.

---

## Objectives

* Analyze Netflix content distribution.
* Identify trends in content additions over time.
* Explore relationships between content type, genre, duration, and release year.
* Understand country-wise content contribution.
* Generate actionable insights through data visualization.

---

## Dataset Information

**Dataset Name:** Netflix Titles Dataset

**Source:** Kaggle

The dataset contains information about Netflix Movies and TV Shows including:

* Show ID
* Type (Movie / TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

---

## Data Cleaning

The following preprocessing steps were performed:

* Handled missing values in:

  * Director
  * Cast
  * Country
  * Duration
* Removed data inconsistencies where necessary.
* Converted date columns into appropriate datetime format.
* Verified data quality through missing value analysis.

---

## Feature Engineering

New features were created to improve analysis:

| Feature         | Description                                    |
| --------------- | ---------------------------------------------- |
| year_added      | Year content was added to Netflix              |
| content_age     | Difference between Year Added and Release Year |
| main_genre      | Primary genre extracted from listed categories |
| primary_country | Primary country extracted from country column  |
| duration_num    | Numeric duration extracted from duration       |
| genre_count     | Number of genres assigned to a title           |

---

## Exploratory Data Analysis

### Univariate Analysis

Analyzed individual variables such as:

* Content Type Distribution
* Release Year Distribution
* Duration Distribution
* Genre Distribution
* Country Distribution

### Bivariate Analysis

Studied relationships between:

* Type vs Genre
* Type vs Rating
* Type vs Duration
* Year Added vs Type
* Release Year vs Content Age

### Multivariate Analysis

Performed:

* Correlation Analysis
* Genre vs Duration vs Type Analysis
* Release Year vs Duration vs Type Analysis

---

## Key Insights

* Netflix's catalog is dominated by recently released content.
* Most content was added between 2018 and 2021.
* Movies represent a significant portion of the platform's library.
* Most titles are added shortly after their original release.
* Multi-genre classification is common across content.
* Content duration varies substantially across titles.
* Release Year and Content Age show a strong inverse relationship.
* Netflix maintains a diverse mix of modern and classic content.
* Genre diversity remains largely independent of content duration.
* The dataset contains very few missing values and exhibits strong overall data quality.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Visualizations

Key visualizations included:

* Content Type Distribution
* Content Added Over Time
* Top Genres
* Top Countries
* Release Year Distribution
* Type vs Genre Analysis
* Type vs Rating Analysis
* Correlation Heatmap
* Multivariate Scatter and Box Plots

---

## Conclusion

The analysis reveals that Netflix primarily focuses on recently released content while maintaining a diverse and globally distributed content library. Movies dominate the catalog, and the platform experienced significant growth between 2018 and 2021. The findings provide valuable insights into Netflix's content acquisition and distribution strategy.

---

## Author

**Aarti Bisht**

 | Python | Pandas | Data Visualization | Exploratory Data Analysis

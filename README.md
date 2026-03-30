# Netflix Content Strategy Analysis

## Overview

This project analyzes Netflix’s content library to understand its content strategy, growth patterns, and distribution across time, genres, and countries. The analysis is based on a publicly available dataset of Netflix titles and focuses on extracting business insights from content availability data.

---

## Objective

The goal of this project is to answer the following key questions:

* How has Netflix’s content library grown over time?
* What is the distribution between Movies and TV Shows?
* Which genres and ratings dominate the platform?
* How does content vary across countries?
* What strategic insights can be derived from content distribution?

---

## Dataset

The dataset contains information about Netflix titles, including:

* Title
* Type (Movie / TV Show)
* Date Added
* Release Year
* Country
* Genre (Listed In)
* Rating
* Duration

---

## Data Cleaning & Preprocessing

The dataset required several preprocessing steps before analysis:

* Converted `date_added` to datetime format using safe parsing
* Extracted `year_added` for time-based analysis
* Handled missing values in key columns such as `date_added` and `country`
* Split and exploded multi-value columns (e.g., country, genre)
* Standardized column names for consistency

---

## Exploratory Data Analysis

### Content Growth Over Time

Netflix experienced rapid expansion in content additions between 2016 and 2019, followed by stabilization post-2020.

### Movies vs TV Shows

Movies dominate the content library, indicating a strategy focused on high-volume content acquisition. TV Shows, though fewer, show steady growth over time.

### Genre Distribution

International Movies and Dramas are among the most common genres, highlighting Netflix’s global content strategy.

### Ratings Distribution

The platform primarily targets mature audiences, with TV-MA and TV-14 being the most frequent ratings.

### Country Analysis

The United States leads in content production, followed by countries like India and the United Kingdom. Content trends vary significantly across regions.

---

## Key Insights

* Netflix followed an aggressive expansion strategy between 2016 and 2019
* Content growth stabilized after 2020, influenced by external factors such as COVID-19
* Movies dominate in volume, supporting user acquisition strategies
* TV Shows contribute to long-term engagement and retention
* Content distribution varies significantly by country, emphasizing localization

---

## Business Recommendations

* Maintain strong movie production to support user acquisition
* Increase investment in high-quality TV Shows to improve retention
* Focus on localized content strategies in key international markets
* Optimize content mix in mature markets where growth has slowed
* Build resilience in content production to handle disruptions like COVID-19

---

## Limitations

* The dataset represents content availability (supply-side) rather than user behavior (demand-side)
* No data on user engagement, watch time, or preferences
* Insights about audience behavior are inferred indirectly and should be interpreted with caution

---

## Conclusion

Netflix has transitioned from rapid expansion to a more optimized content strategy. While movies dominate the platform, TV Shows play a crucial role in retention. Future growth will depend on balancing content types, strengthening localization, and adapting to external disruptions.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

* `netflix-dataset-eda.ipynb` → Full analysis notebook
* `presentation.pdf` → Business insights and strategy slides
* `README.md` → Project documentation

---
## Data Source

The dataset used in this project is publicly available and was originally provided by Netflix for analysis purposes. It contains information about movies and TV shows available on the platform, including metadata such as genre, country, release year, and date added.

Source: Netflix Movies and TV Shows Dataset (commonly available on platforms such as Kaggle)

Note: This project uses the dataset solely for educational and analytical purposes. All rights belong to the original data provider.


## Author

Amee Ghai
B.S. Physics, IIT Jodhpur


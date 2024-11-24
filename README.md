# Netflix Data Analysis Case Study

## Project Overview
This case study explores the Netflix dataset to analyze key trends, customer behaviors, and content performance. The goal is to uncover insights related to viewer preferences, content popularity, and the impact of various attributes like genre, release year, and ratings on user engagement. The analysis is aimed at providing data-driven recommendations to improve content strategy and audience targeting for streaming platforms.

Project link: [Netflix Data Analysis Case Study](https://github.com/DurgaPrasadsampatirao/Netflix-Data-Analysis-Recommendations-.git)

---

## Key Objectives
1. **Content Performance Analysis**: Explore which genres, countries, and types of content (movies vs. TV shows) are most popular.
2. **Customer Behavior Insights**: Analyze how ratings, release year, and content duration influence user engagement.
3. **Trends Over Time**: Identify trends in Netflix's content catalog growth over the years, including the rise of original content.
4. **Correlation Analysis**: Examine relationships between different features like rating, genre, and content type.

---

## Insights and Findings

### 1. Data Overview
- **Dataset**: The dataset includes information about Netflix's movies and TV shows, such as title, genre, country, release year, rating, and duration.
- **Key Columns**:
  - `show_id`: Unique identifier for each movie or TV show.
  - `type`: Type of content (e.g., movie or TV show).
  - `title`: Title of the movie or TV show.
  - `director`: Director(s) of the content (some entries missing).
  - `cast`: Cast of the movie or TV show (some entries missing).
  - `country`: Country where the content was produced (some entries missing).
  - `date_added`: Date the content was added to Netflix (some entries missing).
  - `release_year`: Year the content was released.
  - `rating`: Viewer rating or content's average rating (some entries missing).
  - `duration`: Duration of the content (for movies, it's in minutes; for TV shows, it's in seasons).
  - `listed_in`: Categories the content is listed under (e.g., Drama, Comedy).
  - `description`: Short description of the content.

### 2. Content Performance Analysis
- **Most Popular Genres**: Genres such as Drama, Comedy, and Action have the highest number of titles.
- **Most Frequent Countries**: The United States and India dominate the dataset in terms of content production, reflecting Netflix's largest markets.
- **Content Type Distribution**: A larger proportion of Netflix's content is movies, with TV shows making up a smaller portion but steadily growing.

### 3. Trends Over Time
- **Growth of Original Content**: The number of Netflix Original titles has increased significantly since 2010, reflecting Netflix’s shift toward creating its own content.
- **Content Release Trends**: More content was released in the last decade, particularly after Netflix’s global expansion.
- **Rating Trends**: Content ratings have remained relatively stable, with the majority of titles falling within the 7-8 range, suggesting solid overall viewer satisfaction.

### 4. Customer Behavior Insights
- **User Rating Behavior**: Shows with higher ratings tend to have a higher average watch time or a larger number of views.
- **Content Preferences**: Users tend to engage more with content that has shorter durations or specific popular genres, such as Action or Drama.

### 5. Correlation Analysis
- **Rating vs. Duration**: The analysis shows a weak negative correlation between the duration of movies and their ratings, suggesting that shorter content may be preferred by users.
- **Genre vs. Rating**: Some genres, like Documentaries and Family content, tend to have higher ratings, while others like Reality shows may have more varied ratings.

---

## Methodology
1. **Data Collection**: The dataset is sourced from Netflix's public data on movies and TV shows. It contains several years of data with various content attributes.
2. **Data Cleaning**: Removed duplicates, handled missing values, and transformed date features to enable more accurate analysis.
3. **Exploratory Data Analysis (EDA)**: Performed EDA to identify trends, outliers, and correlations between content attributes and viewer engagement.

---

## Technologies Used
- **Python**: For data cleaning, analysis, and visualization.
- **Libraries**: Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn
- **Jupyter Notebooks**: For interactive analysis and visualization.
- **SQL**: For querying the dataset if needed.


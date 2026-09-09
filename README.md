# Social-Media-Engagement-Analytics
Python data analysis project on social media engagement.


# Social Media Engagement Analytics

## Project Overview

This project analyzes social media engagement data using Python to understand user behavior, content performance, and engagement patterns.
The analysis includes data import and preparation, data cleaning, exploratory data analysis, data wrangling, statistical analysis, and data visualization.

## Dataset

The dataset contains 5,000 social media records with information about:

- User demographics
- Post types and categories
- Likes, comments, and shares
- Watch time and impressions
- Follower count
- Verification status
- Device type
- Sentiment
- Hashtags
- Engagement rate

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Analysis Performed

### Data Import & Setup
- Imported the dataset using Pandas
- Checked data types
- Converted date values to datetime
- Performed basic NumPy operations

### Data Cleaning
- Detected and handled missing values
- Checked for duplicate records
- Checked and standardized categorical values
- Created hashtag count
- Checked engagement-related values

### Exploratory Data Analysis
- Examined dataset structure and descriptive statistics
- Analyzed categorical distributions
- Created a correlation matrix
- Performed group-based analysis

### Data Wrangling
- Created an engagement score using likes, comments, and shares
- Performed groupby analysis by post type, country, and sentiment

### Statistical Analysis
Calculated:
- Mean
- Median
- Mode
- Standard deviation
- Variance
- Percentiles

### Data Visualization

Visualizations were created using Matplotlib, Seaborn, and Plotly, including:

- Likes vs Impressions
- Daily Engagement Trend
- Posts by Category
- Gender Distribution
- Age Distribution
- Engagement Rate Distribution
- Post Type Distribution
- Average Likes by Category
- Followers vs Sentiment
- Numeric Feature Pair Plot
- Correlation Heatmap
- Engagement Score by Device Type
- Interactive Plotly visualizations

## Key Insights

- Video posts recorded the highest average engagement score among post types.
- Music was the highest-performing post category.
- Brazil recorded the highest average engagement rate among the countries.
- The 13–18 age group recorded the highest average engagement score.
- Non-verified users recorded higher average engagement than verified users.
- Mobile users had the highest average watch time.
- Negative-sentiment posts recorded the highest average engagement score.

## Project Files

- `Module-end Python DA assignment.ipynb` — Complete Jupyter Notebook containing the analysis and visualizations.
- `social_media_engagement_5000.csv` — Dataset used for the analysis.

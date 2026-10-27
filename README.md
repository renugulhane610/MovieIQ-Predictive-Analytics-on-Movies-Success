# MovieIQ – Predictive Analytics on Movie Success

MovieIQ is an interactive Streamlit dashboard that explores the factors influencing movie performance and predicts whether a movie is likely to be commercially successful. The project uses data analysis, statistical testing, and machine learning to examine relationships between budget, revenue, popularity, runtime, ratings, and genre.

## Key Features

- **Movie Success Prediction:** Predicts whether a movie is profitable based on whether its revenue exceeds its budget.
- **Data Visualization:** Uses Matplotlib and Seaborn to explore trends such as budget versus revenue and performance across genres.
- **Statistical Analysis:** Applies t-tests and chi-square tests to investigate relationships and differences in movie data.
- **Machine Learning:** Uses a Random Forest Classifier to predict movie success.
- **Interactive Dashboard:** Allows users to filter movies by genre and average vote rating.
- **Streamlit Deployment:** Provides an interactive interface for exploring the results.

## Tech Stack

- **Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Statistical Testing:** SciPy
- **Dashboard:** Streamlit

## Dataset

The project uses a `movies.csv` dataset containing information about movies, including the following columns:

`budget`, `revenue`, `popularity`, `runtime`, `vote_average`, `title`, and `genres`.

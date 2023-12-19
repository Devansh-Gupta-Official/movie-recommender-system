# Movie Recommendation System using Collaborative Filtering

This repository contains code for building a movie recommendation system using **item based collaborative filtering** techniques. The dataset used is a collection of movie ratings by users, allowing us to predict movie recommendations based on user preferences.

## Overview
This project aims to create a recommendation system for movies based on user ratings. Collaborative filtering is used to predict movie preferences for users based on their historical ratings by grouping similar movies together.

## Dataset
1. Movie_Id_Titles.csv: Contains movie IDs and corresponding titles.
2. u.data: Includes user ratings for various movies.
3. My_Ratings.csv: Contains a list of 2 movies and their ratings.

## Dependencies
- Python 3
- Libraries:
  - Pandas
  - NumPy
  - Seaborn
  - Matplotlib
 
## Usage
1. Clone the repository:
   ```
   git clone https://github.com/Devansh-Gupta-Official/movie-recommender-system.git
   ```

2. Install the required dependencies:
   ```
   pip install pandas numpy seaborn matplotlib
   ```
3. Ensure the dataset files Movie_Id_Titles.csv and u.data are in the project directory.
4. Run the Jupyter notebook Movie_Recommendation.ipynb to see the analysis and recommendations.

## Implementation Details
### Data Preprocessing
- **Data Cleaning:** Handle missing values, if any, and remove duplicates.
- **Merging Data:** Combine movie titles and user ratings to create a unified dataset for analysis.
- **Data Transformation:** Convert categorical data into a suitable format for analysis.

### Exploratory Data Analysis (EDA)
- **Rating Distribution:** Visualize the distribution of movie ratings to understand user preferences.
- **Popular Movies:** Identify the most rated movies and their average ratings.
- **User Activity:** Analyze user engagement by the number of ratings per user.

### Collaborative Filtering
- **Item-Based Filtering:** Implement item-based collaborative filtering using similarity measures (e.g., cosine similarity) between movies.
- **Predictions:** Generate movie recommendations based on a user's past ratings and similarities with other movies.

### Model Evaluation
- **Performance Metrics:** Evaluate the recommendation system using metrics like Mean Squared Error (MSE) or Root Mean Squared Error (RMSE).
- **Validation:** Split the dataset into training and testing sets to validate the model's accuracy.



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
The system starts by cleaning the dataset, handling missing values, and eliminating duplicates. It merges movie titles and user ratings, creating a unified dataset. Categorical data is transformed to a suitable format for analysis.

### Exploratory Data Analysis (EDA)
- **Rating Distribution:** Visual representations (histograms, box plots) to showcase the spread of movie ratings and user preferences.
- **Popular Movies:** Identification of highly rated and frequently rated movies to understand their popularity.
- **User Activity:** Analysis of user engagement through the number of ratings per user.

### Collaborative Filtering
- **Item-Based Filtering:** Implementation of item-based collaborative filtering techniques. Utilizes similarity measures (e.g., cosine similarity) between movies to make recommendations.
- **Predictions:** Generating personalized movie recommendations for users based on their historical ratings and movie similarities.

### Model Evaluation
- **Performance Metrics:** Evaluation of the recommendation system using Mean Squared Error (MSE) or Root Mean Squared Error (RMSE).
- **Validation:** Splitting the dataset into training and testing sets to validate the accuracy of the model.


## Results
### Data Visualization
- **Ratings Distribution:** Visual representations highlighting the distribution of movie ratings to understand user preferences.
- **Movie Correlations:** Heatmaps or correlation matrices illustrating relationships between different movies based on user ratings.

### Analysis
- **Top-Rated Movies:** A list of the top-rated movies along with their average ratings and popularity.
- **Similar Movies:** Examples of movies highly correlated based on user ratings, suggesting similar audience preferences.
- **Recommendations:** Personalized movie recommendations based on a user's historical ratings and similarity with other users.

### Evaluation
- **Model Accuracy:** Presentation of evaluation metrics assessing the accuracy of the recommendation system.
- **Comparative Analysis:** Comparison of different collaborative filtering approaches or algorithms to highlight effectiveness.

## Conclusion
This movie recommendation system demonstrates the effectiveness of collaborative filtering techniques in providing personalized movie suggestions. It offers insights into user preferences and movie correlations, aiming to enhance user experience and satisfaction.

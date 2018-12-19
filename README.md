This repository contains self-contained Recommendation System examples.

### Table of Contents
  - <a href='#movie-recommender-using-imdb-calculation'>Movie Recommender-IMDB Calculation</a> 
  - <a href='#movie-recommender-using-parameter-filtering'>Movie Recommender-Parameter Filtering</a> 
  - <a href='#movie-recommender-using-collaborative-filtering'>Movie Recommender-Collaborative Filtering</a> 
  
 <hr>
  
- ###### [Movie Recommender using Collaborative Filtering:](https://github.com/rahulvaish/RecommendationSystems-Python/blob/RecommendationSystems/MovieRecommender-CollaborativeFiltering.ipynb) 
  * Load the Dataset [u.data]
  * Create User-Movie Rating Relationship Table
  * Cater Missing Values
  * Prepare User-User Similarity Matrix Dataframe [Cosine Metric]
  * Handle diagnols
  * Create Movie-User Rating Relationship Table
  * Cater Missing Values
  * Prepare Item-Item Similarity Matrix Dataframe [Correlation Metric] 
  * Load the Dataset [u.item]
  * Prepare user defiend functions to compute Recommendations.
 
  
 <hr>
  
- ###### Movie Recommender using IMDB Calculation:
  * Load the Dataset [movies_metadata.csv]
  * Apply IMDB Formula
  ![image](https://user-images.githubusercontent.com/689226/50198368-53956c00-0371-11e9-9fc4-e5c082c351af.png)
  * Sort movies based on score calculated 
  * Get the top n movies
  ![image](https://user-images.githubusercontent.com/689226/50198225-a6baef00-0370-11e9-8a19-5e33f59090f8.png)

  <hr>
  
- ###### Movie Recommender using Parameter Filtering:
  * Load the Dataset [movies_metadata.csv]
  * Filter by adult/Non-Adult Movie
  * Filter by year
  * Filter by Vote Count
  * Filter by Run time
  * Filter by Vote Average
  * Filter by Genres


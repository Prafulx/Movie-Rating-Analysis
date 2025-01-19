# Movie-Rating-Analysis
This project demonstrates an analysis of movie ratings using Python and pandas. The dataset contains information about users, movies, and ratings, which are merged and analyzed to uncover interesting insights, such as gender-based preferences, the most controversial movies, and genre-wise ratings.
Dataset Files

The analysis is performed on three datasets:

users.dat - Contains user information, such as user ID, gender, age, occupation, and zip code.

ratings.dat - Contains movie ratings by users, including user ID, movie ID, rating, and timestamp.

movies.dat - Contains movie details, including movie ID, title, and genres.

Analysis Steps

Data Loading and Merging:
The datasets are loaded using pandas and merged for easier analysis.

Mean Ratings by Gender:
Calculated mean ratings for each movie, grouped by gender.

Popular Movies:
Identified movies with at least 250 ratings to focus on frequently rated titles.

Top Movies by Female Viewers:
Sorted movies based on ratings by female viewers.

Rating Differences:
Created a column to analyze differences in ratings between male and female viewers.

Most Controversial Movies:
Identified movies with the highest variance in ratings, indicating disagreements among viewers.

Genre-Wise Analysis:
Explored genre-level ratings by different age groups using the explode method to handle multiple genres for a movie.

Results and Insights

Mean ratings categorized by gender reveal differences in preferences.

Movies with significant rating differences between genders were identified.

The most controversial movies (highest variance in ratings) were analyzed.

Genre-wise preferences by age group were visualized.


## Exploring_And_Predicting_FIFA_Players_Stats
Conducted data collection, preprocessing, feature engineering (including web scraping, REST API calls, principal component analysis), and regression modeling to predict overall player ratings, achieving 94% accuracy with KNN regression, as part of the Application in Data Analysis course completion.

# Motivation
The FIFA World Cup is a widely popular sporting event, and with the tournament taking place in the winter, we decided to explore football-related data for this project. We chose to use player data from the EA Sports FIFA21 video game, which corresponds to real-world players' characteristics. Our goal was to analyze and predict the overall ratings of FIFA players based on their multiple-attribute skillset. By building regression models, we aimed to provide insights for football teams in deciding which players to consider for their roster and help fans understand what makes the perfect FIFA player.

# Data
We collected the dataset for this project through web scraping from sofifa.com, a website that tracks EA Sports FIFA football player's characteristics, game statistics, club history, and more. We also used an API called SoccerData to compare and merge relevant features for our analysis. The dataset comprises 18,944 FIFA 2021 players with 106 attributes, including demographics, physical attributes, club profile, monetary value, and skills. The dependent variable for our analysis is "overall_ratings," which represents the players' ratings.

# Data Cleaning & Reduction
We performed data cleaning and reduction to prepare the dataset for analysis. This included text cleaning, setting categorical variables, creating dummy variables, and handling missing data entries. Due to the large size of the dataset with 106 attributes, we also used principal component analysis to reduce dimensionality and visualize the data. We found that only 46% of the variance was captured in the first two principal components, indicating the complexity and size of the dataset.

# Data Classification
We used classification methods to understand the internal structure of the dataset and unlock predictive potential. K-means and Gaussian Mixture clustering models were applied to classify players into distinct groups based on their attributes. However, we found that the clusters were mostly defined by the overall ability of players rather than their relative strengths and weaknesses or demographic characteristics.

# Data Exploration
We explored the dataset further by creating graphs and visualizations to understand various patterns of players' attributes, such as age distribution, region-specific attributes, team/club-specific attributes based on their positions, and monetary value. This helped us in eliminating irrelevant attributes and fine-tuning our models.

# Analytics Models
In this project, we used various regression models to predict significant factors for rating FIFA players. These included Multiple Linear Regression, Multiple Linear Regression with 10-Fold Cross Validation, Ridge Regression, K-Nearest Neighbors (KNN) Regression, and Voting Regression. We also performed model comparison and feature selection using Gradient Boosting.

# Conclusion
In conclusion, this project aimed to explore and predict FIFA player's stats based on their attributes using data analysis techniques. Through data collection, cleaning, reduction, classification, and exploration, we gained insights into the factors affecting FIFA player's overall ratings. Our regression models provided valuable information for football teams in making roster decisions and for fans in understanding what makes the perfect FIFA player.

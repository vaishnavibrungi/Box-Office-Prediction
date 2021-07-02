# **Problem Statement**

We are presented with metadata on over 7,000 past films from The Movie Database to try and we have to predict the worldwide revenue for 4398 movies. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.

# **Summary**

## Train Data Cleaning 
* Missing values were fixed.
* "release_date" which was in object format was converted to datetime format.
* Created and modified features using feature engineering

## Test Data Cleaning 
* Missing values were fixed.
* "release_date" which was in object format was converted to datetime format.
* Created and modified features using feature engineering

## Exploratory Data Analysis

Descriptive statistics were generated for Train data.

## Data Visualization

Scatter plots were used to analyze the data.

# **Data Dictionary**
A complete overview of the data can be found here
[**Data Description**](https://www.kaggle.com/c/tmdb-box-office-prediction/data?select=train.csv)


# **Conclusions**
The objective of the analysis was to build a model to predict worldwide box office revenue for 4398 movies. Our model resulted in an RMSE of 82909571.5, which translates to an error of  ~±$82909572 for the average movie revenue.
The factors seen as  predictors through our model were :
   * budget
   * popularity
   * runtime
   * genre_Adventure
   * title_words_count
   * genre_Animation
   * genre_Horror
   * genre_Romance
   * genre_Family
   * genre_TV Movie

# **Next Steps**

For our model we have focussed on only 8 features, to predict worldwide box office revenue. To fine-tune the model we can :
* Include the  "original_language" column , "cast" and the "crew" columns ,create dummies  to see if they have an impact on revenue.
* Include "production_companies" column and see if it is positively correlated with the movie revenue

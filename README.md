# zomato-recommendation-system
this project "Recommendation System for Zomato data" that I made under the guidance of "Astha Sinha" Madam, consists of the recommendation system or model that recommends to user the restaurant based upon the input of the user for a certain restaurant.

This project aims to develop a restaurant recommendation system using a cleaned and analyzed Zomato dataset. The system will leverage user preferences and restaurant attributes to provide personalized recommendations.

Dataset:

Source: Zomato dataset
Description: The dataset contains information about restaurants, including location, cuisine, ratings, reviews, and user preferences.
Cleaning: The dataset underwent thorough cleaning, including:
Handling missing values (imputation or removal)
Removing duplicates
Identifying and addressing inconsistencies
Data type conversions
Outlier detection and handling
Methodology:

Data Exploration and Analysis: Exploratory Data Analysis (EDA) was performed to understand the dataset's characteristics. Key insights were extracted, such as popular cuisines, highly-rated restaurants, and user preferences.
Feature Engineering:
Relevant features were extracted or engineered from the cleaned data. Examples: * User-based features: User's past orders, ratings, preferred cuisines. * Restaurant-based features: Cuisine, location, price range, ratings, reviews. * Contextual features: Time of day, day of the week, special occasions.
Recommendation Algorithms:
Collaborative Filtering: * User-based: Recommends restaurants based on the preferences of similar users. * Item-based: Recommends restaurants similar to those the user has liked in the past.
Content-Based Filtering: Recommends restaurants based on user preferences for specific attributes (e.g., cuisine, location, price range).
Hybrid Approaches: Combine collaborative and content-based filtering for improved accuracy.
Model Evaluation: The performance of the recommendation models was evaluated using appropriate metrics:
Precision, Recall, F1-score
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Implementation:

Programming Language: Python
Libraries: Pandas, NumPy, seaborn, matplotlib, CountVectorizer, TfidfVectorizer
Tools: Jupyter Notebook
Text Preprocessing

Lower casing
Removal of Punctuations
Removal of Stopwords
Removal of URLs
Spelling correction
Project Structure:

data/: Contains the raw and cleaned Zomato dataset.
notebooks/: Contains Jupyter Notebooks for data cleaning, analysis, and model development.
src/: Contains Python scripts for data preprocessing, model training, and evaluation.
models/: Stores trained recommendation models.
README.md: This file.
Future Work:

Incorporate real-time user feedback to refine recommendations.
Develop a user interface for an interactive recommendation system.
Explore more advanced recommendation algorithms, such as deep learning models.
Integrate location-based services for personalized recommendations.

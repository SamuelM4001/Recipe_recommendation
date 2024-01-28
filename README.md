# Recipe Recommendation System

The Recipe Recommendation System is a machine learning and natural language processing project designed for personalized recipe suggestions based on user-input ingredients. The system analyzes a dataset of recipes using TF-IDF encoding and KNN classification with cosine similarity.

## Overview

### 1. Data Conversion and Cleaning
- **File:** Data_conversion_and_cleaning.ipynb
- **Description:** This notebook processes the dataset downloaded from [eightportions.com](https://eightportions.com/datasets/Recipes/).
  - Converts the data from JSON to CSV format.
  - Handles missing data.
  - Saves the cleaned dataset as `cleaned_data.csv`.

### 2. Ingredient Parser
- **File:** Ingredient_parser.ipynb
- **Description:** Implements natural language processing techniques to clean the ingredients column.
  - Removes stop words, measuring words, and irrelevant terms.
  - Applies lemmatization for base form extraction.
  - Encodes the data using TF-IDF encoding.
  - Saves the encoded data in pickle format.

### 3. Recommendation System
- **File:** Recommendation_System.ipynb
- **Description:** Takes user-input ingredients and employs KNN classification to recommend recipes.
  - Uses cosine similarity as a measure of distance.
  - Loads the pre-trained model and encoded data.
  - Outputs personalized recipe recommendations.

## Usage

1. Run `Data_conversion_and_cleaning.ipynb` to clean and convert the dataset.
2. Execute `Ingredient_parser.ipynb` to process and encode the ingredients.
3. Utilize `Recommendation_System.ipynb` to get personalized recipe recommendations.

## Acknowledgement

- The dataset was obtained from [eightportions.com](https://eightportions.com/datasets/Recipes/).
- Reference: [Building a Recipe Recommendation System](https://towardsdatascience.com/building-a-recipe-recommendation-system-297c229dda7b).

This project was made by me to learn more about ML and NLP, feel free to use it as reference.

---

*Samuel Mendonca*

           

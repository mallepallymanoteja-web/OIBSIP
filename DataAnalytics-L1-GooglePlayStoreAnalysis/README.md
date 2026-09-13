# Unveiling the Android App Market – Google Play Store Analysis

## Objective

To analyze Google Play Store data and uncover insights about app categories, ratings, installs, pricing, app size, reviews, and user sentiment.

## Dataset

The datasets used for this project are:

- Google Play Store Apps dataset
- Google Play Store User Reviews dataset

Source: Kaggle – Google Play Store Apps

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- TextBlob
- Google Colab / Jupyter Notebook

## Data Cleaning

The datasets were cleaned by:

- Removing duplicate records
- Handling missing values
- Correcting invalid ratings
- Converting installs into numeric values
- Converting prices into numeric values
- Converting app size into MB
- Converting the Last Updated column into datetime format
- Standardizing categorical missing values
- Removing reviews with missing review text

## Exploratory Data Analysis

The analysis covers:

- Number of apps by category
- Average rating by category
- Total installs by category
- Free vs paid applications
- Paid application price analysis
- Rating vs number of reviews
- App size vs installs
- User sentiment distribution
- Sentiment analysis by app category

## Sentiment Analysis

TextBlob was used to calculate sentiment polarity for user reviews.

Reviews were classified into:

- Positive
- Negative
- Neutral

The average TextBlob polarity was **0.189**, indicating an overall slightly positive sentiment in the analyzed reviews.

## Key Insights

1. **Family dominates the app marketplace by volume:**  
   The FAMILY category has the highest number of apps with 1,943 apps, followed by GAME with 1,121 apps and TOOLS with 843 apps.

2. **Events has the highest average rating:**  
   The EVENTS category has the highest average rating of 4.44, followed by EDUCATION with 4.38 and ART_AND_DESIGN with 4.36.

3. **Games have the highest user reach:**  
   The GAME category has the highest total installs at approximately 31.54 billion, followed by COMMUNICATION with 24.15 billion and SOCIAL with 12.51 billion.

## Conclusion

This analysis explored the Google Play Store app market using app information and user reviews. The data was cleaned and analyzed to understand category popularity, ratings, installs, pricing, app size, reviews, and customer sentiment.

The findings can help app developers and businesses understand market trends and user preferences when planning or improving applications.

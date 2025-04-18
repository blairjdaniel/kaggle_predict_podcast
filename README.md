# kaggle_predict_podcast
Kaggle competition to predict the listening time of a podcast - April 2025

## EDA
- Focused on key columns: `episode_length_minutes`, `host_popularity_percentage`, and `guest_popularity_percentage`.
- Performed data cleaning, including handling missing values and outlier removal.
- Applied Principal Component Analysis (PCA) to reduce dimensionality and extract the most important features.
- Encoded categorical variables such as `episode_sentiment`, `publication_day`, `genre`, and `publication_time` using `LabelEncoder`.
- Scaled numerical features using `StandardScaler` for better model performance.

## Results
- **Best R² Score:** 0.7439595444873465
- **Root Mean Squared Error (RMSE):** 13.40
- **Mean Squared Error (MSE):** 179.50
- **R² Score:** 0.75

## Kaggle Ranking
- **Rank:** 1690
- **Username:** blairjdaniel
- **Score:** 14.35349
- **Submissions:** 1
- **Time Remaining:** 2 minutes
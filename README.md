# Google Play Store Exploratory Data Analysis (EDA)

## Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on the Google Play Store apps dataset to uncover market demand, competition, monetization patterns, and perceived app quality. The analysis is designed for business and strategic insights rather than prediction or machine learning.

## Objectives
- Understand app market demand across categories
- Analyze competition intensity within categories
- Compare performance of paid vs free apps
- Examine factors associated with perceived app quality
- Identify categories where new apps may have realistic opportunities

## Dataset
The dataset contains metadata for Google Play Store apps, including:
- App name and category
- Ratings and number of reviews
- Number of installs
- App size and price
- Content rating and genres
- Android version compatibility

## Data Cleaning & Preparation
Key data preprocessing steps include:
- Handling duplicate app entries across categories and genres
- Cleaning and normalizing install counts and prices
- Converting app size to numeric format
- Removing invalid or corrupted records
- Handling missing values with context-aware decisions
- Standardizing column names and formats

## Key Analyses Performed
- **Category Demand Analysis:** Identified high-demand categories using installs per app
- **Competition Analysis:** Compared demand relative to app count across categories
- **Monetization Analysis:** Compared ratings, installs, and reviews between paid and free apps
- **Pricing vs Quality:** Evaluated whether higher-priced apps show better perceived quality
- **Rating Consistency:** Identified categories with consistently high ratings using average rating and variability
- **Opportunity Identification:** Highlighted categories with strong demand and manageable competition

## Key Insights
- Free apps dominate overall installs, while paid apps tend to have slightly higher average ratings
- High app size correlates with higher installs but has minimal influence on ratings
- Very high-priced apps do not consistently show better perceived quality
- Categories such as Education and Personalization maintain stable, consistently high ratings
- Some categories exhibit strong demand with relatively fewer competitors, indicating potential opportunities

## Tools & Technologies
- Python
- pandas, NumPy
- Matplotlib, Seaborn

## Scope & Limitations
- This project focuses strictly on exploratory analysis
- No machine learning, prediction, or causal inference is performed
- Installs are bucketed values and should be interpreted as relative demand indicators
- Review counts reflect engagement volume, not sentiment

## Conclusion
This EDA provides a structured and business-oriented view of the Google Play Store app ecosystem. The insights derived can support strategic decision-making for marketing teams, founders, and investors when evaluating app market opportunities.

## License
The dataset used in this project is licensed under the MIT License and was sourced from an open repository.

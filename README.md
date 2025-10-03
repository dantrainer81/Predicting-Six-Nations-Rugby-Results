# Predicting Six Nations Rugby Match Results 

## Executive Summary

This project aims to build a predictive model to forecast match outcomes for the 2026 Six Nations Rugby Championship fixtures using only public, match-level data, producing both hard classifications (home/away win). With models trained and evaluated for accuracy. Match-level results do not identify individuals, if any player-level attributes are added later, the data will be treated as personal data and the project will follow UK GDPR principles. This project was hampered by the match level data only including generic information, with no team form/strength being included. This produced near constant probabilities for the results. Future iterations of this project should include the use of feature engineering to produce rolling form scores and an Elo rating system.

## Data Collection

The Six Nations Championship was formed in the year 2000, with the Five Nations Championship being its predecessor. Each completing team plays the opposition once during the tournament, which doesn't give a high volume of match data to build the model on. Therefore, the project used data from all international matches between the Six Nation Championship teams. The initial data source included all international rugby matches from 1871 to 2024 (Data Source One), and an additional data source being used for the 2025 Six Nations Championship results (Data Source Two). Both data sources are publicly accessible via www.kaggle.com

Data Source One - https://www.kaggle.com/datasets/lylebegbie/international-rugby-union-results-from-18712022

Data Source Two -  https://www.kaggle.com/datasets/simfour/rugby-6-nations-results-2000-2024?select=rugby_six_nations.csv

## Data Preparation

The pre-processing and preparation for this project was conducted within Python, using libraries such as pandas and numpy.
The data was first imported into a pandas data frame using the pd.read_csv function, with the initial exploration of the data set being conducted to gain the first insights.

<br>

![Initial Data Review](images/initial_data_review.png)

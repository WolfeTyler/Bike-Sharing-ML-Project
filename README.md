# Bike Sharing ML Project
> A machine learning project to analyze and predict bike-sharing demand using multiple regression techniques.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project aims to understand and predict bike-sharing demand based on various factors like weather conditions, season, and user type.
- The business problem addressed is optimizing resource allocation for bike-sharing services by accurately forecasting demand.
- The dataset used is the publicly available **Bike Sharing Dataset**, which includes daily data on bike rentals, weather, and user statistics.

## Conclusions
- **Season and Weather**: Bike demand is higher in summer and fall (pleasant weather) and lower during winter and severe weather conditions.
- **Registered Users**: Registered users have a higher correlation with total bike demand compared to casual users.
- **Temperature**: Temperature significantly affects bike rentals, with higher demand observed on warmer days.
- **Categorical Variables**: Proper encoding of categorical variables (e.g., `season`, `weathersit`) improves the model’s performance (R-squared: 0.856).

## Technologies Used
- Python 3.x
- pandas 1.x
- numpy 1.x
- scikit-learn 1.x
- seaborn 0.x
- matplotlib 3.x

## Acknowledgements
- This project was inspired by predictive modeling techniques in machine learning.
- Special thanks to tutorials and documentation from the scikit-learn and pandas libraries.

## Contact
Created by [@WolfeTyler](https://github.com/WolfeTyler) - feel free to reach out with questions or feedback!

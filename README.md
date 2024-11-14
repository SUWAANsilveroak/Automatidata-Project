# NYC Taxi Tipping Prediction

## Project Overview
This project aims to build a machine learning model to predict whether a NYC taxi rider will be a **generous tipper** (i.e., tip ≥ 20%). This decision was made to focus on positive tipping behavior, benefiting both taxi drivers and passengers. The model leverages trip details such as itinerary, predicted fare, and time of day to make predictions.

## Problem Statement
Taxi drivers often face challenges in predicting generous tippers. The goal of this project is to create a model that predicts whether a rider will provide a generous tip, based on features such as trip duration, fare amount, and time of day.

## Data Overview
The dataset includes variables that are believed to influence tipping behavior:
- **Trip Itinerary**: Distance and route of the taxi ride.
- **Predicted Fare**: Estimated fare amount for the trip.
- **Time of Day**: When the trip occurred (e.g., rush hour or late night).

## Modeling Approach
Two machine learning models were used to predict generous tipping:
- **Random Forest**: Performed slightly better in terms of prediction accuracy.
- **XGBoost**: Also performed well, but with a slightly lower F1 score.

The **Random Forest model** was selected due to its higher **F1 score** of **0.7235**.

## Model Evaluation
- **F1 Score**: 0.7235 (Random Forest)
- The model was tested and validated using historical NYC taxi data to ensure a robust prediction of generous tipping.

## Recommendations
- **Beta Testing**: The team recommends beta testing with real-world taxi drivers to gather feedback and refine the model further for operational use.

## Technologies Used
- **Python**: For data analysis, feature engineering, and model development (Pandas, Scikit-learn, XGBoost)
- **Jupyter Notebooks**: For model training and evaluation
- **GitHub**: Version control and project hosting

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SUWAANsilveroak/Automatidata-Project.git

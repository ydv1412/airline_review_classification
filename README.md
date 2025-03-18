# Airline Passenger Referral Prediction

## Project Overview
This project analyzes airline passenger reviews to predict whether a traveler will recommend a flight or not. The dataset consists of various features such as seat comfort, cabin service, entertainment, food & beverages, and overall ratings.

## Key Components
- **Exploratory Data Analysis (EDA)**: Understanding trends in airline recommendations.
- **Feature Engineering**: Identifying important factors influencing recommendations.
- **Machine Learning Models**: Implementing multiple classification models to predict referrals.
- **Performance Evaluation**: Comparing model accuracies and F1 scores.

## Dataset Summary
The dataset contains **65,947 rows and 17 columns**, with key attributes like:
- **Ratings**: Seat comfort, cabin service, entertainment, ground service, value for money, and overall rating.
- **Metadata**: Airline name, aircraft, route, review details, and recommendation status.

## Model Performance
| Model                 | Accuracy | F1 Score |
|----------------------|-----------|-----------|
| **KNN Classifier** | 0.96 | 0.95 |
| **Logistic Regression** | 0.96 | 0.94 |
| **SVM Classifier** | 0.96 | 0.95 |
| **Decision Tree** | 0.95 | 0.94 |
| **Random Forest** | **0.968** | **0.96** |
| **Gradient Boosting** | 0.96 | 0.95 |

## Key Insights
- **American Airlines** and **United Airlines** have the highest number of "No Recommendations."
- **China Southern Airlines** has the highest recommendation rate.
- Features like **overall rating, value for money, and food & beverage quality** significantly impact recommendations.
- The **Random Forest model** achieved the best performance.

## Challenges
- Handling **missing values** in the dataset.
- Converting **textual reviews** into meaningful numerical features for modeling.

## Conclusion
The project successfully predicts airline passenger referrals using machine learning models, with **Random Forest achieving the highest accuracy (96.8%)**. The findings can help airlines enhance their services based on passenger feedback.

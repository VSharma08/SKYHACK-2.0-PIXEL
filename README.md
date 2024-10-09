# United Airlines Call Center Optimization

The project focuses on optimizing United Airlines' call center operations by reducing key metrics like **Average Handle Time (AHT)** and **Average Speed to Answer (AST)**. 
By analyzing customer interactions, agent performance, call reasons, and sentiment data, the project applies machine learning models to predict AHT and identify primary call reasons. 
These predictions aim to help agents resolve calls more efficiently and proactively address frequent issues, especially during high call volume periods. 
The goal is to enhance customer experience by improving operational efficiency, reducing call wait times, and minimizing the duration of customer interactions.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Modeling Approach](#modeling-approach)
- [Results](#results)
- [Next Steps](#next-steps)
- [How to Run](#how-to-run)
- [Contributors](#contributors)

## Project Overview
The project utilizes machine learning to predict key call center metrics and call reasons, helping to:
- Reduce AHT by identifying factors that extend call durations.
- Minimize AST by improving workforce allocation during high call volumes.
- Predict primary call reasons to better prepare agents and reduce handling times.

## Data Description
The project uses several datasets:
- **calls.csv**: Includes detailed information on each call, including duration, customer sentiment, and agent interaction details.
- **customers.csv**: Contains customer information like name, elite status, and previous interactions.
- **reason.csv**: Specifies the primary reason for the call (e.g., baggage issues, cancellations).
- **sentiment_statistics.csv**: Provides sentiment analysis data for each call interaction.
- **test.csv**: Used for testing the prediction models.

## Modeling Approach
1. **AHT Prediction Model**: 
   - Uses a Random Forest Regressor to predict AHT based on customer details, call reasons, sentiment scores, and agent/customer tone.
2. **Call Reason Prediction Model**: 
   - Employs a classification model to predict the likely reason for a customer's call.

## Results
- **AHT Prediction**: 
   - The model performed well on training data but showed signs of overfitting on test data. Further tuning is required.
- **Call Reason Prediction**: 
   - The model accurately predicted the reasons for customer calls, improving agent preparedness.

## Next Steps
- Tune the AHT model to reduce overfitting.
- Apply cross-validation and feature selection to enhance model performance.
- Implement the models in real-time to assist agents during peak call periods.

## Contributors
- Vrinda Sharma, Nandini Karmarkar – Data Scientist

---

Let me know if you'd like to customize it further!

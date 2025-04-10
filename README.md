# Predicting Troop Betrayal in the War

## Problem Overview

In the ongoing conflict against the Phrygians, predicting troop betrayal is critical for ensuring the loyalty and effectiveness of our forces. The goal of this project is to develop a predictive system that can identify soldiers at risk of defecting to the enemy. This system uses a combination of social, psychological, and economic factors to assess the likelihood of betrayal and provide commanders with actionable insights.

### Key Factors Considered:
1. **Greed Index**: Measures the soldier’s susceptibility to offers of wealth.
2. **Loyalty History**: Tracks past behaviors and incidents of desertion or disobedience.
3. **Peer Influence**: Assesses the strength of relationships with defected or questionable individuals.
4. **Discontent Level**: Gauges morale through surveys and interviews.
5. **Temptation Score**: Accounts for external offers from the enemy.
6. **Respect and Recognition**: Evaluates the soldier’s rank and perceived value within the army.
7. **Risk Attitude**: Determines whether the soldier is more risk-averse or risk-seeking.

### Data Collection Methods:
- **Surveys and Interviews**: Collect qualitative data on loyalty and morale.
- **Historical Data**: Analyze past behavior of soldiers with similar traits.
- **Real-time Monitoring**: Track morale and social interactions continuously.

## Machine Learning Solution

The project leverages machine learning to classify soldiers as either potential defectors or loyalists. The primary steps are:

1. **Data Preprocessing**: Normalize and standardize the data.
2. **Feature Engineering**: Score each feature (e.g., Greed Index, Discontent Level) based on its contribution to betrayal risk.
3. **Model Selection**: Utilize classification models such as Logistic Regression, Decision Trees, or Random Forests.
4. **Model Training**: Train the model using historical data of both loyal soldiers and defectors.
5. **Evaluation**: Use accuracy, precision, recall, and F1-score to measure performance.

### Workflow:
1. **Input Data**: Feed new soldier data into the system.
2. **Prediction**: The model generates a betrayal risk score.
3. **Ranking**: Soldiers are ranked based on the likelihood of betrayal.
4. **Feedback Loop**: Real-time data from the field is continuously fed back into the system for refinement.

## Tools and Technologies

- **Python**: Primary language for data processing and model implementation.
- **Pandas**: For data handling and manipulation.
- **Scikit-learn**: For building and training the predictive models.
- **Jupyter Notebook**: For interactive data analysis and model development.

## Jupyter Notebook Overview

The solution provided in the Jupyter notebook (`part2_solution.ipynb`) includes the following sections:

1. **Data Loading and Preprocessing**: Loading the data, handling missing values, and normalizing the features.
2. **Feature Engineering**: Scoring features like Greed Index, Loyalty History, etc.
3. **Model Training**: Training a classification model (Random Forest) using historical soldier data.
4. **Model Evaluation**: Evaluating the performance of the trained model using test data.
5. **Prediction and Risk Scoring**: Predicting the betrayal risk for new soldiers and generating a betrayal likelihood ranking.

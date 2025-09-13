# Machine Learning I Class - Data Science Degree - NOVA IMS

## Obesity in Focus: data for healthier lives

Obesity is one of the most pressing public health issues of our time, affecting millions of individuals worldwide (Haththotuwa, Wijeyaratne, & Senarath, 2020). Studies have shown that the prevalence of obesity is driven by factors such as sedentary lifestyles and unhealthy eating habits (Sultana et al., 2021). This trend has highlighted the urgent need to develop effective tools for assessing the risk of obesity based on behavioral patterns, physical conditions, and other information about individuals. 

In recognition of this need, machine learning researchers created a predictive model aimed at identifying obesity levels based on individuals' dietary habits, physical conditions and background. The project’s goal is to support prevention campaigns by providing a better understanding of the relationship between lifestyle factors and the risk of obesity, thereby enabling more effective and personalized interventions.

## The Data

The data was gathered through interviews done to individuals between ages 16 and 56. The dataset is divided between a training set (close to 1600 participants) and a testing set (close to 500 participants):

- `obesity_train.csv`
- `obesity_test.csv`
 
#### Dataset Description:
Contains information about each customer

#### Columns:
- `IDcode`: Unique identifier for the participant
- `age`: Participant’s age in years.
- `alcohol_freq`: How often the participant consumes alcohol.
- `caloric_freq`: Whether the participant frequently eats chocolate/sweets or not.
- `devices_perday`: The amount of time (in hours) the participant spendsusing electronic devices daily.
- `eat_between_meals`: Whether the participant consumes food between meals.
- `gender`: The gender of the participant.
- `height`: Participant’s height in meters.
- `marital_status`: The participant’s marital status.
- `meals_perday`: How many main meals the participant consumes daily.
- `monitor_calories`: Whether the participant monitors their daily caloric intake.
- `parent_overweight`: Whether the participant’s parents (father or mother) suffer from overweight.
- `physical_activity_perweek`: How many days per week the participant engages in physical activity.
- `region`: The participant’s region of origin.
- `siblings`: Number of siblings the participant has.
- `smoke`: Whether the participant smokes or not.
- `transportation`: The primary mode of transportation used by the participant.
- `veggies_freq`: How frequently does the participant consume
- `vegetables`: in their meals.
- `water_daily`: The amount of water (in liters) the participant consumes daily.
- `weight`: Participant’s weight in kilograms.
- `obese_level`: The participant’s obesity level (target variable).

## The Project

In this project, the main objectives are:

1. **Data Exploration and Preprocessing**: Conduct thorough data exploration to understand the main characteristics of the dataset and prepare it for effective modeling.
2. **Feature Analysis**: Identify and analyze the most significant predictors of obesity levels based on lifestyle habits, physical condition and background.
3. **Predictive Modeling**: Apply machine learning algorithms to predict an individual’s obesity level using the variables in the dataset.
4. **Critical Insights**: Beyond predicting obesity levels, derive insights that can inform public health strategies, preventive interventions, and policies aimed at reducing obesity risk.

## The resutls

For the evaluation of the model we used macro F1-score as the primary evaluation metric to ensure fair performance across all obesity classes. 
The final kaggle submission score was **0.9665**
The final project grade - 18/20


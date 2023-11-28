# Waze User Churn Prediction Project

Welcome to your new role at Waze! In this project, we aim to analyze user data and develop a machine learning model that predicts monthly user churn. As a data analyst on the Waze data team, your insights will play a crucial role in preventing churn, improving user retention, and contributing to Waze's business growth.

## Project Goal

The goal of this project is to develop a machine learning model that accurately predicts monthly user churn on the Waze app. The insights gained from the model will help optimize Waze's retention strategy, enhance user experience, and inform data-driven decisions for product development.

## Project Background

Waze’s data team is in the earliest stages of the churn project. Before diving into data analysis, the following tasks need to be accomplished:

- Create a project proposal with organized milestones.
- Classify tasks using the PACE workflow.
- Identify relevant stakeholders.

## Team Members at Waze

### Data Team Roles
- Harriet Hadzic - Director of Data Analysis
- May Santner - Data Analysis Manager
- Chidi Ga - Senior Data Analyst

### Other Roles in the Scenario
- Sylvester Esperanza - Senior Project Manager
- Emrick Larson - Finance and Administration Department Head
- Ursula Sayo - Operations Manager

## Meeting Notes

### Sylvester Esperanza (Senior Project Manager)
- The data team will need a global-level project document to outline project goals and milestones.
- Visuals need to be generated for sharing with the Waze executives.

### Chidi Ga (Senior Data Analyst)
- The dataset has to be inspected before any analysis can begin.
- Exploratory Data Analysis (EDA) is needed to learn more about the data.
- Testing the model for consistent results is crucial.

### Harriet Hadzic (Director of Data Analysis)
- Before sharing insights, ensure the model meets project requirements.
- Identify main talking points for the presentation to the leadership team.

### May Santner’s Thoughts and Concerns
- Suggests using Python for the project.
- Emphasizes the importance of establishing relationships between key variables.
- Recommends considering hypothesis testing.

## Data dictionary

This project uses a dataset called waze_dataset.csv. It contains synthetic data created for this project in partnership with Waze. 

The dataset contains:

14,999 rows – each row represents one unique user 

13 columns

| Column name            | Description                                                |
|------------------------|------------------------------------------------------------|
| ID                     | A sequential numbered index                                |
| label                  | Binary target variable (“retained” vs “churned”) for if a user has churned anytime during the course of the month |
| sessions               | The number of occurrences of a user opening the app during the month |
| drives                 | An occurrence of driving at least 1 km during the month     |
| device                 | The type of device a user starts a session with             |
| total_sessions         | A model estimate of the total number of sessions since a user has onboarded |
| n_days_after_onboarding | The number of days since a user signed up for the app        |
| total_navigations_fav1 | Total navigations since onboarding to the user’s favorite place 1 |
| total_navigations_fav2 | Total navigations since onboarding to the user’s favorite place 2 |
| driven_km_drives       | Total kilometers driven during the month                    |
| duration_minutes_drives| Total duration driven in minutes during the month           |
| activity_days          | Number of days the user opens the app during the month      |
| driving_days           | Number of days the user drives (at least 1 km) during the month |

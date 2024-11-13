# Garment Case Study - Predicting Productivity in the Garment Industry

## Project Overview
The garment industry is highly labor-intensive and critical to global commerce, with production and delivery performance of workers being central to meeting high global demand. As a data scientist for a garment manufacturing company, this project aims to analyze and predict the productivity of working teams using various features such as time-related variables, department, overtime, incentives, idle time, and more.

The objective is to develop a predictive model using Decision Trees to help management identify key factors affecting productivity, enabling better planning and improved performance outcomes.

## Project Structure
This project includes the following main components:
1. **Data Loading and Preprocessing**: Load the data, handle missing values, and preprocess categorical variables for model input.
2. **Exploratory Data Analysis (EDA)**: Investigate the data to understand patterns, distributions, and relationships between productivity and various factors.
3. **Modeling with Decision Trees**: Build a Decision Tree model to predict team productivity based on various input factors.
4. **Feature Importance Analysis**: Identify and analyze the factors that most significantly impact productivity.
5. **Evaluation and Insights**: Assess model performance and interpret key insights for management.

## Dataset Description
The data is provided in CSV format and contains the following columns:

- **date**: Date in MM-DD-YYYY format
- **day**: Day of the Week
- **quarter**: A portion of the month (month divided into four quarters)
- **department**: Department associated with the instance
- **team_no**: Team number associated with the instance
- **no_of_workers**: Number of workers in each team
- **no_of_style_change**: Number of style changes for a product
- **targeted_productivity**: Target productivity set for each team for each day
- **smv**: Standard Minute Value, or time allocated for a task
- **wip**: Work in progress, the number of unfinished items
- **over_time**: Amount of overtime for each team in minutes
- **incentive**: Financial incentive in BDT for motivating workers
- **idle_time**: Time when production was interrupted
- **idle_men**: Number of idle workers due to production interruption
- **actual_productivity**: Actual productivity percentage delivered by the team (ranges from 0-1)

## Goals
- **Analyze** the dataset to uncover insights about productivity and influencing factors.
- **Develop** a Decision Tree model to predict actual productivity.
- **Identify** critical factors that management can focus on to improve productivity outcomes.

## Methodology
1. **Data Cleaning**: Handle missing values, encode categorical data, and standardize numerical features as needed.
2. **Exploratory Analysis**: Perform initial data analysis to visualize productivity trends across departments, overtime, incentives, idle time, etc.
3. **Feature Engineering**: Create and select features that may improve model performance.
4. **Modeling**: Train a Decision Tree model to predict `actual_productivity` based on input features.
5. **Evaluation**: Evaluate model performance using metrics such as Mean Absolute Error (MAE) and R-squared (R²).

## Insights
By identifying the most influential factors affecting productivity, this analysis can help management:
- Understand the impact of overtime, incentives, and idle time on productivity.
- Optimize team allocations and scheduling to maximize productivity.
- Make data-driven decisions regarding incentives and production processes.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn (optional, for visualization)


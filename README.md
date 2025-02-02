# DSIP Final Project Part 2 - Machine Learning

## Project Overview
This project is part of the DSIP Final Project series and focuses on solving the **Spaceship Titanic** classification problem with feature engineering and machine learning techniques such as KNN and Logistic Regression. The primary objective is to predict passenger survival outcomes based on various features.

The dataset used for this project comes from the **[Kaggle Spaceship Titanic Challenge](https://www.kaggle.com/competitions/spaceship-titanic)**.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Information](#dataset-information)
- [Data Engineering](#data-engineering)
- [Machine Learning Workflow](#machine-learning-workflow)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Dataset Information
The **Spaceship Titanic** dataset contains information about passengers, including their cabin type, service usage, and other features that can be used to predict their survival status.

### Key Features
- Passenger ID
- Home Planet
- CryoSleep status
- Cabin information
- Service expenses (RoomService, FoodCourt, etc.)
- Age
- Destination

### Target Variable
- **Transported**: Boolean indicating if a passenger was transported to another dimension.

## Data Engineering
In this stage, the following tasks were completed:
- Data cleaning and handling missing values
- Feature extraction and transformation
- Encoding categorical variables
- Data normalization

## Machine Learning Workflow
The machine learning part of the project involved:
- **Feature Engineering:** Filtered and fitted the data to fit the desired format and to help achieve optimal classification results.
- **Model Selection:** Evaluated several classifiers including KNN and Logistic Regression.
- **Manual Implementation:** As part of the project, manual implementation from scratch of ML models and avoiding problems such as long classification time, integer overflow etc..

## Dependencies
The project uses the following Python libraries:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Horizon-Sunshine/Spaceship_Titanic_ML_Project
   ```
2. Navigate to the project directory:
   ```bash
   cd Spaceship_Titanic_ML_Project
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook ML_Part.ipynb
   ```
4. Execute the cells sequentially to train the model and view results.

## Results
- Achieved good levels of acucary on the test set for all machine learning techniques.
- The final model demonstrated strong performance in predicting passenger transport status.
- Feature importance analysis revealed that **CryoSleep** and **Cabin Type** were significant predictors.

## Acknowledgements
- Kaggle for providing the Spaceship Titanic dataset.
- DSIP professors for their guidance and support.


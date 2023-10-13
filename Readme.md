# Taxi Tip Prediction with Scikit-Learn and SnapML

## Project Overview
This project focuses on creating a predictive model for estimating tip amounts in taxi trips. It leverages the power of both Scikit-Learn and SnapML to preprocess data, build regression models, and assess model performance.

## Objective
The main goals of this project are as follows:
1. **Data Preprocessing**: Utilize Scikit-Learn to perform essential data preprocessing tasks, ensuring the dataset is well-prepared for modeling.
2. **Model Training**: Create a regression model to predict tip amounts using both Scikit-Learn and SnapML. This allows for a comparison of performance and training times.
3. **Evaluation**: Evaluate model performance using Mean Squared Error (MSE) and compare the training efficiency between Scikit-Learn and SnapML.

## Dataset
The dataset contains information about taxi trips, with each entry consisting of 18 variables. The primary target variable for prediction is 'tip_amount'.

## Detailed Steps

### Data Preprocessing
The initial steps involve cleaning and preparing the dataset:
- Rows with zero tips are removed.
- Outliers are excluded, especially trips with tips exceeding the fare cost.
- Columns containing the target variable or unnecessary information are dropped.
- Categorical features are encoded using one-hot encoding.
- Continuous variables are normalized.

### Model Building
Two regression models are trained using Scikit-Learn and SnapML:
- Scikit-Learn: A Decision Tree Regressor is implemented with specified parameters.
- SnapML: A similar Decision Tree Regressor is created, allowing for multi-threaded CPU/GPU training.

### Model Evaluation
Model performance is assessed by calculating the Mean Squared Error (MSE) on the test dataset. The project then compares the training times between Scikit-Learn and SnapML, highlighting the training speedup advantage of Snap ML.

## Author
- Deepraj Arya

## License
This project is licensed under the MIT License - 

## Project Files
- The provided code allows users to preprocess the dataset, build, train, and evaluate the Decision Tree Regressor models.
- It offers the flexibility to adjust model parameters, explore the dataset further, and experiment with different settings.

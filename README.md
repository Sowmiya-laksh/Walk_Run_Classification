> # Walk_Run_Classification
### Project Overview
This project aims to classify whether a person is walking or running based on sensor data from daily activities. Using motion sensor data, the goal is to create and evaluate machine learning models that accurately predict the type of activity being performed.

### Problem Statement
#### Task 1:
Prepare a complete data analysis report based on the provided dataset.

#### Task 2:
Create a predictive model to classify a person's activity (walking or running) using the given predictor variables.

### Dataset Description
The dataset consists of motion sensor readings recorded while users performed typical daily activities. The dataset is a subset of the original "Run or Walk" dataset and contains 11 attributes, including sensor data like acceleration and gyroscope readings. These features are used to classify the activity as either running or walking.

### Key Attributes:
- *date*: Date of the activity recording
- *time*: Time of the activity recording
- *username*: Username of the individual performing the activity
- *wrist*: Whether the sensor was on the wrist
- *activity*: The target variable indicating whether the activity is 'walk' or 'run'
- *acceleration_x*: Acceleration in the x-axis
- *acceleration_y*: Acceleration in the y-axis
- *acceleration_z*: Acceleration in the z-axis
- *gyro_x*: Gyroscope reading in the x-axis
- *gyro_y*: Gyroscope reading in the y-axis
- *gyro_z*: Gyroscope reading in the z-axis

### Solution Approach
- *Data Analysis and Preprocessing*: Prepare the dataset by cleaning and preprocessing, including handling missing values and normalizing sensor data.
- *Exploratory Data Analysis (EDA)*: Investigate the distribution of the features, visualize the data, and assess the relationship between sensor readings and activity types (walking or running).
- *Modeling*: Train various machine learning models such as Multilayer Neural Networks, Decision Trees, and Random Forest to predict whether a person is walking or running based on sensor readings.
- *Model Comparison*: Evaluate the performance of different models based on accuracy, precision, recall, and F1-score to identify the best-performing classifier.
- *Model Selection*: Select the most suitable model for production use based on the comparison of metrics.

### Challenges Faced
- Dealing with noisy sensor data and outliers.
- Managing the imbalanced nature of activities in the dataset, if applicable.
- Optimizing model hyperparameters to improve classification accuracy.
- Handling potential missing values or erroneous readings in the raw sensor data.

### Practice Skills
- Sensor data preprocessing and feature engineering.
- Building and evaluating neural networks and other classification models.
- Handling time-series data for activity recognition.
- Model evaluation techniques, including cross-validation and metric analysis.

### Model Comparison Report
This section contains a detailed comparison of multiple machine learning models applied to the data, with recommendations for the best model based on overall performance.

### Conclusion
This project demonstrates how motion sensor data can be used to classify daily activities such as walking and running. By comparing multiple models, the best-performing classifier will be identified for deployment.

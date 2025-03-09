# Industrial-Equipment-Fault-Detection-Machine-Learning-1-Capstone-Project
## Industrial Equipment Fault Detection Machine Learning 1 Capstone Project

## Project Summary
This project aims to develop a machine learning model for fault prediction in industrial equipment, leveraging a dataset that includes sensor measurements (temperature, pressure, vibration, humidity), equipment types, and locations. By addressing the limitations of traditional scheduled maintenance, the model seeks to enhance preventive maintenance strategies through accurate classification of equipment states. Using data-driven techniques, a classification approache will be explored, and model performance will be evaluated with metrics such as precision, recall, and F1-score to identify the most effective fault detection system. The ultimate goal is to optimize maintenance processes, reduce downtime, and improve industrial efficiency by demonstrating the potential of predictive analytics in enhancing the reliability of complex systems.

## OBJECTIVES
- Fault Detection: Develop a model that can accurately classify equipment as either operating normally or likely to experience a fault.
- Performance Evaluation: Evaluate and improve the model using performance metrics such as precision, recall, and F1-score to ensure reliable fault detection.

## METHODOLOGY
- Loading Libraries and Downloading the Dataset
- Exploratory Data Analysis: Explore data distribution, correlations, outliers, and class imbalance; visualize feature relationships with faulty.
- Data Preprocessing: Handle missing values, encode categorical variables (equipment, location), and scale numerical features; address class imbalance if needed.
- Modeling: Split data into train-test sets, and train using baseline model (Random Forest).
- Model Evaluation:  Assess performance with metrics like accuracy, precision-recall, F1-score, and ROC-AUC; analyze feature importance.
- Summarize Insights/findings.

## DATASET COLUMN INFORMATION
- Temperature: Temperature reading at the time of observation (in °C).
- Pressure: Pressure reading at the time of observation (in bar).
- Vibration: Vibration level reading (normalized units).
- Humidity: Humidity percentage recorded at the location of the equipment.
- Equipment: Type of industrial equipment being monitored (e.g., Turbine, Compressor, Pump).
- Location: Location of the equipment (city name).
- Faulty: Binary indicator (0 = Not Faulty, 1 = Faulty) specifyIng whether the equipment is functioning properly or requires maintenance.

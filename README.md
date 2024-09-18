Obesity Prediction Using Machine Learning
This project focuses on predicting obesity levels using a dataset of individual health-related features. It includes preprocessing steps, model training, evaluation, and result interpretation.

Project Overview
This machine learning project aims to predict obesity levels based on various health-related features such as age, weight, physical activity, and eating habits. A classification model is built and evaluated on the dataset to predict categories of obesity.

Dataset
The dataset contains the following features:

Gender: Male/Female
Age: Age of the individual
Height: Height in meters
Weight: Weight in kilograms
Family History of Overweight: Yes/No
FAVC: Frequent consumption of high-calorie food
FCVC: Frequency of vegetable consumption
NCP: Number of main meals
CAEC: Consumption of food between meals
SMOKE: Smoking habits
CH2O: Daily water intake
SCC: Monitoring of calorie consumption
FAF: Physical activity frequency
TUE: Time using technology devices
CALC: Alcohol consumption
MTRANS: Mode of transportation
Objective
Classification Problem: Predict different levels of obesity using the provided features.
Project Workflow
Data Preprocessing

Handling missing values
Encoding categorical variables
Standardizing numerical variables
Splitting data into training and testing sets
Modeling

A classification model (e.g., Logistic Regression, Random Forest) is trained on the preprocessed data.
Model Evaluation

The model is evaluated using metrics such as:
Accuracy
Precision
Recall
F1-Score
Results

The model achieved an accuracy score of 0.89 on the test set.
Detailed classification metrics are provided in the final report.
How to Run the Project
Install the dependencies:

bash
Copy code
pip install -r requirements.txt
Run the script:

bash
Copy code
python main.py
Evaluate the model: The evaluation report will be displayed with classification metrics.

Directory Structure
bash
Copy code
.
├── data
│   └── obesity_dataset.csv         # Dataset used for training
├── models
│   └── model.joblib                # Trained model file
├── src
│   ├── preprocessing.py            # Preprocessing pipeline
│   ├── train.py                    # Model training script
│   └── evaluate.py                 # Model evaluation script
├── README.md                       # Project documentation
└── requirements.txt                # Python dependencies
Dependencies
Python 3.x
Scikit-learn
Pandas
NumPy
Joblib
Conclusion
The model successfully predicts obesity levels with high accuracy. Further improvements can be made by testing different models, optimizing hyperparameters, or adding more features.


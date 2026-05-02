House Price Prediction Pipeline :-


1.Overview
Built an end-to-end Machine Learning pipeline to predict house prices using structured housing data. The project covers data preprocessing, model training, and inference in a production-like workflow.



2. Workflow
Performed Stratified Sampling based on income category for balanced train-test split
Built a data preprocessing pipeline using:
SimpleImputer (handling missing values)
StandardScaler (feature scaling)
OneHotEncoder (categorical encoding)
Combined transformations using ColumnTransformer
Trained a Random Forest Regressor for prediction
Saved model and pipeline using joblib


3. Inference Pipeline
Loaded trained model and preprocessing pipeline
Transformed new input data using the same pipeline
Generated predictions and saved results to output.csv


4. Tech Stack
Python
Pandas, NumPy
Scikit-learn
Joblib


5. Key Features
End-to-end ML pipeline (training + inference)
Handles missing and categorical data efficiently
Ensures consistent preprocessing using pipelines
Reusable and production-ready structure



6.Outcome
Developed a scalable ML system that automates preprocessing and prediction, ensuring consistency and reliability in real-world deployment scenarios.

🌾 Crop Recommendation System
This project is a Machine Learning-based system that recommends the most suitable crop to grow based on environmental and soil conditions. It is aimed at helping farmers and agricultural planners make data-driven decisions to improve productivity.

📌 Project Objective
To build a predictive model that recommends the best crop to grow using parameters like:

Nitrogen (N)

Phosphorus (P)

Potassium (K)

Temperature

Humidity

pH level

Rainfall

🚀 Technologies Used
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Machine Learning Models:
K-Nearest Neighbors (KNN)
Decision Tree Classifier
Data Preprocessing:
StandardScaler for feature scaling
RandomOverSampler to balance the dataset
Optuna for hyperparameter tuning
Visualization: Matplotlib, Seaborn

📊 Dataset
The dataset was obtained from Kaggle, containing over 2,200+ samples of soil and climate features labeled with crop names. It includes:
Feature	Description
N	Nitrogen content in soil
P	Phosphorus content in soil
K	Potassium content in soil
temperature	Temperature in °C
humidity	Relative humidity in %
ph	pH value of the soil
rainfall	Rainfall in mm
label	Crop name (target variable)
📈 Model Performance

Achieved ~98% accuracy using KNN after tuning
Precision, Recall, and F1-score: 98% (macro average)
Balanced the dataset using RandomOverSampler to handle class imbalance
Used StandardScaler to standardize features and reduce outlier effects
Applied Optuna to tune hyperparameters for optimal performance

Example input:
input = [90, 42, 43, 20.8, 82.0, 6.5, 202.9]
Output:
Recommended Crop: rice

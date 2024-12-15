# Release Speed Prediction for Clayton Kershaw
The goal of this project is to develop a machine learning model to predict release speed for Clayton Kershaw. He is regarded as one of the best pichers in baseball history.<br>
This dataset resource is Statsvant: https://baseballsavant.mlb.com/statcast_search and collected by Statcast system. The dataset is based on group ID (different pitch type). Thus, this dataset is not iid.<br>
For splitting, I used GroupShuffleSplit() and GroupKFold(). <br>
For preprocessing, I used OneHotEncoder and StandardScaler to tranform the dataset.<br>
Created a ML pipeline to train some ML algorithms with tuning many parameters and found the best model for the project. The best model is XGBoost and I used XGBoost for further analysis and evaluation.

## Repository organization is as follows:

- data/ - Stores dataset.
- figures/ - Stores all figures
- results/ - Stores best model and predictions
- report/ - Stores final report
- src/ - Stores the code for the project

## The packages I used in this project:
- Python version is 3.12.5
- numpy version 1.26.4 is installed.
- matplotlib version 3.9.2 is installed.
- sklearn version 1.5.1 is installed.
- pandas version 2.2.2 is installed.
- xgboost version 2.1.1 is installed.
- shap version 0.45.1 is installed.
- plotly version 5.23.0 is installed.


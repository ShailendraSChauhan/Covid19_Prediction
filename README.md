 Project Proposal for COVID19 prediction
# COVID-19 Prediction Project

## Overview
This project aims to predict COVID-19 test results based on various features such as symptoms, age, and contact history. The dataset includes information about individuals who underwent the RT-PCR test from 11th March 2020 to 30th April 2020.

## Dataset
- The dataset contains 11 columns, including features suspected to play a role in predicting COVID-19 outcomes.
- The target variable is 'Corona,' indicating test results as 'positive,' 'negative,' or 'other.'
- There are 2,78,848 individuals in the dataset.

## Project Structure
- **covid.ipynb**: Jupyter notebook for data preprocessing, handling missing values, and encoding.
- **Covid.ipynb**: Jupyter notebook for training and evaluating machine learning models.
- **README.md**: Project documentation.

## Data Preprocessing
- Features such as symptoms and contact history are encoded.
- Target variable 'Corona' is encoded as 'positive,' 'negative,' and 'other.'

## Model Training
- Five machine learning models are trained: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting, SVM.
- Model performance is evaluated on the validation set.
- The best-performing model is selected based on accuracy.

## Requirements
- Python 3.7
- Jupyter Notebook
- Required Python packages are specified in `Requirements.txt`. Install them using: # COVID-19 Prediction Project

## Overview
This project aims to predict COVID-19 test results based on various features such as symptoms, age, and contact history. The dataset includes information about individuals who underwent the RT-PCR test from 11th March 2020 to 30th April 2020.

## Dataset
- The dataset contains 11 columns, including features suspected to play a role in predicting COVID-19 outcomes.
- The target variable is 'Corona,' indicating test results as 'positive,' 'negative,' or 'other.'
- There are 2,78,848 individuals in the dataset.

## Project Structure
- **data_processing.ipynb**: Jupyter notebook for data preprocessing, handling missing values, and encoding.
- **model_training.ipynb**: Jupyter notebook for training and evaluating machine learning models.
- **Covid EDA Report.html**: EDA html file using ydata-profiling(pandas-profiling)
- **README.md**: Project documentation.

## Data Preprocessing
- Features such as symptoms and contact history are encoded.
- Target variable 'Corona' is encoded as 'positive,' 'negative,' and 'other.'

## Model Training
- Four machine learning models are trained: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
- Model performance is evaluated on the validation set.
- The best-performing model is selected based on accuracy.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python packages are specified in `requirements.txt`. Install them using pip install -r requirements.txt


## Results
- The best model achieved an accuracy of [0.9837] on the test set.


Feel free to customize this based on your specific project details and requirements.


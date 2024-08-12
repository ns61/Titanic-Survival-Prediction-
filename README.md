# Titanic Survival Prediction

This repository contains a machine learning project that predicts the survival of passengers aboard the Titanic using a logistic regression model.

## Project Overview

The objective of this project is to develop a predictive model that determines whether a passenger survived the Titanic disaster based on several key features such as age, gender, passenger class, and more. The model is built using Python and employs data cleaning, feature engineering, and model evaluation techniques.

## Dataset

The dataset used in this project is the classic Titanic dataset, which includes the following features:

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (1 = Survived, 0 = Did not survive).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard the Titanic.
- **Parch**: Number of parents/children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Project Structure

- **Titanic Survival Prediction.ipynb**: Jupyter notebook containing the entire project code, including data loading, cleaning, model training, and evaluation.
- **README.md**: Project documentation.

## Installation

To run this project locally, you'll need to install the necessary Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## How to Use

1. Clone this repository to your local machine.
2. Open the `Titanic Survival Prediction.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Run the notebook cells to execute the code.

## Model

The model used in this project is a logistic regression model. The following steps were taken to develop and evaluate the model:

1. **Data Cleaning**: Handling missing values and converting categorical variables.
2. **Feature Selection**: Choosing relevant features for model training.
3. **Model Training**: Training the logistic regression model using Scikit-learn.
4. **Model Evaluation**: Evaluating the model’s performance using accuracy score and other metrics.

## Results

The model achieved a reasonable accuracy, providing insights into the factors that influenced survival during the Titanic disaster.

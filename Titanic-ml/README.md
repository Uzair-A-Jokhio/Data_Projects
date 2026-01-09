# Titanic Survival Prediction

This project is a classic machine learning problem from Kaggle's "Titanic: Machine Learning from Disaster" competition. The goal is to predict whether a passenger on the Titanic survived or not, based on a given set of features.

## Project Overview

This is a binary classification problem where the task is to predict `1` for survived and `0` for deceased. The project involves a complete machine learning workflow from data exploration to model building.

## The Notebook: `titanic-ml.ipynb`

The `titanic-ml.ipynb` notebook contains the full analysis and modeling process, including:

-   **Exploratory Data Analysis (EDA):**
    -   Analyzing the distribution of passengers who survived vs. those who did not.
    -   Investigating the relationship between survival and various features like `Sex`, `Pclass`, `Age`, `Embarked`, `SibSp` (number of siblings/spouses aboard), and `Parch` (number of parents/children aboard).
    -   Visualizing these relationships using `matplotlib` and `seaborn`.

-   **Feature Engineering:**
    -   Creating a new feature called `Initial` by extracting titles (e.g., Mr., Mrs., Miss) from the `Name` column. This helps in handling missing `Age` values more effectively.

-   **Data Preprocessing:**
    -   **Handling Missing Values:**
        -   Imputing missing `Age` values by using the mean age of passengers with the same title.
        -   Filling missing `Embarked` values with the most frequent port of embarkation.
    -   Converting categorical features (like `Sex`, `Embarked`, `Initial`) into numerical format suitable for machine learning models.

-   **Modeling (Inferred):**
    -   The notebook likely proceeds to train and evaluate several classification models such as:
        -   Logistic Regression
        -   Support Vector Machines (SVM)
        -   Decision Trees
        -   Random Forests
        -   Gradient Boosting models.
    -   The performance of these models would be evaluated using metrics like accuracy.

## Dataset

The project uses the `train.csv` and `test.csv` files provided by the Kaggle Titanic competition.

## Dependencies

-   `numpy`
-   `pandas`
-   `matplotlib`
-   `seaborn`
-   `scikit-learn` (inferred for modeling)

You can install these dependencies using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

1.  Clone this repository.
2.  Make sure you have the `train.csv` and `test.csv` files in the same directory or update the file paths in the notebook.
3.  Open and run the `titanic-ml.ipynb` notebook in a Jupyter environment.

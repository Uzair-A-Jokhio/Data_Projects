# California Housing Prices Prediction

This project aims to predict California housing prices using machine learning techniques. It explores the California Housing dataset, performs data analysis, preprocesses the data, and builds predictive models to estimate median house values.

## Project Overview

The main steps covered in this project typically include:

-   **Data Acquisition:** Downloading and loading the California Housing dataset.
-   **Exploratory Data Analysis (EDA):**
    -   Understanding the dataset structure and features.
    -   Visualizing geographical data and other key distributions.
    -   Identifying correlations between features and the target variable (median house value).
-   **Data Preprocessing:**
    -   Handling missing values (e.g., imputation).
    -   Feature engineering (e.g., creating new features from existing ones).
    -   Scaling numerical features.
    -   Encoding categorical features.
-   **Model Training:**
    -   Training various regression models (e.g., Linear Regression, Decision Trees, Random Forests, Support Vector Machines, Gradient Boosting models) to predict housing prices.
-   **Model Evaluation:**
    -   Assessing model performance using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared.
-   **Hyperparameter Tuning:**
    -   Optimizing model parameters to improve prediction accuracy.

## Dataset

The dataset used is the California Housing dataset, commonly used for regression tasks. It contains various features related to housing districts in California. The notebook seems to download this data from a public GitHub repository.

## Dependencies

The project typically uses the following Python libraries for data manipulation, visualization, and machine learning:

-   `pandas`
-   `numpy`
-   `matplotlib`
-   `seaborn`
-   `scikit-learn`
-   `urllib` (for data download)
-   `os`, `tarfile` (for handling data files)

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1.  Clone this repository.
2.  Open and run the `california-housing-prices.ipynb` notebook in a Jupyter environment (e.g., Jupyter Notebook, JupyterLab, VS Code with Python extension). The notebook handles the data download automatically.
3.  Follow the steps in the notebook to execute the data analysis, preprocessing, and model training.


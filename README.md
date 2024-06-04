# Multiple Linear Regression and Residual Analysis

## Overview

This project performs multiple linear regression and residual analysis on a dataset. The analysis aims to explore relationships between various predictors and the target variable, and to validate the assumptions of linear regression through comprehensive residual diagnostics.

## Table of Contents

- [Overview]
- [Tools and Libraries]
- [Project Structure]
- [Data]
- [Usage]
- [Results]
- [Contributing]
- [License]

## Tools and Libraries

The following libraries are used in this project:
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Numpy
- Scipy
- Statsmodels

## Project Structure

The notebook is divided into several sections:
1. **Importing Libraries**
2. **Loading and Viewing the Dataset**
3. **Exploratory Data Analysis (EDA)**
4. **Visualization**
5. **Model Building**
6. **Residual Analysis**
    - Standardization
    - Residual Plots
    - Normality of Residuals
    - Independence of Residuals
    - Leverage and Influence
    - Autocorrelation

## Data

The dataset used for this analysis is `Life Expectancy Data.csv`, which contains various health, economic, and demographic indicators. The target variable is life expectancy.

## Usage

To run the analysis, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Navigate to the project directory:
    ```sh
    cd your-repo-name
    ```
3. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebook:
    ```sh
    jupyter notebook 23122101_CIA3.ipynb
    ```

## Results

The notebook provides a comprehensive analysis, including:
- Exploratory Data Analysis and visualization of key variables.
- Model building using multiple linear regression.
- Detailed residual analysis to validate model assumptions, including:
    - Standardization of residuals
    - Residual plots for predicted vs. actual values, standardized residuals vs. predicted values, etc.
    - Normality tests using Q-Q plots, P-P plots, histograms, and Shapiro-Wilk test.
    - Independence tests using the Durbin-Watson test.
    - Leverage and influence diagnostics including Cook's Distance.
    - Autocorrelation plots.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.
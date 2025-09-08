# 🏡 Housing Price Prediction

##  Overview

This project predicts **California housing prices**
(`median_house_value`) using features such as rooms, population,
households, and location.\
It includes **EDA, feature engineering, preprocessing, regression
models, and evaluation**.

------------------------------------------------------------------------

##  Requirements

``` bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

------------------------------------------------------------------------

##  Workflow

-   **Prep & EDA**: clean data, visualize distributions & correlations.\
-   **Features & Preprocessing**: log transforms, ratios, one-hot
    encoding.\
-   **Modeling**: Linear Regression (baseline), Random Forest (better),
    GridSearchCV (best).\
-   **Evaluation**: R², RMSE, actual vs predicted plots.

------------------------------------------------------------------------

##  Results

-   **Linear Regression**: simple baseline.\
-   **Random Forest**: higher accuracy.\
-   **Best Random Forest**: best overall after tuning.

------------------------------------------------------------------------

##  Project Structure

    housing.csv
    housing.py
    README.md

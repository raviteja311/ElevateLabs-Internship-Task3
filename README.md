# Housing Price Prediction (Linear Regression)

This project uses a simple Linear Regression model to predict house prices using the `Housing.csv` dataset.

## What it Does

The code in the `Task3.ipynb` notebook does the following:

1.  **Loads Data:** Reads the `Housing.csv` file.
2.  **Cleans Data:** Removes potential outliers (unusual values) from the price, area, and parking columns.
3.  **Prepares Data:** Converts text categories (like 'yes'/'no') into numbers and scales numerical features so the model can use them effectively.
4.  **Splits Data:** Divides the data into a training set (to teach the model) and a testing set (to check how well it learned).
5.  **Trains Model:** Builds a Linear Regression model using the training data.
6.  **Evaluates Model:** Checks the model's accuracy on the test data using common metrics (MAE, MSE, R²).
7.  **Visualizes:** Shows plots comparing the actual prices to the prices predicted by the model, and which features influence the price the most.

## Requirements

You need Python and these libraries:

*   pandas
*   numpy
*   scikit-learn
*   matplotlib
*   seaborn

Install them using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab


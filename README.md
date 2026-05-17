# Paris Housing

Machine learning task using the `ParisHousing.csv` dataset to predict house prices.

## Description

This project explores a housing dataset and trains a simple Linear Regression model to predict the price of a house based on features such as size, number of rooms, yard, pool, floors, garage, and other property details.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset

The dataset file used in this project is `ParisHousing.csv`.

The target column is `price`.

## How to Run

1. Place `ParisHousing.csv` in the same folder as the notebook.
2. Install the required libraries:

    pip install pandas numpy matplotlib scikit-learn

3. Open and run the notebook:

    jupyter notebook paris_housing.ipynb

## Model

The project uses a Linear Regression model. The data is split into training and testing sets, then the model is trained and evaluated using R² score, Mean Absolute Error, and Root Mean Squared Error.

## Conclusion

The model performs very well because the dataset has a strong relationship between house features and price. The most important feature for predicting price is the size of the house in square meters.
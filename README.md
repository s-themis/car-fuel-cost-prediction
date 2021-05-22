# Car-Fuel-Cost-Prediction

This is a regression problem, where given various vehicle characteristics we predict the fuel cost at 12,000 miles.

## Dataset

The dataset is taken from: https://github.com/amercader/car-fuel-and-emissions

## Modelling

* Manual feature selection through data exploration with Pandas.
* Handling of missing values with imputation.
* Scaling numerical features and one-hot encoding categorical features.
* Composition of imputation, preprocessing and regression as a single pipeline with scikit-learn Pipelines and ColumnTransformer.
* Model selection.

## How to run the notebook.

Create and activate a virtual environment.
```
$ python -m venv venv
$ source venv/bin/activate
```

Install the dependencies.
```
$ pip install -r requirements.txt
```

Launch a JupyterLab server.
```
$ jupyter-lab
```
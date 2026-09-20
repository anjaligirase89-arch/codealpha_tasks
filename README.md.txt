# Iris Flower Classification using Machine Learning

## Overview

This project uses Machine Learning to classify Iris flowers into three species: **Iris-setosa, Iris-versicolor, and Iris-virginica** based on sepal and petal measurements.

## Objective

* Understand basic Machine Learning classification.
* Train a model using the Iris dataset.
* Predict Iris flower species from measurements.
* Evaluate model performance using test data.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook
* Decision Tree Classifier

## Dataset

The dataset contains **150 Iris flower samples** with four features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

## Model

A **Decision Tree Classifier** was trained using an **80/20 train-test split**:

* Training samples: 120
* Testing samples: 30

## Result

The model achieved **100% accuracy on the selected test split**.

Confusion Matrix:

```text
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
```

## Project Structure

```text
Iris-Flower-Classification/
├── Iris_Flower_Classification.ipynb
├── Iris.csv
├── requirements.txt
└── README.md
```

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Open the notebook in Jupyter:

```bash
jupyter notebook
```

Then open `Iris_Flower_Classification.ipynb` and run the cells in order.

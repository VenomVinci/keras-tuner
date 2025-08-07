
# Automating Hyperparameter Tuning with Keras Tuner

This repository demonstrates how to automate the process of hyperparameter tuning for a neural network model using [Keras Tuner](https://keras.io/keras_tuner/). The project focuses on classifying diabetes onset based on diagnostic measurements using the Pima Indians Diabetes dataset.

## Dataset

The dataset used in this project is the **Pima Indians Diabetes Database** sourced from Kaggle:

* [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

It contains several diagnostic measurements for female patients of Pima Indian heritage, aimed at predicting the onset of diabetes.

## Project Overview

* Build a neural network model using TensorFlow/Keras.
* Use Keras Tuner to automatically search for optimal hyperparameters such as the number of layers, units per layer, and learning rate.
* Evaluate the model using accuracy and loss metrics on training and validation sets.

## Results

* **Training Accuracy:** 0.8502
* **Training Loss:** 1.2446
* **Validation Accuracy:** 0.6688
* **Validation Loss:** 1.6125

These metrics indicate that the tuned model achieves reasonable accuracy but may be overfitting, as seen from the difference between training and validation accuracy.

## Getting Started

### Requirements

* Python 3.x
* TensorFlow
* Keras Tuner
* pandas
* scikit-learn

Install dependencies via pip:

```bash
pip install tensorflow keras-tuner pandas scikit-learn
```

## References

* [Keras Tuner Documentation](https://keras.io/keras_tuner/)
* [Pima Indians Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)


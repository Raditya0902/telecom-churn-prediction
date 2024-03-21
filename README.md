# Telecom Churn Prediction

This project aims to predict customer churn in a telecom company using machine learning techniques, particularly a neural network model built with TensorFlow/Keras.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview

Customer churn, or the rate at which customers stop doing business with a company, is a critical metric for telecom companies. Predicting churn can help identify at-risk customers and take proactive measures to retain them. In this project, we employ machine learning techniques to predict churn based on various customer attributes.

## Dataset

The dataset used for this project is stored in a CSV file named `customer_churn.csv`. It contains information about telecom customers, including features such as tenure, monthly charges, contract type, internet service, etc.

## Preprocessing

- Handling Missing Values: Missing values in the 'TotalCharges' column are handled by coercing them to numeric and removing rows with missing values.
- Encoding Categorical Variables: Categorical variables are converted into numerical format using one-hot encoding.
- Scaling Features: Numerical features are scaled using Min-Max scaling to ensure uniformity.

## Model Training

We train a neural network model using TensorFlow/Keras. The model architecture consists of an input layer, hidden layers with ReLU activation, and an output layer with a sigmoid activation function.

## Evaluation

The model is evaluated on a test set using metrics such as accuracy, precision, recall, and F1-score. Confusion matrix is also generated to visualize the model performance.

## Usage

To use this project:

1. Ensure you have Python installed on your system.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the provided Python script to preprocess the data, train the model, and evaluate its performance.

## Dependencies

- pandas
- matplotlib
- numpy
- scikit-learn
- TensorFlow
- Keras

## Contributing

Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

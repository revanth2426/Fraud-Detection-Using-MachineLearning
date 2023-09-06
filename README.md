# Fraud Detection Using Machine Learning

## Overview

This project is a fraud detection system using machine learning techniques. It allows users to input transaction data and determine whether the transaction is fraudulent or legitimate. The project is implemented as an interactive web application using the Streamlit library.

## Prerequisites

Before running the project, make sure you have the following Python libraries installed:

- [Streamlit](https://streamlit.io/): A Python library used for building interactive web applications for data science and machine learning projects.

- [scikit-learn](https://scikit-learn.org/stable/): A Python library for machine learning and data mining.

- [Joblib](https://joblib.readthedocs.io/en/latest/): A Python library for efficient tools for saving and loading Python objects.

## Getting Started

1. **Obtain the Dataset:** Download the dataset from Kaggle using the provided link:
 [Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

2. **Data Processing:** Upload the dataset to a Jupyter notebook and perform necessary data operations.

3. **Save Model:** Save the Jupyter notebook with all relevant information and use Joblib to dump the model in .pkl format. This file contains the trained model and preprocessing steps.

4. **Run the Interface:** Upload the .pkl file to the `Interface.py` file, which utilizes Streamlit to create a user interface. Run the interface by executing the following command in the terminal:

5. **Detect Fraud:** Enter encrypted values for each data entry in the provided form on the interface. Click the "detect" button to determine whether the transaction is fraudulent or legitimate.

## Dataset Source

The dataset used in this project can be found on Kaggle:
[Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Credits

This project was created by Desavath Revanth Naik and is available on GitHub: [GitHub Repository](https://github.com/revanth2426/Fraud-Detection-Using-MachineLearning).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

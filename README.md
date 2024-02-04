# Fraudulent Credit Card Transaction Detection using XGBoost

## Overview

This Python notebook demonstrates a fraudulent detection model developed for a dataset containing credit card transaction details. Similar to a previous implementation using neural networks, this model uses XGBoost, a popular gradient boosting library. The dataset features were anonymized due to regulatory requirements. This model achieved an accuracy of 99.8% on the unseen test set, which is an improvement on the neural nets implementation that achieved 97.38% accuracy.

- **Neural nets implementation:** [Fraudulent Credit Card Transaction Detection using PyTorch](https://github.com/GraphicsMonster/fraud-detection-with-neural-nets--kaggle-dataset)

## Model Architecture

The XGBoost model is known for its ensemble learning capabilities and is particularly effective in tabular data scenarios. The model is configured with default hyperparameters, and no extensive tuning is performed due to the impressive out-of-the-box performance.

## Features

- **Anonymized Feature Engineering:** The model showcases the capability to engineer relationships between anonymized features, demonstrating the ability to learn patterns without explicit knowledge of individual feature meanings.

- **Tabular Data Handling:** XGBoost excels in handling tabular data, making it suitable for credit card transaction datasets.
  
- **High Accuracy:** The model achieved a high accuracy of 99.8% on the unseen data(test set).

## Dependencies

- Python 3.x
- PyTorch
- pandas
- scikit-learn

Ensure the required packages are installed using:

```bash
pip install torch pandas scikit-learn

```

## Result

- **Test Set Accuracy:** 99.8%
- Can't test the model on a validation set since the data is anonymized and hence it's difficult to synthesize a validation set.

## Acknowledgments

- Dataset source -- [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023)

## License

This project is licensed under the [MIT License.](https://choosealicense.com/licenses/mit/)
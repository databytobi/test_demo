# Breast Cancer Classification with Scikit-learn

This project uses Scikit-learn's built-in breast cancer dataset to build and evaluate classification models that differentiate between malignant and benign cases. The dataset provides an excellent opportunity to experiment with machine learning techniques and evaluate model performance using various metrics.

---

## Overview

The project focuses on building classification models using the following algorithms:
- Decision Tree Classifier
- Logistic Regression

Evaluation metrics are used to measure the performance and effectiveness of the models.

---

## Libraries and Tools Used

The following libraries from Scikit-learn are used in this project:

- **Models:**
  - `DecisionTreeClassifier`
  - `LogisticRegression`

- **Metrics:**
  - `accuracy_score`
  - `classification_report`
  - `confusion_matrix`
  - `precision_score`
  - `roc_curve`, `auc`, `roc_auc_score`

---

## Features

- Load and preprocess the breast cancer dataset.
- Train classification models to predict malignant vs. benign cases.
- Evaluate the models using multiple performance metrics, including ROC curve and AUC score.

---

## Installation

### Prerequisites

Make sure you have Python installed along with the required libraries. You can install the dependencies using the following command:

```bash
pip install -U scikit-learn numpy pandas matplotlib
```

---

## Usage

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/databytobi/breast-cancer-classification.git
   ```
2. Run the script to build and evaluate the models:
   ```bash
   python main.py
   ```

---

## Evaluation Metrics

The project evaluates the models using the following performance metrics:
- **Accuracy Score**: Overall accuracy of predictions.
- **Classification Report**: Summary of precision, recall, and F1-score.
- **Confusion Matrix**: Visualization of true positives, true negatives, false positives, and false negatives.
- **Precision Score**: Measure of the model's ability to correctly predict positive cases.
- **ROC Curve & AUC**: Measure of the model’s ability to distinguish between classes.

---

## Project Structure

```
breast-cancer-classification/
│
├── data/                  # Dataset files (if applicable)
├── notebooks/             # Jupyter notebooks for exploration and visualization
├── src/                   # Source code
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── tests/                 # Unit tests
├── main.py                # Main script to run the project
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## Contributing

Contributions are welcome! If you have ideas for improvements or additional features, please feel free to submit a pull request or open an issue.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Scikit-learn for providing the breast cancer dataset and machine learning tools.

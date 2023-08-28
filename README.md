# Email Classification

Email Classification is a machine learning project aimed at classifying emails into categories such as spam or ham (not spam). We use various text-processing techniques and classifiers to achieve this.

## Features

1. **Data Cleaning**: Removing special characters and converting text to lowercase for uniformity.
2. **Feature Engineering**: Use of the `TfidfVectorizer` to convert the raw email text into a numerical feature vector.
3. **Classifier**: Used `RandomForestClassifier` with hyperparameter tuning.
4. **Evaluation Metrics**: Provides accuracy, precision, recall, F1-score, and a confusion matrix for model evaluation.

## Getting Started

### Prerequisites

The following Python libraries are required:

- pandas
- scikit-learn
- re
- os

You can install these using pip:

```bash
pip install pandas scikit-learn
```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/Damilola-Yinusa/email-classification.git
```

2. Navigate to the project directory and run the script:

```bash
cd email-classification
python email_classifier.py
```

### Dataset

The model is trained on a dataset named `spam_ham_dataset.csv` which should be placed in the root directory.

## Contributions

Feel free to fork the project, make a pull request, or suggest any other enhancements.

## License

This project is licensed under the MIT License.

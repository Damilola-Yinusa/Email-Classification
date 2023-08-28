Email Classification

Overview

This project aims to classify emails into different categories, such as spam or not-spam, using machine learning techniques. The primary goal is to accurately identify spam emails to improve email filtering systems.

Technologies Used
Python 3
scikit-learn
pandas
re (regular expressions)

Features
Data Cleaning: Removing special characters and converting text to lowercase.
Text Vectorization: Converting text to numerical data using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
Model: Using Random Forest Classifier with hyperparameter tuning via GridSearchCV.
Evaluation: Metrics used for evaluating the model include Accuracy, Precision, Recall, and F1-score.

How to Set Up and Run the Project
Prerequisites
Python 3.x
pip (Python package installer)
Installation Steps

Clone the GitHub repository:
bash
Copy code
git clone https://github.com/Damilola-Yinusa/email-classification.git
Navigate to the project folder and install the required packages:

bash
Copy code
cd email-classification
pip install -r requirements.txt
Running the Project
After installation, you can run the project using:

Copy code
python email_classification.py
This will train the model on the dataset and output evaluation metrics like Accuracy, Precision, Recall, and F1-Score.

Dataset
The dataset spam_ham_dataset.csv should be placed in the project root directory. The dataset should contain two columns:

Autor
Damilola Yinusa

License
This project is licensed under the MIT License. See the LICENSE.md file for details.

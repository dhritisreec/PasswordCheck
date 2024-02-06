# PasswordCheck
This project implements a password strength classifier using machine learning techniques. The primary goal is to assess the strength of passwords and categorize them into three classes: Weak, Strong, and Very Strong. The classification is performed using logistic regression, and the textual data of passwords is converted into numerical features using TF-IDF vectorization.

## Key Features

**Data Processing:** The dataset is processed to handle missing values, and the passwords are shuffled for robust model training.

**TF-IDF Vectorization:** The project utilizes the TF-IDF vectorization technique to convert textual password data into a numerical format suitable for machine learning models.

**Model Training:** A logistic regression model is trained on the processed data to learn the relationships between password characteristics and their strength levels.

**User Interaction:** The project includes a feature for users to input a password, and the trained model predicts its strength level (Weak, Strong, or Very Strong).

**Model Evaluation:** The effectiveness of the model is assessed using evaluation metrics such as confusion matrix, accuracy score, and a classification report.

## Getting Started

To use the project, follow the installation instructions in the README. After installation, you can explore the Jupyter Notebook to understand the code, train the model, and evaluate its performance. The provided Python script allows users to interactively check the strength of their passwords.

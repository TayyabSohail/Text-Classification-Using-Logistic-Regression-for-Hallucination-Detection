# Text-Classification-Using-Logistic-Regression-for-Hallucination-Detection
# Hallucination Detection Using Logistic Regression

This project aims to detect hallucinations in text by classifying summaries as either factual or hallucinated using a logistic regression model implemented from scratch. The Bag of Words (BoW) approach is utilized for feature extraction from the text data, leveraging the XSum Hallucination dataset to demonstrate effective text classification techniques.

# Features
Binary Classification: Classifies text as factual or hallucinated.
Bag of Words (BoW): Transforms text into a numerical representation for model training.
Custom Logistic Regression: Logistic regression model implemented without external libraries.
Model Evaluation: Comprehensive evaluation using metrics like accuracy, precision, recall, and F1 score.
Cross-Validation: Implements k-fold cross-validation to ensure model robustness.
Error Analysis: Identifies and analyzes misclassified instances to improve model performance.

# Dataset
XSum Hallucination Dataset: XSum Hallucination Annotations
Uses the summary field as input text and is_factual as the label.

# Tools and Technologies
Programming Language: Python

# Libraries:
pandas: For data handling
NumPy: For numerical operations
scikit-learn: For evaluation metrics and cross-validation

# Getting Started
Clone the repository.
Install the required libraries.
Load the dataset and run the provided scripts to train and evaluate the model.

# Results

## Detailed evaluation metrics (accuracy, precision, recall, F1 score).
![image](https://github.com/user-attachments/assets/fc30eed3-b2a9-4ab4-9630-6eb9c8196197)


## Confusion matrix visualizing model performance.
![image](https://github.com/user-attachments/assets/9f3eae5f-cdd8-4625-8807-48c0891c2a1f)


## K-Fold Results
![image](https://github.com/user-attachments/assets/18151160-64ea-4682-8d32-6dc10dd8c6b7)


## Analysis of misclassified examples with suggested improvements.
![image](https://github.com/user-attachments/assets/e3b8741b-7a95-41c6-bbeb-d9785b6d995c)



# Contribution
Contributions are welcome! Feel free to open issues, submit feature requests, or make pull requests.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

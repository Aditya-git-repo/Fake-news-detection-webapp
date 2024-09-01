# Fake-news-detection-webapp
A web application that uses machine learning to detect fake news. It analyzes articles in real-time, classifying them as real or fake. Features include a user-friendly interface and high detection accuracy.

## Overview
This project aims to build a web application for detecting fake news using machine learning techniques. The application leverages the `TfidfVectorizer` for text vectorization and the `PassiveAggressiveClassifier` for classification. The dataset used for training and testing the model can be downloaded from Kaggle.

## Table of Contents
- Introduction
- Dataset
- Machine Learning Techniques
- Installation
- Usage
- Contributing
- License

## Introduction
Fake news has become a significant issue in the digital age, spreading misinformation and causing various negative impacts. This project aims to tackle this problem by using machine learning techniques to detect and classify fake news articles.

## Dataset
The dataset used for this project contains news articles labeled as real or fake. It includes features such as the title, text, subject, and date of the articles. You can download the dataset from Kaggle.

## Machine Learning Techniques
### TfidfVectorizer
The `TfidfVectorizer` is used to convert the text data into numerical data. It transforms the text into a matrix of TF-IDF (Term Frequency-Inverse Document Frequency) features. This helps in understanding the importance of a word in a document relative to a collection of documents (corpus).

### PassiveAggressiveClassifier
The `PassiveAggressiveClassifier` is used for classification. It is an online learning algorithm that remains passive for a correct classification and becomes aggressive when there is a misclassification. This makes it suitable for large-scale learning and real-time applications.

## Installation
To run this project, you need to have Python installed along with some necessary libraries given in the code.

## Usage
1. Download the dataset from Kaggle and place it in the project directory.

2. Run the application:
    ```
    python app.py
    ```

3. Open your web browser and go to `http://localhost:5000` to access the web application.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

# Fake News Detection Using Data Science

## Introduction
This project aims to detect fake news using data science techniques. The main goal is to build and evaluate machine learning models that can accurately classify news articles as fake or true based on their content.

## Dependencies and Setup
To run this project, you'll need the following dependencies:
- pandas
- numpy
- scikit-learn

You can set up the required environment using Anaconda or pip. Make sure you have Jupyter Notebook installed to execute the code.

## Dataset Information
We use two datasets for this project: "fake.csv" and "true.csv." The datasets contain news articles along with their titles, text, subjects, and dates. We merge these datasets to create a complete dataset for classification.

## Data Preprocessing
We preprocess the data by adding a "class" label (0 for fake, 1 for true) to each article. The text column is cleaned using various preprocessing techniques such as converting to lowercase, removing special characters and URLs, etc.

## Model Training and Evaluation
We train three classification models: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier. The models are evaluated using accuracy, and a detailed classification report is provided for each model's performance.

## Manual Testing
You can manually test the models using the provided functions "output_label" and "manual_testing." Simply enter a news article, and the models will predict whether it is fake or true.

## Conclusion
The models achieved high accuracy in detecting fake news. However, further improvements can be made to enhance their performance.

## Usage
1. Install the required dependencies.
2. Clone the repository.
3. Open the Jupyter Notebook "fake_news_detection.ipynb."
4. Run the cells sequentially to replicate the analysis.


## References
- "fake.csv" and "true.csv" datasets from https://www.kaggle.com/code/therealsampat/fake-news-detection/notebook

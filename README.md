
# SMS Text Classification

## Introduction
This project focuses on classifying SMS messages into three categories: Normal, Fraud/Scam, and Promotion. The goal is to build a machine learning model that can accurately classify these messages based on their content.

## Dataset
The dataset used for this project contains SMS messages labeled into three categories:
- SMS Normal
- SMS Fraud / Penipuan
- SMS Promo

## Requirements
To run the notebook and reproduce the results, the following libraries are required:
- pandas
- numpy
- matplotlib
- scikit-learn
- pickle

You can install the required libraries using the following command:
```
pip install pandas numpy matplotlib scikit-learn
```

## Data Preprocessing
The preprocessing steps include:
1. Loading the dataset.
2. Cleaning the text data (e.g., removing punctuation, converting to lowercase).
3. Tokenizing and vectorizing the text data using techniques like TF-IDF.

## Modeling
Several machine learning models were trained and evaluated in this project, including:
- Logistic Regression
- Naive Bayes
- Support Vector Machine
- Random Forest

## Evaluation
The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. Visualization techniques like confusion matrices and bar plots were used to present the performance of the models.

## Results
The best-performing model achieved an accuracy of X% on the test set. Detailed results and analysis are provided in the notebook.

## Conclusion
This project successfully demonstrated the process of building and evaluating a machine learning model for SMS text classification. Future work could include exploring more advanced techniques like deep learning and incorporating additional features.

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Open the Jupyter notebook and run all cells.

```
git clone <repository-url>
cd <repository-folder>
pip install -r requirements.txt
jupyter notebook SMS_Text_Classification.ipynb
```

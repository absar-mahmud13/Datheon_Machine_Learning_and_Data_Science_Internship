# Task 4: NLP Sentiment Classification Using TF-IDF

## Project Overview
This project uses Natural Language Processing (NLP) and machine learning to classify customer reviews as positive or negative. Text data is cleaned and transformed into TF-IDF features before training and evaluating sentiment classification models.

## Objectives
- Clean and preprocess raw review text.
- Convert text to lowercase and remove HTML tags and punctuation.
- Remove stopwords and optionally perform lemmatization.
- Extract numerical text features using `TfidfVectorizer(max_features=5000)`.
- Train Multinomial Naive Bayes and Logistic Regression classifiers.
- Evaluate models using accuracy, precision, recall, F1-score, and a confusion matrix.
- Create a `predict_sentiment()` function for custom user input.

## Dataset
**Customer / Product Review Sentiment Dataset**

Dataset source: [Download CSV](https://raw.githubusercontent.com/datasets/sample-reviews/main/sentiment_reviews.csv)

The dataset is intended for text-based sentiment classification. Verify the dataset columns and sentiment labels before running the notebook.

## Technologies Used
- Python
- Pandas and NumPy
- NLTK or regular expressions
- Scikit-learn
- TfidfVectorizer
- MultinomialNB
- LogisticRegression
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab

## Methodology
1. Load and explore the review dataset.
2. Handle missing review text and sentiment labels.
3. Clean and preprocess the text.
4. Split the dataset into training and testing sets.
5. Fit TF-IDF features on the training data.
6. Train Multinomial Naive Bayes and Logistic Regression models.
7. Compare model performance using classification metrics.
8. Visualize the confusion matrix and model comparison.
9. Implement `predict_sentiment()` to classify custom review text.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Repository Structure
```text
Task_4_NLP_Sentiment_Classification/
├── Task_4_NLP_Sentiment_TFIDF.ipynb
├── README.md
└── visualizations/
```

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if necessary.
3. Load the dataset from the provided source.
4. Run the notebook cells in order.
5. Test the `predict_sentiment()` function with custom reviews.

## Deliverables
- Jupyter Notebook containing the NLP pipeline.
- Accuracy and classification metric comparison.
- Confusion matrix visualization.
- Interactive custom-review sentiment prediction function.

## Author
Md. Absar

Machine Learning and Data Science Internship

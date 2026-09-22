# Sentiment Analysis

**Intern:** Dinesh Desale  
**Track:** Data Analytics  
**Task:** Level 1 – Task 4

## Objective

The objective of this task is to perform sentiment analysis on movie reviews and classify them as positive or negative using machine learning techniques.

## Dataset

- Dataset: IMDb Movie Reviews
- Total Reviews: 50,000
- After duplicate removal: 49,582 reviews
- Classes: Positive and Negative

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK
- WordCloud
- Google Colab

## Analysis Performed

- Dataset inspection and data quality checking
- Duplicate removal
- Text preprocessing
- TF-IDF feature extraction
- 80/20 train-test split
- Naive Bayes classification
- Logistic Regression classification
- Accuracy, Precision, Recall and F1-score evaluation
- Confusion Matrix
- WordCloud visualization
- Misclassified review analysis

## Model Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Naive Bayes | 85.37% | 84.92% | 86.14% | 85.53% |
| Logistic Regression | 88.53% | 87.51% | 89.99% | 88.74% |

## Key Insights

- 418 duplicate reviews were removed.
- TF-IDF was used to convert text into numerical features.
- Logistic Regression achieved 88.53% accuracy.
- Five misclassified reviews were examined for error analysis.
- Mixed opinions, context and ambiguous language can cause classification errors.

## Conclusion

This project demonstrates how machine learning can be used to classify movie reviews into positive and negative sentiment categories.

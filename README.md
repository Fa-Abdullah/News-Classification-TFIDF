# News Category Classification using TF-IDF & Logistic Regression

Classify news articles into 20 categories using the 20 Newsgroups dataset.

## Dataset

- Source: sklearn.datasets.fetch_20newsgroups
- Classes: 20 categories (e.g., politics, sports, religion, technology)
- Samples: ~18,000 documents

## Approach

- Text Vectorization: TF-IDF (Term Frequency – Inverse Document Frequency)
- Classifier: Logistic Regression (max_iter=1000)
- Train/Test Split: 80/20

## Results

- Classification report with precision, recall, F1-score for all 20 classes
- Per-class F1 scores visualized in a bar chart

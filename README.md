# Assignment Title
Twitter Sentiment Analysis on Samay Raina

## (1) Problem Statement
The task is to analyze tweets related to Samay Raina and classify them into positive, neutral, and negative sentiments.

## (2) Objective
- Build sentiment classification models
- Compare Naïve Bayes, Logistic Regression, and SVM
- Evaluate using precision and recall

## (3) Dataset
Source: Manually created dataset (simulated tweets)  
Features:
- text (tweet content)
- label (sentiment)  
Size: 100 tweets (80 train, 20 test)

## (4) Methodology
### Data Preprocessing
- Lowercasing
- Removing stopwords, symbols

### EDA
- Distribution of sentiments

### Model Building
- Naïve Bayes
- Logistic Regression
- SVM

### Evaluation
- Precision
- Recall
- F1-score
- Accuracy

## (5) Results
- SVM performed best (Accuracy: 65%)
- Logistic Regression had high precision but low recall
- Naïve Bayes showed moderate performance

## (6) How to Run
pip install -r requirements.txt  
python main.py

## (7) Conclusion
SVM is the best-performing model for this dataset. TF-IDF improves feature extraction, but dataset size limits performance.

## (8) Student's Details
Name:  Simra Sharif  
Roll No:  66
UIN:  231A058
YEAR: TE-AIDS

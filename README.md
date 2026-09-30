# Customer Product Review – Sentiment Analysis

Classifies Amazon product reviews as positive or negative and compares a baseline model with an improved one.

## Models
| Model | Features | Classifier |
|---|---|---|
| Baseline | Bag-of-Words (5k words) | Multinomial Naive Bayes |
| Improved | TF-IDF, 1-2 grams | Logistic Regression + GridSearchCV |

## Data
Amazon Polarity reviews from Hugging Face (`amazon_polarity`), sampled to 40,000 rows.
Fallback: UCI Sentiment Labelled Sentences (Amazon subset).

## Run
```bash
pip install -r requirements.txt
jupyter notebook Customer_Product_Review.ipynb
```
Or open in Google Colab and run all cells.

## Results
Fill in after running:

| Model | Accuracy | F1 |
|---|---|---|
| Baseline | | |
| Improved | | |

## Tech
Python, pandas, scikit-learn, seaborn, matplotlib

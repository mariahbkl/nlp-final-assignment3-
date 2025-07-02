# Sentiment Analysis - NLP Assignment

This notebook applies sentiment analysis techniques to a sample of 500 tweets using two different approaches:

1. **Lexicon-based method** with VADER from the `nltk` library
2. **Transformer-based method** using a pre-trained model from Hugging Face's `transformers` library

The goal is to identify the sentiment polarity (positive, neutral, or negative) of each tweet and compare the results of both methods.

---

## Files

- `sentiment_analysis.ipynb`: Main notebook with preprocessing, analysis and visualisation
- `tweets-data.csv`: Dataset containing the tweet contents

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload `tweets-data.csv` manually when prompted
3. Run the notebook to:
   - Clean the tweet text
   - Apply VADER sentiment analysis
   - Apply Transformers sentiment classification
   - Compare and visualise the results

---

##Output

- Sentiment labels from both VADER and Transformers
- Comparison matrix and bar charts of sentiment distribution


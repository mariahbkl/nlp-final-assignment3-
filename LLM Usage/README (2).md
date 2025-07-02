# LLM Usage - Email Classification

This notebook demonstrates how a pre-trained Large Language Model (LLM) can be used to classify emails as spam or ham using **prompt engineering**.

We use the `distilbert-base-uncased-finetuned-sst-2-english` model from Hugging Face and apply it to a sample of 200 real email messages.

---

##  Files

- `llm_classification.ipynb`: Notebook using a transformer pipeline for classification
- `spam.csv`: CSV file with email messages and labels

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload `spam.csv` manually when prompted
3. Run the notebook to:
   - Format prompt-based inputs
   - Apply the LLM to classify emails
   - Compare predictions to true labels
   - Compute classification accuracy

---

## Output

- Predicted labels: `spam` or `ham`
- Confusion matrix of true vs predicted labels
- Accuracy score of the model




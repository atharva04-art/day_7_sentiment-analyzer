# Day 7 - Sentiment Analysis Dashboard 🤖📊

This project uses Hugging Face Transformers (`distilBERT`) to perform **sentiment analysis** on a list of text inputs, then displays the results as a **bar chart** with confidence scores.

## 🔍 Features

- NLP model: `distilbert-base-uncased-finetuned-sst-2-english`
- Classifies text as **Positive** or **Negative**
- Bar chart with:
  - Text inputs on X-axis
  - Confidence scores on Y-axis
  - Green for positive, red for negative
- Clean layout with score labels on top

## 🧠 Tech Stack

- Python
- Jupyter Notebook
- Hugging Face `transformers`
- Matplotlib for visualization

## 📸 Preview

![Sentiment Bar Chart](screenshot.png) <!-- Replace with your screenshot filename -->

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install transformers matplotlib

📚 Learnings
Loading pretrained transformer models with Hugging Face

Running batch predictions with the pipeline

Bar chart visualizations for interpretability


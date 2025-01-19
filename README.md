# Sentiment Analysis with Hugging Face and LoRA

This repository contains a text classification pipeline for sentiment analysis using the Hugging Face Transformers library. The model is fine-tuned on a subset of the IMDb dataset to classify movie reviews as either Positive or Negative.

---

## Features

- **Pretrained Model**: Fine-tunes the `distilbert-base-uncased` model for sentiment analysis.
- **LoRA Fine-Tuning**: Efficient parameter updates using LoRA (Low-Rank Adaptation).
- **Evaluation**: Calculates accuracy as the evaluation metric.
- **Deployment**: Optionally push the model to Hugging Face Hub for reuse.

---

## Requirements

- Python 3.8+
- Transformers
- Datasets
- PEFT
- Evaluate
- Torch

Install dependencies using:
```bash
pip install transformers datasets evaluate peft

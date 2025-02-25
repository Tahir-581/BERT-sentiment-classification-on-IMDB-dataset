# BERT Sentiment Classification on IMDb Dataset

This repository contains code for training a **BERT-based** sentiment classification model using the **IMDb dataset**. The model is trained using the Hugging Face `transformers` library and visualized using Matplotlib.

## **Features**
- Utilizes **BERT-base-uncased** for sequence classification.
- Processes IMDb movie reviews and classifies them as **positive** or **negative**.
- **Automatic tokenization** using Hugging Face's `BertTokenizer`.
- **Trainer API** for efficient training and evaluation.
- **Visualization of training loss** over epochs.

## **Installation**
Before running the script, install the required dependencies:

```bash
pip install transformers datasets matplotlib numpy

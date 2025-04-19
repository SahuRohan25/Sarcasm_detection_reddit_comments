# Sarcasm Detection using Hierarchical BERT

## Overview
This project implements sarcasm detection using a Hierarchical BERT architecture, inspired by a research paper that combines the power of the BERT model with additional layers like BiLSTM and CNN. The aim is to classify text comments into sarcastic or non-sarcastic categories, addressing the challenge of understanding subtle language nuances.

## Research Paper
The methodology is based on the research paper: [A Large Self-Annotated Corpus for Sarcasm](https://aclanthology.org/2020.figlang-1.14.pdf).

## Key Highlights
- **Data Preprocessing**: Cleaning and preparing the dataset by removing unwanted characters, converting text to lowercase, and tokenizing the text using the BERT tokenizer.
- **Hierarchical Architecture**: Integrating BERT embeddings with advanced layers for sentence encoding, context summarization, and feature extraction.
- **Binary Classification**: Leveraging the processed data and hierarchical model to classify comments with high accuracy.

## Dataset
The dataset contains 1.3 million sarcastic comments from Reddit, which were scraped and labeled with a sarcasm tag. The dataset is available in the `train-balanced-sarcasm.csv` file.

### Acknowledgements
The data was gathered by Mikhail Khodak, Nikunj Saunshi, and Kiran Vodrahalli for their article "A Large Self-Annotated Corpus for Sarcasm".

## Requirements
- Python 3.x
- Libraries:
  - TensorFlow
  - Transformers
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn

You can install the required libraries using:
```bash
pip install tensorflow transformers pandas scikit-learn matplotlib seaborn

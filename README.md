# Sentiment Analysis on IMDB Reviews using BiLSTM

## Project Overview
This project implements a **Sentiment Analysis system** on the IMDB movie reviews dataset using a **Bidirectional LSTM (BiLSTM)** model. The model classifies movie reviews as **positive** or **negative** based on their text content. The system is built using **Python** and popular deep learning libraries such as **TensorFlow** and **Keras**.

The main goal is to demonstrate how BiLSTM networks can capture contextual information from both past and future words in a sentence, improving sentiment classification accuracy.

---

## Dataset
The project uses the **IMDB Dataset of 50,000 movie reviews**:
- [IMDB Dataset.csv](IMDB%20Dataset.csv) included in this repository.
- Balanced dataset: 25,000 positive and 25,000 negative reviews.
- Dataset pre-processing includes tokenization, padding, and train-test split.

---

## Requirements
Install the necessary Python libraries using `requirements.txt`:

```bash
pip install -r requirements.txt
# My Project

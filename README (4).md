# Part 3 - NLP and Sequence Modeling

## Project Overview
In this project, a basic NLP pipeline was created for text classification. The dataset contains customer support messages with sentiment labels. Different preprocessing and text vectorization techniques were used to prepare the text data for machine learning models.

---

## Dataset Information
The dataset contains customer support messages and their corresponding sentiment labels.

Main columns:
- customer_message
- sentiment_label

The goal of the project is to classify the sentiment of customer messages.

---

## Dataset Understanding
The dataset was explored to check:
- Number of records
- Class distribution
- Sample text messages
- Average text length
- Missing values

---

## Text Preprocessing
The following preprocessing steps were performed:
- Converted text into lowercase
- Removed special characters
- Tokenized text
- Removed stopwords
- Created cleaned text data

---

## Text Vectorization
TF-IDF Vectorization was used to convert text into numerical form. Text must be converted into vectors because machine learning models cannot directly understand raw text.

---

## Baseline Model
A Logistic Regression model was used as the baseline model for sentiment classification.

---

## Model Evaluation
The model was evaluated using:
- Classification Report
- Confusion Matrix
- Accuracy metrics

---

## Sequence Model Concept
An LSTM sequence model was explained for handling sequential text data.

Main layers:
- Input Layer
- Embedding Layer
- LSTM Layer
- Output Layer

---

## Attention and Transformers
The project also includes a short explanation of:
- RNN limitations
- LSTM memory handling
- Attention mechanism
- Importance of Transformers in modern NLP and Generative AI

---

## Results
The NLP pipeline successfully classified customer messages and demonstrated how text data can be processed using machine learning and sequence modeling concepts.

---

## Folder Structure
part-3-nlp-sequence-modeling/
│
├── dataset/
├── results/
├── notebook.ipynb
├── README.md
└── requirements.txt


---

## Note
This project was created for learning NLP preprocessing, text vectorization, and sequence modeling concepts.
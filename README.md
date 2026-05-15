# Name - Ajay Singh
# Student id - Bitsom_ba_2511011


# Part 3: NLP Sequence Modeling 

## Project Overview

This project builds machine learning and deep learning models to classify customer support messages by sentiment (positive, neutral, negative). It demonstrates a complete NLP pipeline from data exploration through model evaluation, comparing multiple text vectorization and classification approaches.

## Dataset

**Dataset**: Customer Support Text Classification Dataset  
**Location**: `https://drive.google.com/drive/folders/1L3LuDHzKTM8sKAsQ8qqG29jqOtq0hJIg?usp=drive_link`


# TASKS

# Task 1: Dataset Understanding
Load and analyze the text dataset.

Include:

Number of records
Target labels/classes
Sample text records
Average text length
Class distribution

# Task 2: Text Preprocessing
Clean the text data.

Your preprocessing should include:

Lowercasing
Removing unnecessary symbols or special characters
Tokenization
Removing stopwords, if required
Padding or truncating sequences, if using sequence models

# Task 3: Text Vectorization
Convert text into numerical format using at least one of the following:

Bag of Words
TF-IDF
Word embeddings
Tokenizer-based sequences
Explain why text must be converted into vectors before being used by a model.

# Task 4: Baseline Model
Build a simple baseline model using any suitable approach.

Examples:

Logistic Regression with TF-IDF
Naive Bayes with Bag of Words
Simple dense neural network with vectorized input
Evaluate the model using appropriate metrics.

# Task 5: Sequence Model or Conceptual Architecture
Build a simple sequence model using one of the following:

RNN
LSTM
GRU
If full model training is not feasible, create a clear architecture design and explain how the model would process the input sequence.

Your explanation should include:

Input sequence
Embedding layer
Recurrent/sequence layer
Output layer
Loss function
Evaluation metric

# Task 6: Attention and Transformer Reflection
Write a short explanation covering:

Why RNNs struggle with long-term dependencies
How LSTMs help with memory
What attention solves in sequence-to-sequence tasks
Why transformers are important in modern NLP and Generative AI
Expected Repository Conten



## File Structure

part-3-nlp-sequence-modeling/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_evaluation.png or .csv
    └── sample_predictions.txt




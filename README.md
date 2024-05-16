# Minecraft Seq2Seq Chatbot

A Minecraft-based chatbot leveraging Seq2Seq models with LSTM architecture for dynamic Q&A interactions. Utilizes beam search for optimal response generation and integrates sentiment analysis for personalized user engagement.

Note that this model could perform much better with more training, tuning, and higher embedding dimensions. My resources were limited and as a result, this current version has insufficient training as of now.
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [System Description](#system-description)
  - [Seq2Seq Model with LSTM Architecture](#seq2seq-model-with-lstm-architecture)
  - [Sentiment Analysis Integration](#sentiment-analysis-integration)
  - [Natural Language Processing Techniques](#natural-language-processing-techniques)
  - [User Preference Tracking](#user-preference-tracking)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is a chatbot designed to answer questions and engage in conversations about Minecraft. The chatbot is built using a Seq2Seq model with LSTM architecture and incorporates beam search for generating optimal responses. Additionally, sentiment analysis is used to tailor responses based on the user's emotional tone.

## Features
- **Seq2Seq Model with LSTM**: For accurate and context-aware responses.
- **Beam Search Decoding**: Ensures high-quality response generation.
- **Sentiment Analysis**: Provides empathetic and contextually appropriate responses.
- **NLP Techniques**: Enhances understanding and processing of user inputs.
- **User Preference Tracking**: Personalized interactions based on user preferences.

## System Description

### Seq2Seq Model with LSTM Architecture
- **Encoder-Decoder Architecture**: Maps input sequences (user queries) to output sequences (responses).
- **LSTM Layers**: Capture long-term dependencies in sequential data.
- **Pre-trained GloVe Embeddings**: 50-dimensional word vectors used for input representation.
- **Beam Search Decoding**: Explores multiple potential output sequences to select the one with the highest probability.

### Sentiment Analysis Integration
- **Hugging Face Transformers**: Pre-trained sentiment analysis pipeline.
- **Contextual Responses**: Adjusts responses based on detected sentiment (positive, negative, neutral).

### Natural Language Processing Techniques
- **Tokenization**: Splitting input text into individual words or tokens using NLTK.
- **Stopword Removal**: Removing common stopwords to focus on meaningful words.
- **Lemmatization**: Reducing words to their base form using WordNet lemmatizer.
- **Part-of-Speech Tagging**: Identifying grammatical roles to understand input structure and intent.
- **Pattern Recognition**: Detecting specific patterns in input text (e.g., preferences, questions).

### User Preference Tracking
- **Personalized Responses**: Tracks user preferences related to Minecraft for tailored interactions.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to adjust any details or add additional sections as needed for your project.


# Siri_ChatBot
A intent-based conversational chatbot built with **Python, NLTK, and TensorFlow/Keras**. The chatbot is used to understand user messages, identify their intent, and generate appropriate responses from a predefined knowledge base.

## Concepts
- Text preprocessing and normalization
- Bag-of-Words (BoW) feature extraction
- Lemmatization for vocabulary normalization
- Intent classification with a feedforward neural network
- Response selection from predefined intent responses
- Softmax Classification and Stochastic Gradient Descent (SGD)

## High-Level Workflow

flowchart TD
    A[intents.json]

    subgraph NLP Pipeline
        B[Tokenization]
        C[Lemmatization]
        D[Bag of Words]
    end

    subgraph Model
        E[Feedforward Neural Network]
        F[Intent Prediction]
    end

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G[Response Selection]
    G --> H[Chatbot Reply]


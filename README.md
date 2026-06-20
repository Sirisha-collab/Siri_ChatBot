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

```mermaid
flowchart TD
    A[intents.json] --> B[Text Preprocessing<br/>Tokenization<br/>Lemmatization]
    B --> C[Feature Extraction<br/>Bag-of-Words (BoW)]
    C --> D[Neural Network<br/>Intent Prediction]
    D --> E[Response Selection]
    E --> F[Chatbot Reply]
```

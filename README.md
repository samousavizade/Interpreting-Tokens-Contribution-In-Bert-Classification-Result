# Interpreting tokens contribution in bert classification result

# Dependencies

- PyTorch `torch`
- Transformers `transformers`
- Captum `captum`

---

# Dataset

The dataset for this project can be any text data in the context of sentiment analysis. Sentiment analysis is the task of determining the emotional tone of a piece of text, such as whether it is positive, negative, or neutral.

---

# Project Definition

The project definition states that the goal is to use the Captum library and the Integrated Gradients algorithm to capture the contribution of individual tokens in BERT classification results. This means that the project aims to provide a way to understand how specific words or phrases in a text input contribute to the overall classification outcome produced by a BERT model.

BERT (Bidirectional Encoder Representations from Transformers) is a powerful language model that has achieved state-of-the-art results in a wide range of natural language processing tasks, including sentiment analysis. However, because BERT models are often complex and opaque, it can be difficult to understand why they produce certain outputs. By using Integrated Gradients and Captum, this project aims to provide a way to interpret and understand the contributions of individual tokens in BERT models, which can help improve their performance and reliability.


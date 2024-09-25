# Interactive Chatbot with LLaMA 2 and Sentiment Analysis

[Open in Google Colab](https://colab.research.google.com/drive/1KoI3iZtTzfFfAYYMYVMa4ncp13jxGHdX?usp=sharing)

## Overview

This project implements an interactive chatbot using the LLaMA 2 model and sentiment analysis to create engaging conversations. The chatbot can understand user input and respond based on the detected emotional tone, making interactions feel more personal and human-like.

## Features

- **Interactive Chat**: The chatbot listens for user input and responds appropriately.
- **Sentiment Analysis**: Analyzes the emotional tone of the input, allowing for tailored responses.
- **Engaging User Experience**: The chatbot adapts its behavior based on the user's mood.

## Installation

### Installing Required Libraries

In the first cell of the notebook, we install the necessary libraries:

```python
import os

def install_dependencies():
    """Install transformers and torch with GPU support"""
    os.system("pip install transformers")
    os.system("pip install --upgrade torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118")

install_dependencies()

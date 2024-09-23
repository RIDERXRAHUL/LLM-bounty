# Sentiment Analysis Chatbot

## Overview

This project implements a chatbot that utilizes sentiment analysis to enhance user interaction. The chatbot can detect whether a user's sentiment is positive, neutral, or negative and responds accordingly, making the conversation more engaging and empathetic.

## Technologies Used

- **Python**: The primary programming language for this project.
- **Google Colab**: An online platform used for running the code.
- **Transformers**: A library from Hugging Face used for pre-trained models like GPT-2.
- **Torch**: A deep learning framework used for model training and inference.

## Features

- **Sentiment Detection**: The chatbot analyzes the emotional tone of user input.
- **Contextual Responses**: Based on the detected sentiment, the chatbot responds in a way that is appropriate to the user's mood.
- **User-Friendly**: The chatbot aims to provide a seamless and supportive user experience.

## Installation

To set up this project, follow these steps:

1. Clone the repository or download the notebook file.
2. Install the required libraries by running the following command in your terminal or within Google Colab:
    ```bash
    pip install transformers
    pip install --upgrade torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
    ```
3. Log in to Hugging Face to access the models:
    ```python
    from huggingface_hub import notebook_login
    notebook_login()
    ```
4. Run the notebook to interact with the chatbot!

## How to Use

1. Input a sentence into the chatbot.
2. The chatbot will analyze the sentiment of your input.
3. Based on the sentiment, it will provide a response that aims to either empathize with negative sentiments or celebrate positive ones.

## Conclusion

This project showcases the potential of combining sentiment analysis with chatbot technology to create a more human-like interaction. Feel free to explore and modify the code to suit your needs!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

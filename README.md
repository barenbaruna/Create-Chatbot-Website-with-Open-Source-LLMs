# Create Your Own Chatbot Website with Open Source LLMs

<div align="center">
  <img src="https://www.cio.com/wp-content/uploads/2023/08/chatbot_ai_machine-learning_emerging-tech-100778305-orig.jpg?quality=50&strip=all" width="200px"/>
</div>

## Introduction

Welcome to "Create Your Own Chatbot Website with Open Source LLMs" project! In this project, you'll learn how to create a simple chatbot using open-source Language Model Libraries (LLMs) with Python and Hugging Face. By the end of this lab, you will understand the main components of a chatbot, how transformers and LLMs work together, and how to integrate your chatbot into a web interface.

### How does a chatbot work?

A chatbot is a computer program that takes a text input and returns a corresponding text output. It utilizes a special kind of computer program called a transformer, which acts as its brain. Inside this brain lies a language model (LLM) that helps the chatbot understand and generate human-like responses by analyzing patterns from a large dataset of text.

The process of interaction between the user and the chatbot involves:

1. Input Processing: The transformer breaks down the user's input into smaller parts called tokens, making it understandable for the chatbot.
2. Understanding Context: These tokens are then passed to the LLM, which interprets the context of the message based on its training on extensive text data.
3. Generating Response: Using its understanding, the LLM generates a response, which is then formatted and sent back to the user by the transformer.
4. Iterative Conversation: This process repeats as the conversation progresses, with the chatbot continually processing new inputs and generating relevant responses.

### Hugging Face
<div align="center">
  <img src="https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo-with-title.png" width="200px"/>
</div>

Hugging Face is an organization specializing in natural language processing (NLP) and AI, offering a variety of tools and resources to support NLP tasks. We'll be utilizing their Python library transformers for this project.

## Learning Outcomes

By the end of this project, you will:

- Understand the main components of a chatbot.
- Learn about transformers and LLMs.
- Gain insights into how to choose an LLM for your application.
- Understand the working of a transformer and tokenization.
- Be able to program your own simple chatbot in Python.
- Integrate your chatbot into a web interface.
- Communicate with the backend using a webpage.

## How to Run This Project?

To run this project, follow these steps:

1. Save the provided code in a Python file (e.g., app.py).
2. Run the Python file by typing `python app.py` in the terminal.
3. By default, Flask hosts the server at `http://127.0.0.1:5000/`.
4. Access the server by visiting `http://127.0.0.1:5000/` or `http://localhost:5000/` in your web browser.

If running in the Skills Network Cloud:

1. Navigate to the Skills Network Toolbox from the toolbar on the left side of the IDE.
2. Click on “Launch Application” in the adjacent vertical sidebar.
3. Put `5000` as your Application Port.
4. Launch the application in a new browser tab.

![Steps for running in the Skills Network Cloud](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-GPXX04ESEN/images/lab2-12.png)

Let's get started with implementing your own chatbot!

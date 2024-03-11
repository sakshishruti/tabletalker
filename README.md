# tabletalker : Chatbot with Gemini Pro, Streamlit, and LangChain
## Overview
This project demonstrates how to build a conversational chatbot using **Google Gemini Pro, Streamlit**, and **LangChain**. The chatbot is designed to answer queries related to an **SQLite sample database** containing multiple tables. It provides human-like responses, making interactions intuitive and user-friendly.
## Features
**Gemini Pro**: Google’s advanced language model for natural language understanding. <br />
**Streamlit**: A Python library for creating interactive web applications. <br />
**LangChain**: A Python library for working with language models and embeddings.
## Prerequisites
Python 3.9+ <br />
API Key: Obtain an API key from the [Google MakerSuite](https://makersuite.google.com/app/apikey). <br />
## Installation
Install the required packages: <br />
`pip install langchain-google-genai pillow streamlit`

Set your Google API key as an environment variable: <br />
`export GOOGLE_API_KEY="your_api_key_here"`

## Usage
Clone this repository <br />
Create virtual environment in terminal <br />
Install all the libraries listed in `requirements.txt` <br />
Run the Streamlit app: <br />
`streamlit run app.py`

Open your web browser and navigate to http://localhost:8501. <br />
## How It Works
1. The chatbot initializes using Gemini Pro and LangChain.
2. Users can input queries related to the SQLite sample database.
3. The chatbot processes the queries and responds in a human-like manner.
4. Conversations are dynamic and context-preserving.
## Example Conversations
1. User: “What are the top-selling products?”
- Chatbot: “Certainly! The top-selling products are…”
2. User: “Show me customer details for order ID 123.”
- Chatbot: “Certainly! Here are the customer details for order ID 123…”

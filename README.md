# 🦙📚 Columbia Copilot

Columbia Copilot is an AI-powered chatbot designed to answer questions about Columbia University. It leverages the capabilities of OpenAI's GPT-4 and LlamaIndex to provide accurate and contextually relevant responses based on the data it has been trained on.

## Overview of the App

- Takes user queries via Streamlit's `st.chat_input` and displays both user queries and model responses with `st.chat_message`.
- Uses LlamaIndex to load and index data and create a chat engine that will retrieve context from that data to respond to each user query.

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://llamaindex-chat-with-student-handbook-8tp48eikcchw2w9g9fvmsj.streamlit.app/)

## Run the app locally

1. Clone the repository
2. Install the dependencies

```bash
pip install -r requirements.txt
```

3. Run the app

```bash
streamlit run streamlit_app.py
```

## Get an OpenAI API key

You can get your own OpenAI API key by following the following instructions:
1. Go to https://platform.openai.com/account/api-keys.
2. Click on the `+ Create new secret key` button.
3. Next, enter an identifier name (optional) and click on the `Create secret key` button, then copy the API key.
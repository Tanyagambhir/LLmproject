# gemini-pro-streamlit-chatbot
This repository is about building a chatbot using Google's Gemini-Pro with streamlit.
# 💬 Gemini Pro Chatbot using Streamlit

This project is a **chatbot web application** built using **Google Gemini Pro API** and **Streamlit**. It allows users to interact with a powerful AI model through a simple chat interface built entirely with Python.

---

## 🌟 What is Streamlit?

[Streamlit](https://streamlit.io/) is an open-source Python library that helps you create **interactive web apps** easily — without writing any HTML, CSS, or JavaScript.

In this project, Streamlit is used to:

- Create a chat-like interface.
- Take user input (questions).
- Show AI responses in chat format.
- Maintain chat history using session state.

📌 Example:
```python
import streamlit as st
st.title("Gemini Chatbot")
prompt = st.chat_input("Ask something")
st.chat_message("user").write(prompt)

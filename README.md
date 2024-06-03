# Terminal Intelligent Assistant Chat

This Python script enables you to interact with an intelligent assistant directly from your terminal. The assistant, named Jarvis, provides well-reasoned, correct, and helpful answers to your queries.

## Features

- Interactive Chat: Engage in a conversation with Jarvis in real-time.
- Local Model Integration: The script points to a local server running an LLM (Language Model), such as those available through LMStudio.
- Streamed Responses: Jarvis streams his responses to ensure a smooth and interactive experience.

## Prerequisites
- LMStudio or Similar Local LLM Setup: Ensure you have a local server running an LLM and accessible at http://localhost:1234/v1.
- OpenAI Library: This script requires the openai library.

## Installation
Install the openai library using pip:

- pip install openai
- Set up your local LLM server.

## Usage
- Ensure your local LLM server is running and accessible at http://localhost:1234/v1.
- Run the script: python terminal_assistant.py
- Start chatting with Jarvis by typing your messages and pressing Enter.

# Ayurveda_AI
Ayurvedic Sciences knowledge based AI Chatbot (beta)

# Chatbot using Retrieval-Augmented Generation (RAG) and OpenAI's LLM

This repository contains a chatbot built using a combination of Retrieval-Augmented Generation (RAG) and OpenAI's Large Language Model (LLM) via the OpenAI API. The chatbot is designed to provide informative responses by combining the capabilities of a pre-trained LLM with specific information retrieved from a custom database.

## Features

- **RAG Architecture**: Combines retrieval-based techniques with generative models, allowing the chatbot to deliver more accurate and contextually relevant responses.
- **OpenAI LLM Integration**: Utilizes the OpenAI API to harness the power of state-of-the-art language models for natural language understanding and generation.
- **Custom Database**: The chatbot is connected to a small, custom-built database that stores specialized information, which can be retrieved and used by the LLM to generate detailed and accurate answers.

## Current Status

- **Limited Testing**: The chatbot has been tested on a small database, and while it shows promising results, it is still in the early stages of development.
- **Sanskrit Data**: We are actively working on adding a comprehensive set of Sanskrit data to the database. Once complete, this will significantly enhance the chatbot's ability to answer questions related to Sanskrit language and literature.

## How It Works

1. **User Query**: A user inputs a query into the chatbot.
2. **Information Retrieval**: The chatbot first searches the connected database to find relevant information.
3. **LLM Processing**: The retrieved information, along with the original query, is passed to OpenAI's LLM via the API.
4. **Response Generation**: The LLM processes the input and generates a coherent and contextually relevant response, which is then returned to the user.

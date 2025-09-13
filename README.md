# Enhanced Q&A Chatbot With OpenAI
A Streamlit-powered Q&A chatbot application that leverages OpenAI's language models through LangChain integration. This application provides a simple yet effective interface for users to interact with AI models and get responses to their queries.

## Features
🤖 Multiple OpenAI Models: Support for GPT-4o, GPT-3.5-turbo, and GPT-4 \
🔧 Adjustable Parameters: Temperature and max tokens controls for response customization \
🔒 Secure API Key Management: Password-protected API key input \
📈 LangSmith Tracking: Integrated monitoring and tracing capabilities \
🎯 Simple Interface: Clean Streamlit UI with intuitive controls \
⚡ Real-time Responses: Instant AI-powered answers

## Code Architecture
The application is built with the following components: 

LangChain Integration: Uses ChatOpenAI for model interaction \
Prompt Template: System message defines the assistant as helpful\
Output Parser: String output parser for clean response formatting \
Chain Pattern: Implements prompt|llm|output_parser chain structure 

## Installation

Clone the repository
`git clone <your-repository-url> cd <repository-name>`

## Install dependencies
`pip install -r requirements.txt`

## Environment Setup (Optional for LangSmith tracking)
Create a .env file: \
Start the application \
streamlit run app.py 

## Configure in the sidebar:

API Key: Enter your OpenAI API key (required) \
Model Selection: Choose from available models \
Temperature: Adjust response creativity (0.0-1.0) \
Max Tokens: Set response length (50-300) 


## Ask questions:

Type your question in the main input field \
Get instant AI-powered responses


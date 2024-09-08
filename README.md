# Q&A-Chatbot-with-OpenAI-and-Ollama

# Enhanced Q&A Chatbot With OpenAI

## Project Overview

This project demonstrates an interactive Q&A chatbot built using OpenAI's models (`gpt-4`, `gpt-4-turbo`, and `gpt-4o`) integrated into a Streamlit application. Users can input questions, and the chatbot generates responses using the selected OpenAI model.

## Key Features

1. **Streamlit Interface**:
   - Simple and user-friendly UI where users can ask questions.
   - Sidebar settings to configure API keys, model selection, and generation parameters (temperature and max tokens).

2. **OpenAI Integration**:
   - Utilizes OpenAI’s GPT-4 models to generate answers to user queries.
   - Customizable model selection and response tuning (temperature and token limits).

3. **Langchain Integration**:
   - Langchain is used for creating prompt templates and managing the interaction between the user's query and the OpenAI model.

## Key Components

1. **Environment Setup**:
   - The project relies on environment variables for LangSmith tracking:
     - `LANGCHAIN_API_KEY`
     - `LANGCHAIN_PROJECT`

2. **Prompt Template**:
   - A system message instructs the model to act as a helpful assistant, while the user input is dynamically filled into the template.

3. **Streamlit App**:
   - Sidebar for settings:
     - API Key input for OpenAI
     - Model selection
     - Temperature and token limits for generating responses.
   - Main interface where users can enter questions and receive answers.



# Enhanced Q&A Chatbot With Ollama (Open Source Models)

## Project Overview

This project showcases a simple Q&A chatbot using open-source models (`mistral`) from Ollama, integrated with a Streamlit application. Users can ask questions, and the chatbot will respond using the selected model, with customizable response settings.

## Key Features

1. **Streamlit Interface**:
   - Interactive UI allowing users to input questions and receive responses.
   - Sidebar for model selection and response settings (temperature and max tokens).

2. **Ollama Integration**:
   - The app uses Ollama’s open-source model (`mistral`) to generate responses based on user queries.
   - Simple integration with Langchain for prompt handling and model interaction.

3. **Langchain Integration**:
   - Uses Langchain’s `ChatPromptTemplate` to manage the chatbot’s conversation template and process the user input with the selected model.

## Key Components

1. **Environment Setup**:
   - Environment variables are used for LangSmith tracking:
     - `LANGCHAIN_API_KEY`
     - `LANGCHAIN_PROJECT`

2. **Prompt Template**:
   - A system message instructs the chatbot to act as a helpful assistant and respond to user queries, with the user input dynamically passed into the template.

3. **Streamlit App**:
   - Sidebar for adjusting model, temperature, and token limits.
   - Main interface for asking questions and getting answers from the selected open-source model.

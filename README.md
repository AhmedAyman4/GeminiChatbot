# Gemini Chatbot Streamlit Application

## Overview
This is a simple Streamlit-based chatbot application that uses Google's Gemini Pro (Flash) generative AI model to provide interactive conversational responses.

## Prerequisites
- Python 3.8+
- Streamlit
- Google Generative AI library
- python-dotenv

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd <repository-directory>
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install required dependencies:
```bash
pip install streamlit google-generativeai python-dotenv
```

## Configuration

1. Create a `.env` file in the project root directory
2. Add your Google API key:
```
GOOGLE_API_KEY=your_google_api_key_here
```

## Running the Application

```bash
streamlit run Gemini_Chatbot.py
```

## Features
- Interactive chat interface
- Streaming response generation
- Chat history tracking
- Uses Gemini Pro Flash model

## Dependencies
- Streamlit: Web application framework
- Google Generative AI: AI model integration
- python-dotenv: Environment variable management

## Notes
- Ensure you have a valid Google API key
- The application uses the Gemini 2.0 Flash model
- Chat history is maintained in the session state

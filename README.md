# LangChain Jupyter Chatbot

A simple conversational chatbot built with LangChain and LangGraph, designed to run entirely in a Jupyter notebook.

## Features

- Contextual chat powered by Google Gemini and LangChain
- Conversation memory and trimming
- Easy to use in Jupyter environments

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/langchain-chatbot.git
   cd langchain-chatbot
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set your Google Gemini API key:**
   - Create a `.env` file in the project folder with:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```

5. **Open `Chatbot.ipynb` in Jupyter and run the cells.**

## Usage

- Interact with the chatbot directly in the notebook.
- Modify the code to customize prompts or logic as needed.



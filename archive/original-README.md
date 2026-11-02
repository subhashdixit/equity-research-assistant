
# Equity Research Chatbot: News Research Tool 

Equity Research Chatbot is a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the stock market and financial domain.

## Features

- Load URLs or upload text files containing URLs to fetch article content.
- Process article content through LangChain's UnstructuredURL Loader
- Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.


## Project Structure

- main.py: The main Streamlit application script.
- requirements.txt: A list of required Python packages for the project.
- faiss_store_openai.pkl: A pickle file to store the FAISS index.
- .env: Configuration file for storing your OpenAI API key.

## How to Use:
1. Create your own OpenAI API Key.
2. Choose the method for generating your cover letter.
3. Pick the model you'd like to use.
4. Upload your urls and click on process url button
5. Ask questions

## Commands for virtual environment:
    1. To create new virtual environment:
        """ conda create -p venv python=3.9 -y
        """
    2. To activate new virtual environment:
        """
            For command promt: conda activate venv/
            For Git Bash: source activate venv/
        """
## Command to install requirements.txt file:
    1. pip install -r requirements.txt

## Command to run Streamlit app:
    1. streamlit run main.py

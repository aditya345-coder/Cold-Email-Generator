# Cold Email Generator

## Overview
The Cold Email Generator is an end-to-end solution designed to streamline and automate the process of crafting cold emails. This project leverages the power of advanced Large Language Models (LLMs) and Generative AI to generate personalized emails efficiently.

## Features
- **Llama3.1 Open Source LLM:** Utilizes the Llama3.1 model for generating high-quality email content.
- **ChromaDB (Vector Store):** Implements ChromaDB for efficient data storage and retrieval, allowing for better contextual understanding in email generation.
- **LangChain:** Employs LangChain to facilitate the interaction between the LLM and the vector store, ensuring smooth data flow and query handling.
- **Streamlit Interface:** Provides a user-friendly interface for generating cold emails with just a few clicks.

## Tech Stack
- **Llama3.1:** Open-source large language model used for generating the email content.
- **ChromaDB:** Vector store for managing embeddings and enabling semantic search.
- **LangChain:** Framework for integrating LLMs and vector databases.
- **Streamlit:** Web framework for creating a simple and interactive UI.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cold-email-generator.git
   ```
   
2. Create virtual environment:
   ```bash
   python -m virtualenv venv
   ```
   
3. Activate virtual environment:
   ```bash
   .\\venv\Scripts\activate
   ```
   
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   
5. Run the Streamlit application:
   ```bash
   cd app
   streamlit run main.py
   ```
## Usage
1. Open the Streamlit app in your browser.
2. Input the job link
3. Generate a cold email with a single click.

## Future Enhancements

* Add more customizable templates.
* Implement email scheduling and sending functionality.
* Improve the contextual understanding by integrating additional data sources.

## License

This project is licensed under the MIT License.

# RAG-Chatbot-with-Langchain
Question-Answering Bot for PDF Documents

This project combines advanced natural language processing techniques to create a Question-Answering (QA) bot that answers user queries based on content extracted from PDF documents. Built using LangChain, a Large Language Model (LLM), and additional tools, this bot automates the process of retrieving and understanding information from extensive document libraries, such as legal files, technical manuals, or business reports.

Features
Document Loading: Seamlessly load and preprocess PDF documents.
Text Splitting: Efficiently handle large documents by splitting text into manageable chunks.
Embeddings and Vector Databases: Use embedding models to store document data in a vectorized format for fast and accurate retrieval.
Retrievers: Enable precise question-answering by finding the most relevant information.
Gradio Interface: Provide a user-friendly front-end for interacting with the QA bot.
Use Case
Imagine having a digital assistant that can instantly search through and summarize content from large document collections. This bot is particularly useful for industries like law, engineering, or customer support, where quick access to specific information is crucial.

Learning Outcomes
This project demonstrates how to:

Integrate document loaders, text splitters, embedding models, and vector databases to build a fully functional QA system.
Utilize LangChain and LLMs to address complex information retrieval challenges.
Develop an intuitive user interface using Gradio.
Technologies Used
LangChain
Large Language Models (LLM)
Gradio for the front-end interface
PDF Document Loaders
Vector Databases and Retrieval Systems


Installation Guide

Clone the repository to your local machine:

git clone https://github.com/sebaskhe/RAG-Chatbot_with_Langchain.git  
cd RAG-Chatbot_with_Langchain

Step 2: Set Up a Virtual Environment
Setting up a virtual environment helps manage dependencies for this project.

Install virtualenv (if not already installed):

pip install virtualenv  
Create a virtual environment named my_env:
virtualenv my_env  
Activate the virtual environment:
On Linux/macOS:
bash
Copiar código
source my_env/bin/activate  
On Windows:

my_env\Scripts\activate  
Step 3: Install Required Libraries
Install the necessary dependencies in the virtual environment:


python3.11 -m pip install \  
gradio==4.44.0 \  
ibm-watsonx-ai==1.1.2 \  
langchain==0.2.11 \  
langchain-community==0.2.10 \  
langchain-ibm==0.1.11 \  
chromadb==0.4.24 \  
pypdf==4.3.1 \  
pydantic==2.9.1  
Step 4: Run the Application
With the environment set up and dependencies installed, you're ready to run the application.

Ensure the virtual environment is active.
Execute the main script:

python3.11 qabot.py  
Step 5: Access the Application
Open the URL provided in the terminal to access the Gradio interface and start interacting with the Question-Answering Bot.

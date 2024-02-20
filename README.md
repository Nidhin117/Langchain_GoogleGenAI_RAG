# Langchain_GoogleGenAI_RAG
RAG QA over custom files using Langchain, Google's Generative AI embedding and Chroma Vector DB 
The custom file used in this project is a report I had prepared regarding Airline Customer Satisfaction for my academic project.
Google's embeddings are not really the best when it comes to RAG over custom files, this is based on the observation that the model failed to answer the question "Are airlines industry profitable" correctly.
This is because the document does not explitely talk about profitability, but instead the document details about how many Airline companies have shutdown over the years.
In a subsequent project the combination of BGE word embeddings and Llama 70b was able to answer the same question more precisely

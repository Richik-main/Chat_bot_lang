# Chat_bot_lang
- I will be using Langchain to create a chatbot 
- In this chatbot I will be using a memory buffer to keep track of the conversations
- I am using dbrx-instruct for best results
- I am using Databricks for the whole implementation
I am going to use Rag to retrieve data from a github repo

<img width="661" alt="image" src="https://github.com/user-attachments/assets/3abda68d-c90c-4283-b30e-e6185ee88c89">

Did loading from github -> chunking -> stuck at storing in vector database as this requires openaiembedding api call. I need to find a way to bypass this.
I will be using LangSmith(these are the best for getting the best results as these are finetuned for best results) for better prompts.

https://python.langchain.com/v0.2/docs/tutorials/rag/#indexing-store
https://python.langchain.com/v0.2/docs/how_to/#document-loaders
https://python.langchain.com/v0.1/docs/modules/data_connection/vectorstores/

# Chat_bot_lang
- I will be using Langchain to create a chatbot 
- In this chatbot I will be using a memory buffer to keep track of the conversations
- I am using dbrx-instruct for best results
- I am using Databricks for the whole implementation
I am going to use Rag to retrieve data from a github repo

<img width="661" alt="image" src="https://github.com/user-attachments/assets/3abda68d-c90c-4283-b30e-e6185ee88c89">

Did loading from github -> chunking -> stuck at storing in vector database as this requires openaiembedding api call. I need to find a way to bypass this.

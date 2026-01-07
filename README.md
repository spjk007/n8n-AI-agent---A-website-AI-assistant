Website AI Assistant:

Tech Stack:

-n8n =>Workflow

-pinecone =>RAG Response AI Assistant

-SupaBase =>PostgreSQL username and password creation for credentials.

-chatgpt =>Debugging

-Claude AI =>Website Creation

-perplexity AI =>API keys for Product related questions

-cohere => For chat model API key

Youtube Video Tutorial Used:

https://youtu.be/mLTqabG0l7c?si=JRz-T2Q-z5YSNfMs

Real Website that is used for this project: www.joolca.com

Step-by-Step Workflow:

1) Start by logging into n8n account and creating new workflow with the "when chat message received" module.
2) Create a Base AI agent with the current module to make the bot "talk". For that use the cohere module for chat model. Get API Keys from cohere platform.
3) Setup Supabase Account and use the PostgreSQL credential from the pool server. Use it in the memory module of the AI agent and setup the credentials.
4) To send email use GMAIL account verification. The content is set to post.
5) Give AI a list of FAQs pdf or txt file using pinecone AI assistant and set it up using "http request" module of the n8n.
6) Give the AI current relevant questions regarding product and troubleshooting to answer by usig perplexity ai model.
7) Copy the n8n chat completions code and ask clause to create a joolca website and it gives you model website to run. Do not forget to copy paste web hook url from the "when chat message received" module.
8) Finally run every thing together in visual studio or replit.

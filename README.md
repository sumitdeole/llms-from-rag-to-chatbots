# Large Language Models (LLMs)
We are living in a LLM-led AI world. LLMs are colossal AI systems, trained on massive datasets of text and code, possess remarkable abilities, including generating human-quality text, translating languages, writing different kinds of creative content, and even answer our questions in an informative way. 

In this project, the following LLM tasks are performed: 

## 1. Mistral 7B model
It is a quantised version of Mistral AI large model. It is small enough to run locally.

## 2. Create a chatbot
In this notebook, I will be a chatbot with the capability to retain information from previous prompts and responses, enabling it to maintain context throughout the conversation.

## 3. Retrieval Augmented Generation (RAG) model
RAG combines information retrieval with language models and improves the ability of LLM tremendously. It first searches for relevant facts in external sources, then feeds those facts to the language model alongside the user's prompt. This helps the model generate more accurate and factual responses, even on topics beyond its initial training data. In this notebook, I will go beyond pretrained models to customizing LLMs. 

## 4. RAG with memory
After exploring LLMs, chatbots, and RAG, I now try to put them all together to create a powerful tool: a RAG chain with memory. To this end, I will use the `ConversationalRetrievalChain`, a LangChain chain for RAG with memory.

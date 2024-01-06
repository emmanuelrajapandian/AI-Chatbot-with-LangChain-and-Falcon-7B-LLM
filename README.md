# AI Chatbot with LangChain and Falcon-7B LLM

Welcome to the repository for my AI chatbot project, where I've created a conversational agent leveraging the capabilities of LangChain, the 8-bit quantized Falcon-7B Language Model (LLM), and Chroma DB. I've developed a chatbot equipped with the capacity to learn from the external world through Retrieval Augmented Generation (RAG).

## Project Overview
I started this project because I wanted to learn a new technology stack and apply it to something I really enjoy—speedcubing, which is a hobby of mine for the past 10 years. To make the chatbot smarter, I decided to build it by getting information from the official WCA website, like rules and guidelines. This information forms the base, helping the chatbot answer questions about speedcubing and its rules.

## Data Extraction and Integration
The heart of the chatbot lies in the data extracted from the WCA website. By incorporating information about speed-cubing, its intricacies, and the official guidelines, the chatbot becomes a valuable resource for speedcubers seeking information or assistance.

## Features
* LangChain: Harnessing the power of LangChain, the chatbot exhibits natural language processing capabilities.
* Falcon-7B LLM: The use of the 8-bit quantized Falcon-7B LLM enhances the efficiency and performance of the chatbot's language understanding. The quantized model also helps the code run faster in comparison to the full 7B model.
* Chroma DB: This integration contributes to a more comprehensive and dynamic knowledge base, enabling the chatbot to provide contextually relevant responses.
* Retrieval Augmented Generation (RAG) Pipeline: The RAG pipeline facilitates the chatbot's ability to learn from the external world, ensuring adaptive and informed responses.

## Getting Started
To explore and experience the capabilities of this chatbot, follow these steps:

* Clone the repository.
* Set up the required dependencies using the `requirements.txt`.
* Run the notebook to witness the construction of the intelligent conversational agent and the RAG pipeline.
* The Website links can be changed accordingly to change the context of the RAG pipeline and therefore the domain knowledge of the chatbot.

## Future Enhancements
This project is a dynamic endeavor, and future enhancements are as follows:

* This chatbot system can be deployed or hosted on Streamlit or Huggingface for public usage.
* With the recent `Mixtral-8x7B-Instruct-v0.1` LLM, I was thinking of this and other LLMs to test the capability and power of each Large Language Model.
* Using `ConversationalRetrievalChain`, the chatbot can have access to chat history and therefore have continous followup questions from the user.

Feel free to explore the code, experiment with customizations, and hit me up if you want to discuss on this in depth.
Happy coding! 🤖✨

---

**Author:** J Emmanuel Rajapandian

**GitHub Repository:** [AI-Chatbot-with-LangChain-and-Falcon-7B-LLM]([https://github.com/4N1Z/hotel-coChat-Cohere](https://github.com/emmanuelrajapandian/AI-Chatbot-with-LangChain-and-Falcon-7B-LLM))  

For inquiries and feedback, please contact me at [emmanuel.rajapandian@gmail.com](mailto:emmanuel.rajapandian@gmail.com]).

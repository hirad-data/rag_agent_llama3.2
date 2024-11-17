# RAG Agent using Llama3.2 and Ollama
This application implements a Retrieval-Augmented Generation (RAG) system using Llama 3.2 via Ollama, with Qdrant as the vector database.
# Features

- Fully local RAG implementation
- Powered by Llama 3.2 through Ollama
- Vector search using Qdrant
- Interactive playground interface
- No external API dependencies

How to start?

1- Clone the GitHub repository:  
git clone https://github.com/hirad-data/rag_agent_llama3.2.git


2- Install the required dependencies:  
pip install -r requirements.txt

3- Install and start Qdrant vector database locally:  
docker pull qdrant/qdrant  
docker run -p 6333:6333 qdrant/qdrant

4- Install Ollama and pull Llama 3.2:  
ollama pull llama3.2

5- Run the AI RAG Agent:  
python local_rag_agent.py

6- Open your web browser and navigate to the provided URL in the console output to interact with the RAG agent through the playground interface.

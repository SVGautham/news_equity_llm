# RESEARCH ARTICLE LLM
Users can input article URLs and ask questions to obtain relevant insights from the stock market and financial domain.

Features
Load URLs or upload text files with URLs to retrieve article content.
Utilize LangChain's UnstructuredURL Loader to process article content.
Create embedding vectors using OpenAI's embeddings and employ FAISS, a powerful similarity search library, for quick and efficient information retrieval.
Interact with the LLM (ChatGPT) by submitting queries and receiving responses, including source URLs.

Project Structure<br>
main.py: The main Streamlit application script.
requirements.txt: A list of required Python packages for the project.
faiss_store_openai.pkl: A pickle file to store the FAISS index.
.env: Configuration file for storing your OpenAI API key.

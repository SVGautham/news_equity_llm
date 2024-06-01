# RESEARCH ARTICLE LLM
Users can input article URLs and ask questions to obtain relevant insights from the stock market and financial domain.

Features<br>
Load URLs or upload text files with URLs to retrieve article content.<br>
Utilize LangChain's UnstructuredURL Loader to process article content.<br>
Create embedding vectors using OpenAI's embeddings and employ FAISS, a powerful similarity search library, for quick and efficient information retrieval.<br>
Interact with the LLM (ChatGPT) by submitting queries and receiving responses, including source URLs.<br>

Project Structure<br>
main.py: The main Streamlit application script.<br>
requirements.txt: A list of required Python packages for the project.<br>
faiss_store_openai.pkl: A pickle file to store the FAISS index.<br>
.env: Configuration file for storing your OpenAI API key.<br>

Install the required dependencies using pip in requirements.txt file<br>
Set up your OpenAI API key by creating a .env file in the project root and adding your API<br>
run the streamlit app

![Uploading Screenshot (401).png…]()

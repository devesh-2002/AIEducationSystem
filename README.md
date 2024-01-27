# AIEducationSystem

This is an AI based Educational System made using **RAG (Retrieval Augmented Generation)**. Students can upload educational data (including PDFs and Videos) and interact with chatbot regarding the documents.

## Tech Stack used : 
1. Model used : [TheBloke/Mistral-7B-Instruct-v0.1-GGUF]([url](https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF)https://huggingface.co/TheBloke/Mistral-7B-Instruct-v0.1-GGUF)
2. General Text Embeddings : [thenlper/gte-large]([url](https://huggingface.co/thenlper/gte-large)), LLAMA Index
3. MongoDB
4. Gradio (2 User Interfaces - Student and School)

## Running the Project : 
1. **Note that Mistral-7B might require GPU/Google Colab Pro, on CPU/Google Colab it can crash**.
2.  Add ``Mongo_URI`` in the secrets.
3.  Run the Colab file.
4.  Add a document in the first interface, in the second interface chat with the chatbot.


# RAG Document Q&A With Groq And Lama3
This project is a Streamlit application that performs retrieval-augmented generation (RAG) for document-based question answering using Groq and Lama3 models. The application loads research papers, creates vector embeddings, and allows users to query the documents.


## Installation and Running

1. Clone the repository:
    ```sh
    git clone https://github.com/OnurAsimIlhan/rag-QA-with-Groq-LLama.git
    cd rag-QA-with-Groq-LLama
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
    or
    ```sh
    cuda create -p venv
    cuda activate venv/
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```
4. Run Streamlit:
   ```sh
    streamlit run main.py
    ```

## Features
- Load and process research papers from a directory.
- Create vector embeddings using FAISS and OllamaEmbeddings.
- Perform document-based question answering using Groq and Lama3 models.
- Display document similarity search results.

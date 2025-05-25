Hybrid Search RAG with Vector Database and LangChain
This project demonstrates a hybrid search approach combining traditional BM25 retrieval with vector-based semantic search using LangChain. It showcases how to implement a Retrieval-Augmented Generation (RAG) system that leverages both keyword-based and semantic search techniques to improve information retrieval performance.

Features
Hybrid Retrieval: Combines BM25 and vector similarity search for enhanced document retrieval.

LangChain Integration: Utilizes LangChain for building modular and scalable language model applications.

Jupyter Notebook: Includes an interactive notebook (experiments.ipynb) for experimentation and demonstration purposes.

Installation
git clone https://github.com/Shyamal1508/Hybrid_search_rag_with_vector_database_and_langchain.git
cd Hybrid_search_rag_with_vector_database_and_langchain

Create a Virtual Environment:
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Usage
Prepare the Data:
Ensure that the bm25_values.json file is present in the repository. This file contains precomputed BM25 values for the dataset.

Run the Jupyter Notebook:
jupyter notebook experiments.ipynb


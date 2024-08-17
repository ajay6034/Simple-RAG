# Simple-RAG
Text file, PDF file, Web base Format Data Used In this Project
## RAG Architecture
![image](https://github.com/user-attachments/assets/ece7db3b-aabd-457f-986c-c92b33f9f00f)
## Objective:
The project aims to build a system that can retrieve relevant documents and generate answers based on those documents. This is typically done by combining a vector database for document retrieval and an LLM (Large Language Model) like OpenAI's GPT for generating responses.

## Implementation Explination
1.Document Ingestion:
The notebook begins by loading documents, which are presumably text files or other formats. These documents are processed and transformed into embeddings (vector representations) that can be efficiently searched.

2. Vector Database:
The project uses FAISS (Facebook AI Similarity Search) for managing vectorized documents. FAISS is a popular library for efficient similarity search and clustering of dense vectors.

3. LangChain Integration:
LangChain is used to handle the document loaders and vector stores, streamlining the process of managing and querying large sets of documents.

4. OpenAI for Embeddings:
The project uses OpenAI’s embeddings to convert textual documents into vectors. These embeddings are essential for enabling the similarity search in the vector database.

5. Query Processing:
A query is processed through the system to retrieve relevant documents from the vector database. The system then uses these documents to generate a response.

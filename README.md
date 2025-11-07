# Mini RAG System Project

This is a simple **RAG (Retrieval-Augmented Generation) system** built in Python using Hugging Face Transformers and Sentence Transformers.  

The project shows how to:

- Use a **retriever model** (`all-MiniLM-L6-v2`) to find the most relevant context from a small knowledge base.  
- Use a **generator model** (`distilbert-base-cased-distilled-squad`) to answer questions based on the retrieved context.  
- Run a simple **assessment pipeline** to check retrieval and answer generation accuracy.  

## Files

- `mini_rag_system.ipynb` — The main notebook with the RAG pipeline and test questions.

## How to Run

1. Install the required libraries:
```
!pip install sentence-transformers transformers torch
```
2. Open and run the ```mini_rag_system.ipynb``` notebook in Jupyter or Colab.
3. Modify the ```knowledge_base``` or ```test_questions variables``` to try your own questions.

## Example
question = "How many miles does the Great Wall of China stretch?"
The system will retrieve the relevant context and generate the answer: 13,000.

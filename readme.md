# Graph RAG: Movie Reviews Knowledge Graph (Rotten Tomatoes)

![Graph RAG • LangChain • Python • GraphRetriever](https://img.shields.io/badge/Graph%20RAG-LangChain%20%7C%20Python%20%7C%20GraphRetriever-blue)

![Project Banner][1]

## Overview

This project demonstrates Retrieval-Augmented Generation (RAG) using a knowledge graph built from Rotten Tomatoes movie reviews and movie info. It features LangChain's GraphRetriever and OpenAI embeddings.

## Features

- Graph RAG with LangChain & Python
- Vector database for movie reviews and metadata
- Knowledge graph traversal via GraphRetriever
- Summarizes and recommends movies using both reviews and structured data

## How to Run

1. Clone the repository.
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Add your API keys to a `.env` file using `.env.example` as a template.
4. Run the core script:  
   `python main.py`

## File Structure

- `main.py` — Core logic for loading data, building vector store, and query/retrieval
- `requirements.txt` — All required Python packages
- `.env.example` — Template for OpenAI and (optionally AstraDB) credentials
- `.gitignore` — Common Python and API key exclusions

## Data Sources

Sample datasets are embedded in the code for demos. For larger experiments, see Rotten Tomatoes datasets on [Kaggle](https://www.kaggle.com/datasets/andrezaza/clapper-massive-rotten-tomatoes-movies-and-reviews).

## Tech Stack

- Python
- LangChain
- GraphRetriever
- OpenAI Embeddings
- pandas, dotenv

---

## License

MIT License

---

[1]: graph-rag-banner.png

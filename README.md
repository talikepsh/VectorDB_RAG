# Using Vector Data Base for RAG for Retreval Improvement

This project explores the use of vector databases to improve Retrieval-Augmented Generation (RAG) systems. By leveraging vector databases, we aim to enhance the retrieval phase of RAG, leading to more accurate and relevant results in generation tasks.

## Introduction

This project investigates the application of vector databases to enhance the performance of RAG systems. RAG combines retrieval and generation, and by optimizing the retrieval process using vector databases, we can improve the overall effectiveness and accuracy of the system.

## Features

- Integration with vector databases for optimized retrieval.
- Enhanced retrieval mechanisms for more accurate generation results.
- Scalable and efficient querying of large datasets.
- Modular design for easy integration with existing RAG systems.

## The Full RAG Pipline
1. Document reading and preprocessing.
2. Chunking documents for embedding generation.
3. Embedding generation and insertion into Pinecone VectorDB.
4. Retrieval of relevant documents.
5. Generating answers to given questions using the retrieved documents.


## Requirements

- Python 3.6+
- sentence-transformers
- datasets
- pinecone-client
- cohere
- tqdm
- numpy
- pandas
- nltk

## Installation

Install the required libraries using pip:

```bash
pip install sentence-transformers datasets pinecone-client cohere tqdm numpy pandas nltk

## Dataset
The dataset we utelize in the project is 'aav-ds/Israel-HAMAS_war_news' from HuggingFace Datasets.
Link for the data: https://huggingface.co/datasets/aav-ds/Israel-HAMAS_war_news

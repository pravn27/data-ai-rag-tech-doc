---
sidebar_position: 3
---

# 3 - Data Ingestion & Data Parsing techniques

## Setup init Python project with uv package manager
    - Before starting any RAG projects with python, better to setup its virtual env. Follow below commands
    - `uv init`
    - `uv venv`
    - once virtual env created, activate it
        - `source .venv/bin/activate`

## Using Langchain to build RAG system
    - https://github.com/langchain-ai/langchain
    - https://reference.langchain.com/python/langchain
    - https://reference.langchain.com/python/langchain/overview

## Langchain Document structure - Page Content and Metadata
    
    - https://github.com/pravn27/rag-learning-journey/blob/master/krish-naik/course-1/projects/rag-1/1-data-ingestion-and-parsing/1-data-ingestion.ipynb

    - https://raw.githubusercontent.com/pravn27/rag-learning-journey/refs/heads/master/krish-naik/course-1/projects/rag-1/1-data-ingestion-and-parsing/ref-resources/1-langchain-document-components.svg

    - Langchain Document are required to Enrich the data by adding metadata, while storing into Vector DB
        - https://reference.langchain.com/python/langchain-core/documents/base/Document

## Data Ingestion & Parsing using Document Loaders

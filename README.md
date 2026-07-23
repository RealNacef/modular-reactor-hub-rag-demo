Archived demonstration of a domain-specific Retrieval-Augmented Generation (RAG) prototype developed for technical knowledge retrieval in the SMR, AMR and microreactor domain.

Project status: archived prototype. The original Google Cloud VM and public application endpoint have been decommissioned. The videos below document the working capabilities of the system at the time of recording.

Overview

Modular Reactor Hub combined:

a corpus of more than 3,000 technical documents;

document extraction, chunking, embeddings and semantic retrieval;

local LLM inference through Ollama;

web augmentation using requests and BeautifulSoup;

multimodal image-query handling;

a Python/Flask backend deployed on Google Cloud Platform.

Demonstrations

Demo 1 — RAG answer generation with web augmentation

The system answers a technical question by retrieving relevant evidence from the indexed corpus and supplementing the response with web-based sources.



Download or watch Demo 1

Demo 2 — Multimodal image analysis

The system accepts an uploaded nuclear-system diagram, analyses its visual content and combines the image interpretation with a natural-language response.



Download or watch Demo 2

Architecture

Technical documents / web sources / uploaded image
                    |
            extraction and chunking
                    |
          embeddings and semantic search
                    |
       retrieved context + user question
                    |
             local LLM / LMM
                    |
        grounded answer and source output

Technology stack

Python · Flask · LangChain · scikit-learn · SQLite · Ollama · BeautifulSoup · requests · Google Cloud Platform

Notes

The public web application is no longer online.

These videos are retained as portfolio evidence of the implemented prototype.

No confidential source documents or access credentials are included in this repository.

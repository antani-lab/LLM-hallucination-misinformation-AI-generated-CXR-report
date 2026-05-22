Hallucination and Misinformation in AI-Generated Radiology Reports
A Comparative Evaluation of Retrieval-Grounded LLMs with Verifier-Guided Revision

Overview
This repository contains the Python notebooks and supporting code for the study:
Hallucination and misinformation in AI-generated radiology reports: a comparative evaluation of retrieval-grounded LLMs with verifier-guided revision.
The project investigates the reliability of large language models (LLMs) for automated chest X-ray (CXR) report generation under retrieval-augmented generation (RAG) and verifier-guided iterative revision settings.

The framework combines:

* Multimodal retrieval using BiomedCLIP embeddings
* FAISS vector similarity search
* Open-source text-only and multimodal LLMs
* Retrieval-grounded prompting
* Verifier-guided confession iteration
* Multi-metric evaluation for both diagnostic accuracy and misinformation risk

The repository is designed to support:

* Reproducible experimentation
* Notebook-based analysis
* Benchmark evaluation
* Local deployment of medical LLM pipelines

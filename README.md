🔍 Retrieval-Augmented Generation (RAG) Practice & Mini Projects
Overview

This repository contains hands-on implementations and mini projects built while learning Retrieval-Augmented Generation (RAG) concepts using Large Language Models, embeddings, and vector-based retrieval.

The goal of this project is to understand how external knowledge can be integrated into LLM workflows and how such systems can be monitored and evaluated.

🧠 Key Concepts Covered

Document loading and chunking

Embedding generation

Vector storage and semantic retrieval

Query-based context augmentation

LLM response generation

Persistent indexing

Observability and tracing using Arize Phoenix

🛠️ Tech Stack

Python

LlamaIndex

Vector Index (local)

Arize Phoenix

OpenInference Instrumentation

GitHub Codespaces

Jupyter Notebook / VS Code

🏗️ RAG Pipeline Workflow
User Query
   ↓
Query Embedding
   ↓
Vector Search
   ↓
Relevant Context Retrieval
   ↓
LLM Response Generation

🔎 Observability with Arize Phoenix

This project integrates Arize Phoenix to monitor and analyze the RAG pipeline.

Phoenix enables:

Tracing of LLM requests and responses

Visualization of retrieved documents

Token usage and latency analysis

Debugging retrieval quality

Phoenix Integration Example
import phoenix as px
from openinference.instrumentation.llama_index import LlamaIndexInstrumentor

px.launch_app()
LlamaIndexInstrumentor().instrument()

🖥️ Development Environment

This project was developed and executed using GitHub Codespaces, providing a cloud-based development environment with reproducible setup and execution.

📌 Learning Outcomes

Designed end-to-end RAG pipelines

Implemented semantic search using embeddings

Integrated observability into LLM workflows

Gained practical experience with AI system debugging

🔮 Future Improvements

Add UI using Streamlit

Support multiple document formats

Add evaluation metrics for retrieval quality

Deploy as an API

👩‍💻 Author

Rupsha Debnath
GitHub: https://github.com/Rupu-techu

LinkedIn: https://www.linkedin.com/in/rupsha-debnath-056739317/

# LangChain-Chat-With-Your-Data

## Overview
This repository showcases a project developed as part of the SHE STEMS 3.0 program by Oman Cables Industry (OCI). The goal was to create an interactive chatbot leveraging LangChain, a framework for building applications powered by Large Language Models (LLMs). The chatbot was designed to interact dynamically with data from OCI's product catalogs.

---

## Features
- **Document Loading:** Import OCI product catalogs in PDF format.
- **Document Splitting:** Divide large documents into manageable chunks for efficient processing.
- **Vectorstore & Embeddings:** Convert text into numerical vectors and store them for fast retrieval.
- **Interactive Chatbot:** Users can ask questions and receive precise, data-driven responses.

---

## Practical Example
A Python-based program using LangChain:
1. **Data Input:** Uploaded PDF product catalogs from the OCI website.
2. **Processing:** 
   - Split documents into smaller sections.
   - Generate embeddings using LangChain.
3. **Storage:** Stored data in a vector database for quick access.
4. **Interaction:** Queries were matched to the database, allowing the chatbot to provide accurate answers.

---

## Technologies Used
- **LangChain Framework**
- **Python**
- **Vector Databases** (e.g., FAISS)
- **PDF Parsing Libraries**

---

## Real-World Applications
- **Customer Support:** Answer product-related queries instantly.
- **Manufacturing:** Retrieve technical guidelines, quality control protocols, and safety documentation in real-time.

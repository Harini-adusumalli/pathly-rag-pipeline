# Pathly — AI-Powered Job Intelligence Platform

An AI-driven job discovery engine built for the Indian market using
Retrieval-Augmented Generation (RAG) and semantic vector search.

Developed as part of my internship at GlowTech Solutions, where I contributed to data preprocessing, RAG-based retrieval workflows, and semantic search capabilities in collaboration with the development team.

## What It Does
- Processes and organizes Indian job records to enable intelligent job discovery
- Supports semantic search across job titles, skills, and industries using vector embeddings
- Utilizes LLM-powered query understanding with fallback mechanisms
- Assists in matching candidate skills with relevant job opportunities

## Tech Stack
- RAG Pipeline: LangChain, Pinecone, Ollama
- Backend: Flask
- Data Processing: Python, Pandas
- Vector Database: Pinecone

## Architecture
User Query → Flask API → LangChain RAG Pipeline → Pinecone Vector Search → Ranked Job Results

## My Contributions
- Contributed to the development and enhancement of RAG-based retrieval workflows
- Assisted in preprocessing and structuring job datasets for efficient retrieval
- Worked on semantic search functionality using Pinecone vector embeddings
- Participated in integrating LLM-based query understanding and response generation
- Collaborated with team members in implementing and testing backend components

## Setup

```bash
pip install -r requirements.txt

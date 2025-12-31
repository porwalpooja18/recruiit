Recruiit
A RAG-Based Resume Screening Project

Recruiit is a personal AI project that explores how semantic search and rule-based ranking can be applied to resume screening.
The system matches internal resumes against a job description using vector embeddings and simple ranking logic.

This project was built primarily for learning and experimentation with retrieval-augmented generation (RAG), embeddings, and AI-assisted search workflows.

Overview

Performs semantic search over resumes using vector embeddings

Supports basic resume parsing (PDF and DOCX)

Ranks candidates using simple, configurable rules (skills, experience, keywords)

Provides basic explanations for why a resume matches a job description

Avoids external candidate sourcing or scraping

Tech Stack

Python

FAISS and MongoDB

SentenceTransformers

FastAPI

PyMuPDF / python-docx




Running the Project
pip install -r requirements.txt
uvicorn api.main:app --reload

Motivation

This project was created to:

Understand RAG-based retrieval pipelines

Practice working with vector databases

Apply AI techniques to a realistic resume screening use case

Build a clear, interview-ready personal project

Author

Pooja Porwal

Document QA RAG System
A Retrieval-Augmented Generation (RAG) system built to answer questions based on a collection of text documents. This project processes news articles, chunks them into manageable pieces, and stores them in a vector database for efficient semantic search and querying using Google's Gemini model.

📖 Overview
This project transforms a directory of static text files (news_articles) into an interactive knowledge base. Instead of manually searching through files, users can ask questions in natural language and receive precise answers sourced directly from the provided articles.

The system uses advanced NLP techniques for sentence segmentation and creates contextually rich chunks for optimal retrieval and generation.

Key Features:

Document Processing: Automatically loads and processes .txt files from a specified directory.

Intelligent Chunking: Uses spaCy's sentencizer to split documents into sentences, which are then grouped into coherent chunks (10 sentences per chunk by default).

Semantic Vector Store: Leverages Google's models/embedding-001 model to create embeddings and stores them in a persistent ChromaDB collection.

Powerful Querying: Ready to be integrated with Google's gemini-2.0-flash-lite-preview model for fast and accurate question-answering.

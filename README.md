# Neo4j Movie Graph QA System

This project implements a question-answering system for a movie database using Neo4j graph database and LangChain with the Groq LLM.

## Project Description

This system loads movie data into a Neo4j graph database and uses LangChain with the Groq LLM to answer natural language questions about the movie dataset. It demonstrates the power of combining graph databases with large language models for information retrieval and question answering.

![Screenshot 2024-12-17 at 9 00 32 PM](https://github.com/user-attachments/assets/513252f5-e4d6-4b8f-89b5-aa0c9c886e1c)


## Features

- Loads movie data into Neo4j from a CSV file
- Creates a graph structure with movies, persons (actors and directors), and genres
- Uses LangChain to create a question-answering chain
- Integrates with Groq's Gemma2-9b-It language model
- Answers natural language questions about the movie dataset

## Tech Stack

- Python
- Neo4j (Graph Database)
- LangChain
- Groq (LLM provider)
- langchain-neo4j
- langchain-groq
- python-dotenv

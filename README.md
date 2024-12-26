# Movie Database Query System with Neo4j and LLM

This project implements a movie database query system using Neo4j graph database, LangChain, and the Gemma2 large language model. It allows users to ask natural language questions about movies, actors, directors, and genres, which are then translated into Cypher queries and executed against the Neo4j database.

## Features

- Neo4j Integration: Utilizes Neo4j graph database for storing and querying movie data
- Data Import: Imports movie data from a CSV file into the Neo4j database
- Natural Language Processing: Uses Groq's Gemma2-9b-It model to interpret user queries
- Cypher Query Generation: Automatically generates Cypher queries based on natural language input
- Flexible Querying: Supports a wide range of queries about movies, actors, directors, and genres

## How It Works

1. The system connects to a Neo4j database using provided credentials
2. Movie data is imported from a CSV file and structured into a graph database
3. The Groq language model is initialized for natural language processing
4. User queries are processed through a GraphCypherQAChain, which:
   - Interprets the natural language query
   - Generates an appropriate Cypher query
   - Executes the query against the Neo4j database
   - Formats the response for the user

## Tech Stack Used

- Neo4j
- LangChain
- Groq (Gemma2-9b-It model)
- Python
- Dotenv

## Note

This project requires valid Neo4j database credentials and a Groq API key. Ensure you have the necessary access and have properly configured the environment variables before running the application.


🚀 Overview

This project is an LLM-powered SQL Query Generator that converts natural-language questions into valid, executable MySQL queries.

Built using Gemini 2.5 Flash, LangChain, and strong prompt engineering, the system ensures schema-aware SQL output without hallucinations.

🧠 Features

Prompt-engineered SQL generation using Gemini Flash

Semantic few-shot retrieval with HuggingFace + Chroma

Schema inspection using LangChain’s SQLDatabase

Strict SQL-only output (no markdown, no explanations)

Dynamic injection of:

relevant examples

database schema

user query

LCEL-based modular workflow

📂 Tech Stack

LangChain

Gemini 2.5 Flash

HuggingFace Embeddings

Chroma Vector Store

MySQL

Prompt Engineering

▶️ How It Works

User inputs a natural-language question

System retrieves the most similar example using semantic similarity

Schema details + retrieved examples + user question → injected into prompt

Gemini Flash generates raw SQL only

(Optional) SQL can be executed against the DB (disabled in SQL-only mode)

📌 Example Queries

“Show all t-shirts with their discount percentage”

“How many white color Levi’s t-shirts?”

“Total revenue from each category in 2024”

🚧 Future Enhancements

Add SQL execution with result tables

Add query validation and error correction

Add user-friendly UI for business users

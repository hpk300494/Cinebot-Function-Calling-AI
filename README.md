# 🎬 CineBot – AI Movie Recommendation Chatbot
![Python](https://img.shields.io/badge/Python-3.11-blue)

![OpenAI](https://img.shields.io/badge/OpenAI-Function%20Calling-green)

![LLM](https://img.shields.io/badge/LLM-Generative%20AI-orange)

![License](https://img.shields.io/badge/License-MIT-red)

An intelligent movie recommendation chatbot built using **Large Language Models (LLMs)** and **OpenAI Function Calling**.

The chatbot understands natural language, extracts user preferences, invokes structured functions to retrieve movie recommendations, and generates personalized responses.

---

## Project Overview

This project was developed as part of the **Advanced Certificate Program in Generative AI**.

The objective was to build an AI-powered conversational assistant capable of:

- Understanding user intent
- Extracting structured information
- Calling external functions
- Returning personalized recommendations
- Demonstrating modern LLM application architecture

---
## Project Documentation

A detailed technical report describing:

- System Architecture
- Dataset
- Recommendation Engine
- Data Processing
- EDA
- Chatbot Design
- Results

📄 **Project Report:** [docs/CineBot_Project_Report.pdf](docs/CineBot_Project_Report.pdf)
---

## Features

- Natural language conversation
- Function Calling
- Structured JSON responses
- Prompt Engineering
- Personalized recommendations
- Movie filtering
- Genre-based recommendations
- Interactive chatbot workflow

---

## Tech Stack

- Python
- OpenAI API
- Function Calling
- Jupyter Notebook
- JSON
- Prompt Engineering

---

## Repository Structure

```
cinebot-function-calling-ai/

├── notebooks/
│   └── CineBot_Recommender.ipynb
│
├── images/
│   ├── architecture.png
│   ├── workflow.png
│   └── demo.png
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Workflow

```
User Query
      │
      ▼
Prompt Engineering
      │
      ▼
LLM
      │
      ▼
Function Calling
      │
      ▼
Movie Database
      │
      ▼
Recommendations
      │
      ▼
LLM Response
```

---

## Function Calling

The chatbot utilizes OpenAI Function Calling to convert user requests into structured JSON before executing backend functions.

Example:

```json
{
  "name": "recommend_movies",
  "arguments": {
    "genre": "Sci-Fi",
    "year": 2020
  }
}
```

---

## Example Queries

- Recommend action movies
- Suggest comedy movies from the 90s
- I like Christopher Nolan films
- Recommend movies similar to Interstellar
- Best horror movies after 2015

---

## Learning Outcomes

- Conversational AI
- Prompt Engineering
- Function Calling
- LLM Application Development
- JSON Schema
- Recommendation Systems

---

## Future Improvements

- Streamlit interface
- TMDB API integration
- LangChain support
- Vector database
- Semantic search
- User authentication
- RAG implementation

---

## License

MIT License

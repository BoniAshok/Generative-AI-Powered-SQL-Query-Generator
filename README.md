# 🤖 Generative AI-Powered SQL Query Generator
## 🔍 Project Overview
This is an end-to-end Generative AI-powered application that uses Google PaLM and LangChain to enable natural language interaction with a MySQL database. Built for AtliQ Tees, a T-shirt retail store, this system allows store managers and stakeholders to ask complex questions in plain English and receive accurate, real-time answers derived directly from the underlying data.

## 💡 Use Case
The database maintains essential records such as inventory, sales, and discounts. A store manager can ask:

"How many white color Adidas T-shirts do we have left in the stock?"

"How much sales will our store generate if we sell all extra-small size T-shirts after applying discounts?"

The system intelligently interprets these questions, generates precise SQL queries, executes them on the MySQL database, and returns user-friendly answers.

## 🧠 Key Technologies
Google PaLM: Large Language Model for natural language understanding and SQL generation

LangChain: Framework to connect LLMs with databases and tools

MySQL: Backend relational database storing real-time store data

Streamlit/FastAPI (Optional): For building a user-friendly web interface


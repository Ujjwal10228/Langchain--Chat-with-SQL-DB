# Langchain--Chat-with-SQL-DB
▶️ [Watch demo video](https://www.linkedin.com/posts/ujjwal-kumar-287831167_langchain-llm-dataanalytics-activity-7335251607460134912-XOj9?utm_source=share&utm_medium=member_desktop&rcm=ACoAACfPy0cB4xmfCQfT8bwgL14GtPTybUDasZ0)

**Description:**
This project demonstrates the integration of LangChain, Streamlit, and Groq’s Llama3-8b-8192 model to build an interactive chatbot interface that allows users to query SQL databases using natural language.

Users can choose between a local SQLite3 database (student.db) or connect to their own MySQL/PostgreSQL database through secure credentials. The chatbot is powered by a LangChain SQL agent, which interprets user queries, converts them to SQL commands, and returns the results conversationally.

**Key Features:**

📊 _Natural Language to SQL_: Converts user input to valid SQL queries using LLMs.

🔒 _Secure Credential Input_: Supports secure password input for MySQL/PostgreSQL.

🧠 _LLM-Powered Query Engine:_ Uses Groq-hosted LLaMA3-8B for contextual understanding.

💬 _Chat UI_: Built with Streamlit’s chat_input and chat_message APIs for real-time interaction.

📁 _Dynamic Database Connection_: Toggle between SQLite (read-only mode) and external MySQL/PostgreSQL databases via UI.

⚙️ _LangChain Toolkit Integration_: Utilizes LangChain’s SQLDatabaseToolkit for seamless LLM-database interaction.

**Technologies Used:**

🐍 Python

🌐 Streamlit (UI/UX)

🦜 LangChain (SQL Agent + Toolkit)

🧠 Groq (LLM API - Llama3-8b)

🗃 SQLite3 & MySQL/PostgreSQL (SQLAlchemy ORM)

🧩 SQLAlchemy (Database Abstraction)

**Use Cases:**

Rapid querying of student or academic databases.

Conversational analytics dashboards.

Interactive data exploration tools for non-technical users.

# text-to-sql-chatbot
## Natural Language → SQL → Answers
### Build, Deploy, and Integrate in Minutes

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

A cutting-edge, real-time chatbot that converts natural language queries into SQL code, providing instant insights and answers.

## What You Get

Ask a question in natural language and get back:

1. **Streaming Progress Updates**
2. **SQL Code Block** (By default only shown to "admin" users)
3. **Interactive Data Table**
4. **Charts** (Plotly visualizations)
5. **Natural Language Summary**

All streamed in real-time to your web component.

## Why text-to-sql-chatbot?

### ✅ Get Started Instantly
* Production chat interface
* Custom agent with your database
* Embed in any webpage

### ✅ Enterprise-Ready Security
**User-aware at every layer** — Identity flows through system prompts, tool execution, and SQL filtering
**Row-level security** — Queries automatically filtered per user permissions
**Audit logs** — Every query tracked per user for compliance
**Rate limiting** — Per-user quotas via lifecycle hooks

### ✅ Beautiful Web UI Included
**Pre-built `<text-to-sql-chatbot>` component** — No need to build your own chat interface
**Streaming tables & charts** — Rich components, not just text
**Responsive & customizable** — Works on mobile, desktop, light/dark themes
**Framework-agnostic** — React, Vue, plain HTML

### ✅ Works With Your Stack
**Any LLM:** OpenAI, Anthropic, Ollama, Azure, Google Gemini, AWS Bedrock, Mistral, Others
**Any Database:** PostgreSQL, MySQL, Snowflake, BigQuery, Redshift, SQLite, Oracle, SQL Server, DuckDB, ClickHouse, Others
**Your Auth System:** Bring your own — cookies, JWTs, OAuth tokens
**Your Framework:** FastAPI, Flask

### ✅ Extensible But Opinionated
**Custom t

## Installation

### Install via pip
```bash
pip install text-to-sql-chatbot
```

### Install via conda
```bash
conda install -c conda-forge text-to-sql-chatbot
```

## Quick Start

```python
from text_to_sql_chatbot import TextToSQLChatbot

# Initialize the chatbot
chatbot = TextToSQLChatbot()

# Ask a question
question = "What is the average salary of employees in the USA?"

# Get the response
response = chatbot.ask(question)

# Print the response
print(response)
```

## Usage

### Example 1: Use the chatbot to get the average salary of employees in the USA
```python
from text_to_sql_chatbot import TextToSQLChatbot

# Initialize the chatbot
chatbot = TextToSQLChatbot()

# Ask a question
question = "What is the average salary of employees in the USA?"

# Get the response
response = chatbot.ask(question)

# Print the response
print(response)
```

### Example 2: Use the chatbot to get the top 10 countries by GDP
```python
from text_to_sql_chatbot import TextToSQLChatbot

# Initialize the chatbot
chatbot = TextToSQLChatbot()

# Ask a question
question = "What are the top 10 countries by GDP?"

# Get the response
response = chatbot.ask(question)

# Print the response
print(response)
```

## Configuration

| Option | Type | Default | Description |
| --- | --- | --- | --- |
| `database` | str | "your_database" | The name of the database to use |
| `llm` | str | "your_llm" | The name of the language model to use |
| `auth_system` | str | "your_auth_system" | The name of the authentication system to use |

## Contributing

Contributions are welcome! If you'd like to contribute to text-to-sql-chatbot, please fork the repository and submit a pull request.

## License

text-to-sql-chatbot is released under the MIT license.

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

Copyright (c) 2026 text-to-sql-chatbot contributors. All rights reserved.

This project is maintained by [Your Name](https://yourwebsite.com).
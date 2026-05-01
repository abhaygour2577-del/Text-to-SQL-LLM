Text-to-SQL Query Generation System
Problem Statement

Manual database querying requires SQL knowledge, making data retrieval difficult for non-technical users.

Solution

This project converts natural language questions into executable SQL queries using Large Language Models.

Technologies Used
Python
Qwen LLM
Hugging Face Transformers
SQLite
Pandas
Gradio
Features
Natural language to SQL conversion
SQL query execution
User-friendly interface
Real-time query generation

Example

Input:
"Show all employees with salary greater than 50000"

Generated SQL:

SELECT * FROM employees WHERE salary > 50000;

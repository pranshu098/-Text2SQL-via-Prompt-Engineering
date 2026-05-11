# -Text2SQL-via-Prompt-Engineering
Text-to-SQL: Bridging the Gap Between Human Language and Databases   
<img width="701" height="473" alt="Screenshot 2026-05-11 at 8 17 34 AM" src="https://github.com/user-attachments/assets/24081894-4ddf-4a3b-ae1c-ed13c6f4ec81" />

## How It Works: From a Simple Question to a Complex Query

The conversion of a user's question into an executable SQL query involves a multi-step process:

1.  **Natural Language Understanding (NLU):** The system first analyzes the user's input to decipher its meaning. This involves identifying key entities (like specific columns or tables), the relationships between them, and the user's ultimate goal (e.g., to filter, aggregate, or sort data).

2.  **Schema Linking:** Once the intent is understood, the system maps the identified entities from the natural language question to the specific tables and columns within the database's schema. This is a critical step to ensure the generated query is accurate and relevant to the available data structure.

3.  **SQL Generation:** With the user's intent and the relevant database schema components identified, the AI model constructs the appropriate SQL query. This can range from a simple `SELECT` statement to a complex query involving multiple `JOIN`s, `WHERE` clauses, and aggregate functions.

4.  **Query Execution and Response:** The generated SQL query is then executed against the database. The retrieved data is presented back to the user in a clear and understandable format, often as a table, chart, or a natural language summary.

   Project Workflow :

  User Query
    ↓
Prompt Builder
    ↓
Gemini API
    ↓
SQL Generation
    ↓
SQLite Execution
    ↓
Results Returned

   

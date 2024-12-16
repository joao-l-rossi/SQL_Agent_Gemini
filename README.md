# SQL Agent with Gemini Integration

This repository contains a Jupyter notebook that demonstrates how to interact with an SQLite database and utilize Google Gemini AI for SQL-related tasks.

## Features

- **Database Interaction**: Functions to connect to an SQLite database, list tables, and query data.
- **Google Gemini Integration**: Leverages the Gemini AI API for generating or analyzing SQL queries.
- **Logging and Error Handling**: Simple logging and error handling to facilitate debugging.

## Requirements

- **Python 3.x**
- **Jupyter Notebook**
- **SQLite**
- **Google Gemini AI API Key**

## Dependencies

Install the required libraries using `pip`:

```bash
pip install google-generativeai
```

## Setup

1. **Clone the Repository**

2. **Set Up Environment Variables**

   Export your Google Gemini API key:

   ```bash
   export GOOGLE_API_KEY="your_api_key_here"
   ```

3. **Database Setup**

   Ensure you have an SQLite database file named `chinook.db` or modify the notebook to use your own database file.

## Usage

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open the `Functions_Gemni.ipynb` notebook.

3. Execute the cells to:

   - Connect to the SQLite database.
   - List tables in the database.
   - Execute queries using the Gemini AI integration.

## Example Functions

- **List Tables**

  ```python
  list_tables()
  ```

  This function returns a list of all tables in the connected SQLite database.

- **Execute Queries**

  ```python
  execute_query("SELECT * FROM customers;")
  ```

  This function executes a given SQL query and returns the results.

## Notes

- Ensure you have a valid Google API key for Gemini AI.
- Modify the database file path as needed.



# Natural Language → SQL Automation  
### n8n + Google Gemini + Supabase

Turn plain English questions into fully working SQL queries automatically.

## ⭐ Overview  
This project converts natural-language input into SQL using:

- **Google Gemini** – Generates SQL queries  
- **n8n** – Workflow automation  
- **Supabase PostgreSQL** – Executes SQL  

Users can type:

> "Show total sales by country"

and the system automatically generates SQL, runs it, and returns the results.

## 🔧 Tech Stack  

- n8n  
- Google Gemini  
- Supabase PostgreSQL   
- Workflow automation  

## 🔁 Workflow  

1. **Manual Trigger** – User enters a question  
2. **Gemini Node** – Converts natural language → SQL  
3. **Supabase Node** – Executes SQL  
4. **Output** – Returns JSON/table  

## 📌 Features  

- Natural language → SQL conversion  
- AI-generated queries  
- Automated execution  
- Secure database connection  
- Works with any SQL question based on your schema  

## 📂 Project Structure  
├── README.md
├── workflow/
│ └── nlq_to_sql.json
├── prompts/
│ └── gemini_prompt.txt
└── examples/
└── inputs_outputs.txt

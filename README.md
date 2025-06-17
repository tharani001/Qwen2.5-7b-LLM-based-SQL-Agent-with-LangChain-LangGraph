## 🚀 Overview

This project builds a modular SQL agent that:

- Parses user questions in natural language  
- Transforms them into SQL via the **Qwen2.5‑7B** model  
- Executes the SQL on **Chinook Database**  
- Validates and iterates queries using LangGraph nodes  
- Returns polished, human-readable answers

## 🧩 Key Features

- 💬 **NL-to-SQL Translation** leveraging Qwen2.5‑7B  
- ✅ **Validation Loop**: auto-checks and refines SQL before and after execution  
- 🔐 **Secure Execution** with parameterized queries  
- 🧠 **Agent Graph Workflow** using LangChain + LangGraph for modular query planning, execution, error recovery, and response synthesis.

## 🛠️ Stack

- **Model**: Qwen2.5‑7B (instruction-tuned)  
- **Agent Orchestration**: LangChain + LangGraph  
- **Database Integration**: Chinook database
- **Execution & Monitoring**: Iterative query validation via tool-based nodes
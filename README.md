# 🤖 Agentic AI Project Builder

An intelligent multi-agent system that automatically plans, designs, and builds software projects from a simple user prompt.

---

## 🏗️ Architecture

* **Planner Agent**
  Converts a user prompt into a structured project plan (features, tech stack, files).

* **Architect Agent**
  Breaks the plan into detailed engineering tasks with clear dependencies.

* **Coder Agent**
  Implements each task, writes code into files, and uses tools like a real developer.

---

## 🚀 Getting Started

### ✅ Prerequisites

* Python 3.11+
* Install **uv** (Python package manager)
* Groq API Key (for LLM access)

---

### ⚙️ Installation

1. Create virtual environment:

```bash
uv venv
```

2. Activate virtual environment:

**Windows (PowerShell):**

```bash
.venv\Scripts\activate.ps1
```

3. Install dependencies:

```bash
uv pip install -r pyproject.toml
```

4. Create a `.env` file and add:

```env
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 🧪 Example Prompts

* Create a to-do list application using HTML, CSS, and JavaScript
* Create a simple calculator web app
* Create a blog API using FastAPI and SQLite

---

## 💡 How It Works

1. User gives a prompt
2. Planner creates a project plan
3. Architect generates step-by-step tasks
4. Coder writes and updates project files automatically

---

## 🛠️ Tech Stack

* Python
* LangGraph
* LangChain
* Groq API
* Pydantic

---

## 📌 Notes

* Ensure `.env` file is correctly configured
* All generated files are stored in the project directory
* The system uses tool-calling agents for file operations

---

# 🚀 Agentic AI Prompt-to-Code Application


AI coding agent is an *agentic AI application* that generates fully functional web applications from a single user prompt. Think of it as an **AI software engineer** that can plan, architect, and code projects end-to-end! ✨


## 🌟 Features

- 🖥 Generate fully functional web apps (calculator, to-do list, portfolio, etc.)  
- 🧩 Modular workflow: **Planner → Architect → Coder**  
- 📊 State management to track progress and ensure stepwise completion  
- 🔍 Debug AI agent decisions visually using AI debugging tools  
- 🤖 Built using **LangGraph**, **LangChain**, and **Groq Cloud GPT**  
- 💡 Open-source GPT OSS access for free LLM integration  

---

## 🛠 Tech Stack

- **Python** – main orchestration language  
- **LangGraph & LangChain** – define agent flows and nodes  
- **Groq Cloud GPT** – open-source LLM access  

---

## 🏗 Architecture & Workflow

1. **Planner Node** – Generates a project plan from your prompt (features, tech stack, file structure).  
2. **Architect Node** – Creates detailed instructions for each file.  
3. **Coder Node** – Generates code and writes files to disk.  
4. **Looping & State Management** – Keeps track of completed steps and auto-advances.  
5. **Agent Debugger** – Inspect agent decisions and states visually.  

---

## 💻 Getting Started

### Prerequisites

- Python 3.10+  
- Groq Cloud API key  

### Installation

```bash
git clone <your-repo-url>
cd coder-buddy
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows
pip install -r requirements.txt

```
---
#### Add your Groq Cloud API key to .env or environment variables.

## Usage

```bash
python main.py
```
Enter a prompt, e.g.:

```bash
"Create a calculator web application"
```

Watch as the agent plans → architects → codes your project.

Check the output/ folder for your generated web app.


## 📂 Example Prompts

- "Create a to-do list app with add/delete functionality"

- "Generate a personal portfolio website with HTML, CSS, JS"

- "Build a weather dashboard using API calls"

## 🎯 Learnings & Takeaways

- Build agentic AI workflows for prompt-to-code applications

- Handle structured outputs and orchestrate LLMs effectively

- Modular, resume-worthy Python projects for AI engineering

- Debug AI agent behavior using AI tools in PyCharm
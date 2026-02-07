# 📝 Todo In-Memory Python Console App

A **command-line Todo application** built using **spec-driven development** with **Claude Code** and **Spec-Kit Plus**.  
This project demonstrates the **Agentic Dev Stack workflow** by transforming specifications into a working Python console app — without manual coding.

---

## 🎯 Objective

Build a **basic-level Todo application** that stores tasks **in memory** and supports full CRUD operations, while strictly following:

- Spec-driven development
- Clean code principles
- Proper Python project structure
- Agentic Dev Stack workflow

---

## 🚀 Development Workflow (Agentic Dev Stack)

This project follows the official workflow:

1. **Write Specification** using Spec-Kit Plus
2. **Generate Plan** from the specification
3. **Break Plan into Tasks**
4. **Implement using Claude Code**
5. **Iterate & Review**

⚠️ **No manual coding was done.**  
All implementation was generated through Claude Code based on specs.

---

## ✅ Features Implemented

✔ Add a new task (title + description)  
✔ View all tasks with status indicators  
✔ Update task details  
✔ Delete tasks by ID  
✔ Mark tasks as complete / incomplete  

---

## 🧠 Application Behavior

- Tasks are stored **in memory** (no database)
- Each task has:
  - ID
  - Title
  - Description
  - Completion status
- Console-based interactive menu
- Clean separation of concerns

---

## 🛠️ Technology Stack

- **Python** 3.13+
- **UV** (Python package manager)
- **Claude Code**
- **Spec-Kit Plus**

---

## 📁 Project Structure
├── src/
│ ├── main.py
│ ├── todo.py
│ └── utils.py
│
├── specs/
│ ├── spec-v1.md
│ ├── spec-v2.md
│ └── plan.md
│
├── CLAUDE.md
├── constitution.md
├── README.md
└── pyproject.toml

---

## 🖥️ Running the Application

### 1️⃣ Clone the Repository
```bash
git clone <your-repo-url>
cd todo-console-app
2️⃣ Install Dependencies using UV
uv sync
3️⃣ Run the App
python src/main.py
🪟 Windows Users — WSL 2 Setup (Required)

Windows users must use WSL 2 for development.

Install WSL 2
wsl --install
Set WSL 2 as Default
wsl --set-default-version 2
Install Ubuntu 22.04
wsl --install -d Ubuntu-22.04

After installation:

Open Ubuntu terminal

Clone and run the project inside WSL

📄 CLAUDE.md

The CLAUDE.md file contains:

Claude Code instructions

Rules for spec-driven development

Constraints for agent behavior

📜 Constitution File

The constitution.md defines:

Coding standards

Architectural rules

Development constraints

Quality requirements

📌 Notes

This project is evaluated based on:

Specs quality

Planning clarity

Iterations

Final implementation

Focus is on process, not just output.

✨ Author

Muhammad Sajid Sheikh
Built as part of an Agentic AI & Spec-Driven Development evaluation.

# 🎬 YouTube Shorts AI Agent 

This folder contains a **Multi-Agent AI system**. 
It automatically creates **YouTube Shorts content for developers** by coordinating multiple AI agents.
Just write the topic and it will generate the script in minutes!!.
---

## 📂 Project Structure
── agent.py

├── loop_agent.py

├── loop_agent_runner.py

├── requirements.txt

├── util.py

├── scriptwriter_instruction.txt

├── shorts_agent_instruction.txt

├── visualizer_instruction.txt

├── .env

└── init.py

---

##  What This Project Does

This project uses **multiple AI agents** to:

1. Write a **short video script**
2. Generate **visual ideas**
3. Format the final output in **Markdown**

---

## 🤖 Agents in This Project

### 1. Root Agent

Defined in:

- `agent.py` fileciteturn0file1

This file creates:

- `ShortsScriptwriter`
- `ShortsVisualizer`
- `ConceptFormatter`
- And combines them into `youtube_shorts_agent`.

---

### 2. Loop Agent Version

Defined in:

- `loop_agent.py` fileciteturn0file2

This version uses `LoopAgent` to run the agents in sequence automatically.

---

### 3. Runner Script

Defined in:

- `loop_agent_runner.py` fileciteturn0file3

This file:
- Creates sessions
- Runs the agent
- Prints the final response

---

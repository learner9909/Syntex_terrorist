# Syntex_terrorist
# AutoTask AI 🚀  
An Autonomous Goal-Oriented AI Agent

AutoTask AI is an autonomous AI agent that can understand a high-level goal, break it into steps, select appropriate tools, and complete tasks with minimal human intervention.

This project is inspired by modern agentic AI systems (AutoGPT-style) and is designed for hackathons, academic evaluation, and portfolio demonstration.

---

## 🧠 Key Features

- Natural language goal understanding
- Automatic task decomposition
- Tool-based autonomous execution
- Memory-driven reasoning
- Feedback and self-evaluation loop
- Modular and extensible architecture

---

## 🏗️ System Architecture

```mermaid
flowchart TD
    U[User Goal] --> GI[Goal Interpreter]
    GI --> TP[Task Planner]
    TP --> AC[Agent Core]
    AC --> TM[Tool Manager]
    TM --> FT[File Tools]
    TM --> DT[Data Tools]
    TM --> WT[Web Tools]
    TM --> RT[Report Tools]
    AC --> MEM[Memory]
    MEM --> AC
    AC --> EV[Evaluator]
    EV --> OUT[Final Output]

# 🧠 LangGraph ReAct Agent with Memory

This repository demonstrates how to build a **ReAct-style agent** using **LangGraph**, with:
- Tool-based reasoning (ReAct pattern)
- Persistent memory using `MemorySaver`
- Visual graph representation using **Mermaid diagrams**

It is designed as a **learning-first, minimal, and clear** example for anyone getting started with LangGraph agents.

---

## 📌 What is ReAct?

**ReAct (Reason + Act)** is an agent pattern where the model:
1. **Reasons** about the user query
2. **Acts** by invoking tools when needed
3. **Observes** the results
4. Repeats until a final answer is produced

LangGraph provides a **graph-based abstraction** to build such agents cleanly and extensibly.

---


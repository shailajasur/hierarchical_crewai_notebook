
# 🧠 Hierarchical CrewAI: Multi-Level Agent Collaboration

This notebook demonstrates the use of **hierarchical agent orchestration** using [CrewAI](https://github.com/joaomdmoura/crewAI), simulating a layered system where high-level planners assign tasks to sub-agents who execute independently and report upward.

---

## 📌 What’s Inside

This notebook walks through:
- Building a **top-level manager agent**
- Defining **multiple specialized sub-agents** (e.g., researcher, writer, reviewer)
- Task delegation and structured output flow
- Execution of a **multi-step plan** through hierarchical agents

---

## 📁 File

- `Hierarchical_CrewAI.ipynb`: Complete walkthrough in notebook form

---

## 🚀 How to Run

1. Install dependencies:
```bash
pip install crewai
```

2. Optionally set your OpenAI API key:
```python
import os
os.environ["OPENAI_API_KEY"] = "your_openai_key"
```

3. Run the notebook in Jupyter or Colab.

---

## 💡 Use Cases

- Research planning with delegation (PM → Analyst → Writer)
- Strategic roadmaps (Exec → Manager → Team leads)
- Autonomy-driven assistants with layered capabilities

---

## 🛠️ Future Improvements

- Add memory for long-running threads
- Integrate open-source LLMs for full local operation
- Visualize agent communication using network graphs

---

## 👤 Author

**Shailaja Suresh**  
[LinkedIn](https://www.linkedin.com/in/shailajasuresh/) | [GitHub](https://github.com/YOUR_USERNAME)
"# hierarchical_crewai_notebook" 

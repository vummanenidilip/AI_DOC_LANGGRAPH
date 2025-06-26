
# 🧠 AI Document Reviewer Agent (LangGraph + LangChain + FAISS)

This project demonstrates a modular and intelligent document reviewer agent built using:
- 🧩 LangGraph for stateful graph-based orchestration
- 🤖 LangChain for LLM + tool integration
- 📄 FAISS for vector-based document retrieval
- 🧠 OpenAI GPT-4o for clause analysis and reasoning

## 📚 Use Case

The agent reviews uploaded legal or policy documents (e.g., contracts), and can:
- Retrieve clauses from vector DB based on user queries
- Interpret and summarize legal content using GPT-4o
- Highlight missing terms, risks, or important points

### 📝 Example Queries:
- "Does this contract mention termination conditions?"
- "What are the payment terms?"
- "Is GDPR compliance mentioned?"

## 🛠️ Project Structure

```
📁 aidocmain.ipynb          # Jupyter Notebook with LangGraph implementation
📄 sample_contract.txt      # Sample input contract document
🧾 requirements.txt         # All dependencies for running the notebook
```

## 🚀 How to Run

1. Clone this repository  
2. Set your `OPENAI_API_KEY` in a `.env` file  
3. Install requirements:
```bash
pip install -r requirements.txt
```
4. Run the notebook: `aidocmain.ipynb`

## ✅ Features
- Built-in clause search tool using FAISS
- Tool routing and memory state using LangGraph
- Loopback support for dynamic query refinement
- Designed for extensibility (add more tools easily)

## 🧠 Ideal For
- LegalTech automation
- AI-powered document review systems
- Beginners learning LangGraph + LangChain agents

---

Feel free to fork or contribute!  
If you're just getting started with LangGraph, this is a great reference project.

Made with 💡 by [Dilip Vummaneni](https://www.linkedin.com/in/vummanenidilip/)

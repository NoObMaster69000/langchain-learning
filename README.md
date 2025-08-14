# 📘 LangChain Learning Series (Expanded 16-Part Edition)

A hands-on guide to building LLM-powered applications from scratch. This repository contains a structured, beginner-to-advanced LangChain learning series in 16 Jupyter notebooks.

## 🎯 What You’ll Learn
- **Core Concepts:** Talk to LLMs using prompts, parsers, and chains.
- **RAG:** Build Retrieval-Augmented Generation (RAG) applications from your own documents.
- **Agent Fundamentals:** Create agents that can reason and use custom tools.
- **Advanced Agents:** Build complex, multi-step agents with memory and planning capabilities.
- **Multi-Agent Systems:** Design and orchestrate collaborative AI teams with advanced communication patterns (MCP/A2A).
- **Evaluation & Debugging:** Use LangSmith to trace, debug, and evaluate your applications.
- **Deployment:** Deploy your agents as production-ready REST APIs using LangServe.

## 🗂️ Folder Structure
```
/
├── notebooks/
│   ├── 01_models_prompts_parsers.ipynb
│   ├── 02_chains.ipynb
│   ├── 03_agent_fundamentals.ipynb
│   ├── 04_custom_tools_and_reasoning.ipynb
│   ├── 05_document_loaders_text_splitters.ipynb
│   ├── 06_embeddings_vectorstores.ipynb
│   ├── 07_rag.ipynb
│   ├── 08_memory_in_chains_and_agents.ipynb
│   ├── 09_advanced_agents_and_langgraph.ipynb
│   ├── 10_real_world_agents_with_apis.ipynb
│   ├── 11_evaluation_with_langsmith.ipynb
│   ├── 12_final_project_autonomous_assistant.ipynb
│   ├── 13_multi_agent_collaboration.ipynb
│   ├── 14_advanced_control_and_persistence.ipynb
│   ├── 15_multi_agent_communication_patterns.ipynb
│   └── 16_deploying_agents_with_langserve.ipynb
├── data/
│   ├── annual-report.pdf
│   ├── movie-plots.csv
│   └── product-info.txt
├── outputs/
│   └── (Generated content, e.g., chroma_db/)
├── .env
├── requirements.txt
└── README.md
```

## ⚙️ Setup

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-name>
    ```

2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up your API keys:**
    - If it doesn't exist, rename `.env.example` to `.env`.
    - Add your API keys (e.g., `OPENAI_API_KEY`, `LANGCHAIN_API_KEY`) to the `.env` file.

## 🚀 How to Use
1.  Start with the first notebook: `notebooks/01_models_prompts_parsers.ipynb`.
2.  The notebooks follow a logical progression, building on previous concepts.
3.  Experiment with the code, break things, and then try to fix them. Learning happens when you debug!

## 🧠 Pro Tips
- Use `verbose=True` in chains and agents to see the internal reasoning steps.
- Always test your document retrieval step separately before building a full RAG pipeline.
- Start using LangSmith early in your development process for easier debugging.
- For complex agents, sketching out the workflow on paper before building the graph can save a lot of time.

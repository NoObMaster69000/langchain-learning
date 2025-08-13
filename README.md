# 📘 LangChain Learning Series

A hands-on guide to building LLM-powered applications from scratch. This repository contains a structured, beginner-to-advanced LangChain learning series in 10 Jupyter notebooks.

## 🎯 What You’ll Learn
- How to talk to LLMs using prompts, parsers, and chains.
- Build Retrieval-Augmented Generation (RAG) applications from your own documents (PDFs, TXT).
- Create autonomous agents that can search the web, perform calculations, and analyze data.
- Use LangSmith to debug, trace, and evaluate your LLM applications.
- Build and deploy real-world AI assistants and chatbots.

## 🗂️ Folder Structure
```
/
├── notebooks/
│   ├── 01_models_prompts_parsers.ipynb
│   ├── 02_chains.ipynb
│   ├── 03_agents.ipynb
│   ├── 04_document_loaders_text_splitters.ipynb
│   ├── 05_embeddings_vectorstores.ipynb
│   ├── 06_rag.ipynb
│   ├── 07_memory.ipynb
│   ├── 08_tool_calling_langgraph.ipynb
│   ├── 09_langsmith.ipynb
│   └── 10_build_deploy_ai_assistant.ipynb
├── data/
│   ├── annual-report.pdf
│   ├── movie-plots.csv
│   └── product-info.txt
├── outputs/
│   └── (Generated summaries, QA results, etc.)
├── .env
├── README.md
└── requirements.txt
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
    - Rename the `.env.example` file to `.env`.
    - Add your API keys (e.g., `OPENAI_API_KEY`) to the `.env` file.

## 🚀 How to Use
1.  Start with the first notebook: `notebooks/01_models_prompts_parsers.ipynb`.
2.  Follow the instructions in each notebook, run the code cells, and complete the exercises.
3.  Experiment with the code, break things, and then try to fix them. Learning happens when you debug!
4.  The notebooks are designed to be modular, but they follow a logical progression.

## 🧠 Pro Tips
- Use `verbose=True` in chains and agents to see the internal reasoning steps. This is invaluable for debugging.
- Always test your document retrieval step separately before building a full RAG pipeline. If you don't get good documents back, the LLM can't give a good answer.
- Start using LangSmith early in your development process. It makes debugging complex chains and agents much easier.
- Don't be afraid to use smaller, local models for initial development and testing. You can switch to more powerful models for final implementation.

# 🏏 Cricket Stats RAG Assistant
A Retrieval-Augmented Generation (RAG) application built with **LlamaIndex**.

## 🚀 Overview
This project uses a hybrid data strategy to answer complex cricket queries:
- **Unstructured Data:** Wikipedia match reports and player biographies.
- **Structured Data:** Cricsheet ball-by-ball JSON/CSV statistics.
- **Routing:** A `RouterQueryEngine` to intelligently switch between narrative and statistical engines.

## 🛠️ Setup
1. Install dependencies: `pip install -r requirements.txt`
2. Set your `GOOGLE_API_KEY` in Colab Secrets.
3. Run the main notebook to initialize the engines.
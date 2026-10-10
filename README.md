# Deep Research Agent

An autonomous AI agent that searches the internet, conducts multi-step research, synthesizes findings, and generates detailed markdown reports. 

Built using **LangChain**, **LangGraph**, **Ollama**, and **Tavily**, this project is designed to run inside a **Kaggle Notebook** utilizing it's free GPUs.

## 🚀 Features
- **Autonomous Planning & Sub-agents:** Automatically breaks down complex user queries and delegates research tasks.
- **Web Search & Scraping:** Uses Tavily search combined with automated markdown scraping to extract up-to-date web data.
- **Structured Reports:** Generates professional reports complete with clear headings, summaries, and inline citations.
- **Kaggle-Ready:** Sets up and runs local open-source models via Ollama entirely within Kaggle.

## 📂 Project Structure
- `Ollama on kaggle notebook/deep-research.ipynb`: The end-to-end Jupyter notebook containing the full agent implementation.

## ⚙️ Quick Start (Kaggle)
1. Open `deep-research.ipynb` inside the `Ollama on kaggle notebook` folder.
2. Add your **Tavily** and **LangSmith** API keys to your Kaggle Secrets (`TAVILY_API_KEY`, `LANGSMITH_API_KEY`).
3. Run the cells to install dependencies, boot up Ollama, and start researching!

## 📄 License
This project is open-source under the [Apache-2.0 License](LICENSE).

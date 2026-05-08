# Multi-Agent Financial AI Analyst 📈

A sophisticated Multi-Agent System (MAS) built using the **Phidata** framework and **Groq** (LLaMA 3) to provide real-time financial analysis, stock market insights, and web-verified news.

## 🚀 Overview
Unlike standard chatbots, this project utilizes **Agentic AI**. It consists of specialized agents that possess "tools" (APIs) to interact with the real world. The system can autonomously decide whether to fetch live stock data via Yahoo Finance or perform a broad web search to verify the latest market sentiment.

### Key Components:
* **Web Search Agent:** Powered by DuckDuckGo to find and cite the latest news and sources.
* **Finance AI Agent:** Integrated with `yfinance` to extract stock prices, analyst recommendations, and company fundamentals.
* **Multi-Agent Orchestrator:** A lead agent that coordinates the sub-agents to deliver a comprehensive, structured response.

## 🛠️ Tech Stack
* **Framework:** [Phidata](https://www.phidata.com/) (Agentic Workflow Orchestration)
* **LLM:** Groq (LLaMA 3-70B) for ultra-fast inference.
* **Language:** Python 3.x
* **APIs/Tools:** yfinance, DuckDuckGo Search.
* **Environment:** Dotenv for secure secret management.

## 📋 Features
- **Real-time Data:** Fetches live market data rather than relying on training data cutoffs.
- **Source Transparency:** Always provides clickable sources for web-based information.
- **Structured Output:** Automatically formats complex financial data into readable tables.
- **Multi-Turn Reasoning:** Capable of comparing multiple stocks and identifying trends across different data sources.

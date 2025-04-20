# Deep Research AI Agentic System
This project implements an **AI Agentic System** designed to perform **deep research** by crawling the web using **Tavily**, processing the data with **LangChain**, and orchestrating workflows via **LangGraph**.

## Objective
To build a dual-agent system:
- **Research Agent**: Crawls the web and gathers relevant information.
- **Drafting Agent**: Analyses the gathered data and drafts meaningful answers.

This system is designed for high-quality, in-depth information extraction from online sources to answer user queries intelligently.

## Architecture
```text
User Query
   ↓
[ Research Agent ] — Tavily API → Web Documents → Summarised Data
   ↓
[ Drafting Agent ] — LLM (OpenAI/GPT) → Final Answer
   ↓
  Output to User

```
- Tool | Purpose
- Python | Core programming language
- LangChain | LLM integration and workflows
- LangGraph | Agent orchestration with graphs
- Tavily API | Web crawling and search
- OpenAI API | Drafting responses from research
- Colab | Development and testing

**Sample Output**
![image](https://github.com/user-attachments/assets/1cb95ed8-2dbf-4cb3-ad44-43686b6eb284)

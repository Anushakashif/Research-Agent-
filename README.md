# 🔬 ResearchMind — AI Research Agent

> **Drop a topic. Get a fully written, cited, and critiqued research report in seconds.**

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-1.0-green?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-UI-red?style=flat-square&logo=streamlit)

---



https://github.com/user-attachments/assets/13bca5aa-3006-4572-81b4-432bbfed62de



## What Is This?

Most AI tools give you a chatbot. **ResearchMind gives you a research team.**

Four specialized AI agents collaborate in a pipeline — each with a single job, each doing it well:

```
You type a topic  →  4 agents get to work  →  You get a polished report
```

No copy-pasting from Google. No stitching tabs together. Just results.

---

## The Pipeline

| Step | Agent | Job |
|------|-------|-----|
| 01 | 🔍 **Search Agent** | Hunts the web for the most relevant, recent sources |
| 02 | 📄 **Reader Agent** | Scrapes and extracts deep content from the top URLs |
| 03 | ✍️ **Writer Chain** | Synthesizes everything into a structured research report |
| 04 | 🧐 **Critic Chain** | Reviews the report, scores it, and suggests improvements |

---

## Demo

```
Topic: "Mars colonization plan by spaceX"

→ Search Agent finds 5 sources from arXiv, MIT, Google DeepMind...
→ Reader Agent scrapes the most relevant one in full
→ Writer drafts a 600-word report with Introduction, Key Findings, Conclusion & Sources
→ Critic scores it 8/10 and flags two areas to strengthen
```

---

## Features

- ⚡ **One-click pipeline** — type a topic, hit Run, done
- 🧠 **Multi-agent architecture** — each agent is specialized, not a swiss-army knife prompt
- 📝 **Structured reports** — Introduction, Key Findings, Conclusion, Sources. Every time.
- 🎯 **Built-in critic** — the pipeline reviews its own output so you don't have to
- ⬇️ **Download as Markdown** — take your report anywhere
- 🖥️ **Clean Streamlit UI** — no CLI, no JSON, no headaches

---

## Stack

- **[LangChain 1.0](https://langchain.com)** — `create_agent` for search & reader agents
- **[Tavily](https://tavily.com)** — real-time web search API
- **[BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)** — URL scraping
- **[OpenAI GPT-4o-mini](https://openai.com)** — LLM backbone
- **[Streamlit](https://streamlit.io)** — frontend UI

---

## Why Multi-Agent?

Single-prompt AI gives you one answer. Multi-agent AI gives you a **process**.

Each agent in ResearchMind has a narrow, clear job. The Search Agent doesn't write. The Writer doesn't search. The Critic doesn't scrape. This separation means each step is better, more reliable, and easier to debug or swap out.

It's the difference between asking one person to do everything and hiring a team.

---



---

<p align="center">Built with LangChain 1.0 · Powered by GPT-4o-mini · Deployed with Streamlit</p>

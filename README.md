# 📈 Founder Feed

A summarization agent that turns startup news, tweets, and blog posts into a clean daily digest for busy founders and investors.

This is a personalizable RAG + summarization pipeline that grabs RSS feeds or URLs, chunks content, and distills it into a daily insight report.

---

## 🔧 Features

- 📰 Pull from RSS or curated URLs
- 🧠 Summarize with LangChain + LLM
- 🗂️ Output in Markdown or Notion-compatible format
- 🧩 RAG support for deeper topic context

---

## ⚙️ Setup

```bash
git clone https://github.com/yourname/founder-feed.git
cd founder-feed
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt

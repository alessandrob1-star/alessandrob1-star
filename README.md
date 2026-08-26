<img width="1000" height="300" alt="Profile banner" src="https://github.com/user-attachments/assets/41c9d870-bb40-437c-b3f9-77e25c455f51" />




# 👋 Hi, I'm Alessandro Benevelli


🎓 B.Sc. Computer Science student at OPIT — Machine Learning & AI track

I build AI applications that combine **multi-agent orchestration**, **Large Language Models**, **deterministic safeguards**, **persistent memory**, and **human-in-the-loop workflows**.

My recent work focuses on local-first and cloud-backed systems: Python/PySide6 desktop apps, browser dashboards, regulatory-intelligence tools, document-intelligence workflows, Ollama/Qwen local models, OpenAI API integrations, Amazon Bedrock, CockroachDB, Docker, and n8n automation.

I am especially interested in reliable, explainable AI systems where the model supports decisions without silently taking control of them.

---

## 🚀 Current Focus

* **AI Engineering:** LLM applications, agentic workflows, retrieval, model orchestration, and evaluation.
* **Multi-Agent Systems:** specialist agents for profile analysis, regulatory monitoring, document classification, memory, and policy enforcement.
* **Human-Controlled Automation:** approval gates, deterministic rule engines, explainable outputs, restore paths, and audit-friendly state.
* **Interfaces:** Python/PySide6 desktop dashboards, browser-based web apps, local launchers, reports, and workflow tools.
* **Model Runtimes:** Ollama/Qwen for local execution, OpenAI API for grounded assistants, and Amazon Bedrock for document intelligence.
* **Persistence and Infrastructure:** CockroachDB, local file stores, Docker, AWS Lambda/API Gateway/S3/SQS, CloudWatch, and GitHub Actions.

---

## 💻 Projects

### Featured AI and automation projects

* **[DocWeave — Bulk PDF Renaming with Persistent Agent Memory](https://github.com/alessandrob1-star/cockroachdb-aws-agentic-memory-docweave)**
  A PySide6 desktop application for messy PDF folders: it extracts document content, uses **Amazon Bedrock Nova** to propose document classes, safer filenames, and destination folders, then requires explicit human approval before any file is moved.
  **Technical adoption:** CockroachDB as persistent agent memory, six-table file history, reversible rename/restore workflow, AWS Lambda/API Gateway/S3/SQS cloud slice, CloudWatch evidence, Bedrock model calls, migration scripts, and a dashboard built around review rather than blind automation. [Watch the 2:58 demo](https://youtu.be/p1QFV6ahOJo).

* [**Dr. G.D.P.R. & AI Act Navigator**](https://github.com/alessandrob1-star/dr-gdpr-ai-act-navigator)
  A multi-agent GDPR and EU AI Act compliance application with both a browser web app and a native desktop dashboard. It turns a guided company profile into a risk assessment, matched regulatory evidence, timeline, progress view, action workspace, and grounded Dr. A assistant.
  **Technical adoption:** Company Profile Agent, Regulatory Monitoring Agent, Regulatory Matching Agent, Dr. A Agent, deterministic Policy Agent safeguards, persistent company memory, official-document retrieval, live regulatory-update pipeline, PDF/DOCX exports, 25-language local UI dictionaries, Docker launchers, Ollama/Qwen local mode, and optional OpenAI `gpt-5.6-sol` runtime.

* [IT Help Desk Ticket Triage Assistant](https://github.com/alessandrob1-star/n8n-it-help-desk-ticket-triage)
  An importable **n8n** workflow that collects IT incidents through a form, classifies them with deterministic JavaScript rules, assigns category/priority/team/confidence, and uses a local **Ollama/Qwen** model only to format the final ticket.
  **Technical adoption:** hybrid rule-engine plus LLM workflow, explainable triage logic, local model runtime, credential-safe workflow export, and a design where the model presents the result but does not control the technical diagnosis.

### Python, data, and systems projects

* [NYTimes Article Search GUI](https://github.com/alessandrob1-star/nytimes-api-scraper)
  A Python desktop GUI and command-line tool for the New York Times Article Search API, with keyword search, result summaries, browser opening, `.env` configuration, and safe handling of private API keys.
  **Technical adoption:** Tkinter UI, Requests-based API integration, environment-variable configuration, CLI/GUI split, and GitHub-safe credential hygiene.

* [IP Subnet Calculator](https://github.com/alessandrob1-star/ip-subnet-calculator-code-in-place-2026)
  A Python/Tkinter IPv4 subnet calculator and learning tool with tabs for CIDR inspection, equal-size subnetting, and an offline tutor with optional OpenAI-powered answers.
  **Technical adoption:** RFC-aware IPv4 calculations, `/31` and `/32` handling, network scope classification, background-threaded online tutor requests, deterministic offline fallback, unit tests, and GitHub Actions on multiple Python versions.

* [📊 Grade Management System (C++)](https://github.com/alessandrob1-star/grade-manager-cpp)
  A C++ course-grade manager that stores courses, weighted assessments, bonus rules, formatted output, and persistent grade data across runs.
  **Technical adoption:** STL `map`/`vector`, file I/O with `fstream`, formatted terminal output, modular functions, basic validation, weighted-average logic, and MIT-licensed source.

* [Airbnb NYC Exploratory Data Analysis](https://github.com/alessandrob1-star/ibm-final-project-airbnb-data-analysis-2023)
  IBM Data Analytics capstone notebook analyzing Airbnb listings in New York City through cleaning, preprocessing, visualization, and business-oriented interpretation of pricing, room types, boroughs, and neighbourhood patterns.
  **Technical adoption:** Jupyter Notebook, Python, Pandas, NumPy, Matplotlib, Seaborn, data-quality checks, correlation analysis, and cautious interpretation of dataset limitations.

---

## 💡 Interests

* Computer Science
* Physics
* Finance
* Biology
* Chemistry

---

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/alessandrobenevelliopit/)

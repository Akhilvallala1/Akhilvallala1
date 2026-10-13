<h1 align="center">Hi, I'm Akhil 👋</h1>
<p align="center">
  ML/AI Engineer building LLM infrastructure, guardrails, and RAG systems. MS Data Science, Florida Atlantic University (GPA 3.95).
</p>

<div align="center">
  <a href="https://akhilvallala1.github.io" target="_blank">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/akhil-fau" target="_blank">LinkedIn</a> ·
  <a href="mailto:akhilvallalajs@gmail.com" target="_blank">Email</a>
</div>

---

### Currently

Lead Machine Learning Engineer at **Blocsmith LLC**, the team behind MoatDrop, a PII/PHI redaction platform. I build the document-extraction and Q&A engine on Gemini and Claude: context caching, PII redaction, RAG evaluation, and an MCP server for Claude Desktop, Cursor and Claude Code.

Open to AI/ML engineering roles.

### Featured projects

- **[conduit-ai-gateway](https://github.com/Akhilvallala1/conduit-ai-gateway)**: a proxy-first AI gateway. Every model call goes through one OpenAI-compatible API, a two-stage complexity router sends most traffic to cheap models and escalates only the ambiguous cases, and a build-time test keeps vendor SDKs out of everything except the provider layer.
- **[agentshield](https://github.com/Akhilvallala1/agentshield)**: a PII guardrail for agent-to-agent traffic that writes its own rules. Fast inline redaction (regex + Presidio), an async LLM auditor that catches what slipped through, and a validator that gates each new rule on eval metrics before it hot-loads into the live gateway. Built at the SF Tech Week hackathon.
- **[studyforge](https://github.com/Akhilvallala1/studyforge)**: an open-source, self-hosted adaptive learning platform. Turns a PDF, link or YouTube video into a course with quizzes, FSRS spaced repetition and per-concept mastery maps. Runs on Claude or a local model through Ollama.
- **[rival-radar](https://github.com/Akhilvallala1/rival-radar)**: automated competitive intelligence for B2B SaaS. A LangGraph + Claude pipeline that tracks competitor sites and posts a weekly Slack brief, with CI/CD to Cloud Run and a live demo.
- **[tiny-physics](https://github.com/Akhilvallala1/tiny-physics)**: my master's thesis. LoRA and instruction fine-tuning of SmolLM2 for on-device physics QA, a 30%+ gain over the base model on MMLU College Physics, shipped as quantized GGUF.

### Research

- Second author, *Unpacking Generative AI in Education*, IEEE Transactions on Computational Social Systems ([DOI 10.1109/TCSS.2025.3630587](https://doi.org/10.1109/TCSS.2025.3630587)). NSF-funded work at FAU; the PySpark data pipeline is in [this repo](https://github.com/Akhilvallala1/NSF-GenAI-Impact-on-the-Student-Project).

### Skills

**AI/ML:** LLM gateways and routing, guardrails and PII redaction (Presidio), RAG, evals, MCP, LangGraph, LangChain, OpenAI/Anthropic/Gemini APIs, Hugging Face, LoRA and instruction tuning
**Data engineering:** Python, SQL, Apache Spark, Databricks, Azure Data Factory, ETL pipelines, MongoDB Atlas Vector Search, FAISS
**Tools:** FastAPI, Docker, GitHub Actions, GCP Cloud Run, Power BI, Tableau

## Hi, I'm Luke

AI Test Engineer at the USDA, building toward a biotech-first AI/ML specialist career — competitive across applied AI/ML engineering, solutions engineering, technical sales, and independent building for biotech teams.

I'm spending the next 12 months — 30 to 60 minutes a day, public from day one on GitHub — learning to build production-grade biotech AI systems end to end. Modern tooling, agentic workflows, model adaptation, paper reproductions.

### What I'm working toward

A portfolio that supports the statement: *"I build and evaluate biotech AI systems. I can ship production-grade tools, prototype customer-facing solutions, train and fine-tune domain models, reproduce research, and communicate tradeoffs to both technical and commercial audiences."*

### What I'm building

Currently in **Phase 0** of a four-phase, 12-month arc:

- **[fabrica](https://github.com/elukemarshall/fabrica)** — Modern Python project template. The forge every subsequent project descends from. *Shipped.*
- *Phase 1:* **`pubmed-digest`** — Multi-model PubMed summarization CLI for biotech research workflows.
- *Phase 1:* **`mcp-bioinformatics`** — MCP server wrapping a tight cluster of biomedical APIs (UniProt, OpenTargets, ClinVar, Ensembl).
- *Phase 2:* **`biomed-scout`** — Biomedical research agent with retrieval, citations, multi-model routing, and a real evaluation harness.
- *Phase 2:* **`evidence-ops-copilot`** — Narrow biotech workflow product (literature triage / target briefing / trial landscape) shipped with demo and one-page solution brief.
- *Phase 3:* **`nanogpt-biomed`** — Small transformer trained from scratch on a biomedical corpus. Tightly scoped; the project that teaches what no API call can.
- *Phase 3:* **`biomed-reranker`** — Trained retrieval/reranking component that measurably improves `biomed-scout`.
- *Phase 3:* **Domain fine-tune** — LoRA/QLoRA fine-tune of an open-weight biomedical model (BioMistral / Meditron / MedGemma) on a narrow task, benchmarked against both base and a frontier general model.
- *Phase 4:* **Paper reproduction** — Reproduce a tractable biotech or biomedical-AI paper end to end, with a dense reproduction report.
- *Phase 4:* **Applied biotech capstone** — Original, narrow project tying engineering, ML, and solutioning together.

### Stack

Python 3.12 · \`uv\` · \`ruff\` · \`pyright\` · \`pytest\` · \`pre-commit\` · GitHub Actions · MCP · LiteLLM · Pydantic AI · HuggingFace \`transformers\`/\`peft\`/\`trl\`/\`accelerate\` · PyTorch · LoRA/QLoRA · \`sentence-transformers\` · vector DBs (\`chroma\`/\`qdrant\`) · structured logging

**Multi-model by design.** Claude Sonnet/Opus 4.6 as daily driver. GPT-5.4, Gemini 3.1 Pro, and Kimi K2.6 (open-source frontier) evaluated per task. Biomedical specialists (BioMistral, Meditron, MedGemma) for domain work. Provider choice is a design decision, never a default.

### Principles

1. **Production-quality from day one.** Tests, types, lint, CI on every project, no exceptions.
2. **Biotech first.** If a project could belong to anyone, the framing is too generic.
3. **Benchmarks over preferences.** Model choice is an engineering decision, justified per project.
4. **Communication is part of the skill.** Demos, briefs, and writeups for the work that earns them.
5. **Public from the first commit.** GitHub is the receipt. LinkedIn comes when there is substance to point at.

### Connect

Email: [elukemarshall@gmail.com](mailto:elukemarshall@gmail.com)

---

*Following a structured 12-month curriculum. Building in public. The work is the resume.*

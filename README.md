## Hi, I'm Luke

Software Development Engineer in Test at TSPi (an Abt Global company), working
on USDA federal delivery — I build automated test systems for regulated
software and ship agentic AI tooling inside a federal engineering org. I'm
pointing that combination at biotech.

The claim this portfolio backs:

> I build and evaluate AI systems to production discipline — tests, types, CI,
> benchmarks, and clear tradeoff writeups — in domains where correctness is
> regulated.

### Track record

- Sole owner of a federal compliance test lane: 300+ automated UI/API/SQL
  tests in Azure DevOps, ~40% personally authored, sustained 100% automation
  pass rate and ≥80% coverage sprint over sprint.
- Selected for USDA's GitHub Copilot pilot (~500 engineers); built multi-agent
  work-delineation tooling that was adopted across the pilot and demoed it to
  the full engineering org.
- Serve on the pilot-transition committee (8 USDA agencies) and its agentic
  builders subcommittee — defining department-wide repo standards for
  agent-based development (agent instruction files, security review
  procedures, common-use structures).
- Delivered a company-wide technical demo (200–300 attendees) on AI-assisted
  QA workflows.

### Now

- **[`pubmed-digest`](https://github.com/elukemarshall/pubmed-digest)** — a
  PubMed literature triage CLI for biotech research workflows. Schemas,
  config, CI, and eval fixtures are in place; retrieval, ranking, and live
  model wiring land next. V1 compares multiple LLM backends on quality,
  latency, cost, and citation discipline.
- **[`fabrica`](https://github.com/elukemarshall/fabrica)** — the Python
  AI/ML project template my portfolio projects inherit from (`uv`, `ruff`,
  strict `pyright`, `pytest`, pre-commit, GitHub Actions, ADRs, eval
  scaffold). Shipped and in use.

### Next

One project at a time, shipped before the next starts:

- `pubmed-digest` v1 with reproducible multi-model benchmarks.
- A fail-closed data-classification router: sensitive workloads route to
  local models only, and refuse rather than fail open — the routing
  discipline regulated AI deployment actually needs.

### Stack

Working daily: Python 3.12, `uv`, `ruff`, `pyright`, `pytest`, pre-commit,
GitHub Actions, Pydantic, Selenium/C#/.NET, Azure DevOps, structured logging,
reproducible eval harnesses. Building with: LiteLLM, MCP, local model serving
(Ollama), vector retrieval.

**Multi-model by design.** Provider choice is a benchmarked engineering
decision, not a default. Projects compare frontier APIs, cheaper baselines,
and open-weight options when the task justifies it.

### Principles

1. **Production-quality from day one.** Tests, types, lint, and CI are part of
   the work, not cleanup at the end.
2. **Regulated first.** I build for environments where correctness is audited,
   not assumed.
3. **Benchmarks over preferences.** Model choice has to be defended with
   evidence.
4. **Communication is part of the skill.** Good demos, briefs, and writeups
   make the work legible.
5. **The work is the resume.** Public artifacts should show taste, judgment,
   and follow-through.

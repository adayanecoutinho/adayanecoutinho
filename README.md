# Adayane Coutinho

**AI Engineer** in Brazil, open to remote AI Engineer and Forward Deployed Engineer roles.

I build practical LLM applications: MCP servers, RAG, agents, and data pipelines. My background is Java and Python backends, and I run self-hosted infrastructure.

## Now

AI Engineering MBA. I am also building a personal knowledge MCP server (Personal Brain) and open-finance tooling.

## Selected work

### [Grounded answers from a PDF](https://github.com/adayanecoutinho/desafio-mba-langchain)

**Problem.** Questions about a PDF should be answered from the file.

**Built.** A Python pipeline that loads the PDF, splits it into overlapping chunks, embeds them with Gemini, and stores the vectors in PostgreSQL with pgvector. Docker Compose runs the database. A CLI chat retrieves the nearest chunks, and the prompt tells the model to use only that text.

**Stack.** Python, LangChain, Gemini, PostgreSQL, pgvector, Docker

### [Prompt pull, rewrite, and evaluation](https://github.com/adayanecoutinho/mba-ia-pull-evaluation-prompt)

**Problem.** A short prompt turned bug reports into user stories with no persona, no examples, and no fixed shape.

**Built.** Scripts pull the prompt from the LangSmith Hub and push a public rewrite. The new prompt sets a senior product-manager role, three worked examples, and a reasoning checklist the model is told not to print. LangSmith scores helpfulness, correctness, F1, clarity, and precision. Pytest checks the prompt structure.

**Stack.** Python, LangChain, LangSmith, pytest

### [Audit-and-refactor skill for legacy APIs](https://github.com/adayanecoutinho/mba-ia-refactor-projects-skill)

**Problem.** Three legacy APIs needed a structural pass: a Flask store, an Express checkout API, and a Flask task manager.

**Built.** `refactor-arch`, a Claude Code skill. It detects the language and framework, writes an audit, and waits for confirmation before editing. The refactor moves each app into config, models, routes, controllers, and a shared error handler. This repo includes the skill, the three refactored apps, and the audit reports.

**Stack.** Python, Flask, Node.js, Express, Claude Code

### [adayanecoutinho.com](https://github.com/adayanecoutinho/adayanecoutinho.com)

**Problem.** Hiring teams need a bilingual site that can be hosted as static files.

**Built.** A Next.js app (App Router, TypeScript, Tailwind CSS, shadcn/ui) exported to static files and served on Cloudflare Pages. The root path redirects to `/en`. Each locale sets a canonical URL and `hreflang` alternates. Live at [adayanecoutinho.com](https://adayanecoutinho.com).

**Stack.** Next.js, React, TypeScript, Tailwind CSS, Cloudflare Pages

## Coming soon

Personal Brain MCP, OpenMonetis + Open Finance, and Treino Evolução. Private for now.

## Stack

| Area | Tools |
| --- | --- |
| Languages | Python, Java, TypeScript |
| LLM applications | LangChain, LangSmith, MCP, RAG |
| Data and runtime | PostgreSQL, pgvector, Docker |
| Web and hosting | Next.js, Flask, Node.js, Cloudflare |

## Contact

[adayanecoutinho.com](https://adayanecoutinho.com) · [LinkedIn](https://www.linkedin.com/in/naihara-lucas-b8a098424/) · [hello@adayanecoutinho.com](mailto:hello@adayanecoutinho.com)

---

Engenheira de IA no Brasil, aberta a times remotos.

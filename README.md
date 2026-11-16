# Awesome-Generative-AI-Contract-Suite

# Top Generative AI Contract Suite Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on AI-Powered Contract Drafting, Review & Self-Hosted Legal Reasoning*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Generative AI Contract Suites**. These tools help legal teams draft, review, negotiate, and analyze contracts using large language models—covering everything from enterprise AI copilots grounded in contract portfolios to open-source agents that keep your agreements entirely on your own infrastructure.

**Examples** include Icertis Vera AI, Ironclad AI, Harvey AI, Luminance, Spellbook, Robin AI, and open-source alternatives like draftLegal and Hermes Legal Advisor (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted contract AI, open-source legal agents, and community-driven redlining—ideal for organizations seeking data sovereignty and avoiding six-figure enterprise licensing. The open-source landscape has matured to genuine viability: **draftLegal** positions itself as the open-source Ironclad + Harvey combination , and **Hermes Legal Advisor** provides a CLI and web dashboard for contract analysis with inline Word redlines .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Icertis Vera AI Suite](https://www.icertis.com/)** | **Enterprise contract AI trained on millions of agreements.** Vera powers agents that draft, redline, negotiate, and analyze portfolios within boundaries you set. Copilot turns 100–150 page agreements into executive summaries so reviewers focus on material issues. Rated leading CLM vendor by MGI Research three consecutive years. | Quote-only (enterprise CLM contract; no public pricing) | No free tier; demo via sales |
| **[Harvey AI](https://www.harvey.ai/)** | **The enterprise legal AI benchmark.** Agents execute complex legal work end-to-end—contract analysis, due diligence, drafting, research—splitting tasks across parallel agents and returning cited, review-ready output. **200,000+ professionals at 3,500+ firms** including Dentons, KKR, PwC, and P&G. Raised **$550M at $15.5B valuation** (Sept 2026). | Quote-only (**~$1,000/seat/month** reported; annual contracts only) | **No self-serve trial**; enterprise sales only |
| **[Luminance](https://www.luminance.com/)** | **Legal-Grade AI with conversational assistant Lumi.** Analyzes up to 20 documents in one conversation, compares drafts to precedents, checks clauses against verified external legal sources, and generates downloadable reports. Treats document families (amendments, side letters) as a single evolving relationship. Every insight has source-level citations. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[Robin AI](https://www.robinai.com/)** | AI legal assistant with contract review capabilities. Uses Claude models with legal-specific fine-tuning. Positioned for in-house legal teams. | Quote-only (per-seat or enterprise) | Free trial available via sales |
| **[Spellbook](https://www.spellbook.legal/)** | AI contract drafting and review assistant built on GPT-4/Claude. Suggests redlines and clause language within Microsoft Word. **Closest alternative to Harvey for teams wanting to compare** (~$360/mo billed annually). | Quote-only (per-seat) | Free trial available |
| **[Casetext CoCounsel](https://casetext.com/)** | AI legal assistant (acquired by Thomson Reuters) with contract analysis. Uses GPT-4 with legal-specific prompting. **~$360/month billed annually**—a direct alternative to Harvey at lower entry. | **~$360/month** (billed annually) | No free tier; demo via sales |
| **[Ironclad AI](https://ironcladapp.com/)** | CLM platform with AI-assisted review and drafting. Positioned for teams wanting execution (approvals, signatures) alongside AI assistance. | Quote-only (per-user subscription) | No free tier; demo via sales |
| **[Lexion AI](https://www.lexion.ai/)** | AI contract management (acquired by Docusign for ~$165M) focused on obligation tracking and spend visibility. Automatically tags contracts, tracks renewals and termination notice deadlines. | Quote-only (enterprise contract) | No free trial; sales-led onboarding |
| **[Evisort AI](https://www.evisort.com/)** | Contract intelligence with 120+ pre-built AI models for clause identification, risk flagging, and term extraction. Customers can refine models with feedback—no coding required. | $30,000–$60,000/year (small teams); $60,000–$120,000/year (mid-market) | Free trial available; self-serve signup |
| **[ContractPodAi Leah](https://contractpodai.com/)** | AI-powered legal platform covering contract management, review/analysis, and legal project management. Role-based access with annual access reviews. | Quote-only (enterprise contract) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[draftLegal](https://github.com/AniketTati/draft-legal)** | [![Stars](https://img.shields.io/github/stars/AniketTati/draft-legal?style=social&color=white)](https://github.com/AniketTati/draft-legal/stargazers) | **The most ambitious open-source contract suite—positioned as Ironclad + Harvey combined.** **Self-hosted via `docker compose up`—contracts never touch third-party SaaS**. **~30 agent tools** over your contracts: search, cite, compare, draft, redline, route approvals—every write proposed on a confirm card first, most undoable. **Portfolio intelligence via hybrid retrieval (pgvector + Elasticsearch + RRF fusion)** answers questions like "A vendor quoted us $200k for an 8-week SOW. How does that compare with the SOWs we've signed?" with citations to clause and section. **Redline negotiation** with conservative/moderate/aggressive counter-proposals. **Full lifecycle**: approval workflows, e-signature, obligation tracking. **Bring-your-own model** (Anthropic, OpenAI, Gemini). **Best for teams wanting Harvey-class reasoning plus Ironclad-class execution** without six-figure SaaS fees. |
| **[Hermes Legal Advisor](https://pypi.org/project/hermes-legal-advisor/)** | [![Stars](https://img.shields.io/github/stars/Lethe044/hermes-legal?style=social&color=white)](https://github.com/Lethe044/hermes-legal/stargazers) | **The most feature-complete open-source contract analysis CLI with inline Word redlines.** **Offline scanner always works—no API key required**. **LLM providers optional**: Groq (free tier), Gemini (generous free tier), OpenRouter, or Ollama (fully local). **True inline redlines**: `--redline-inline` inserts each suggestion as a real Word Tracked Change directly into a copy of your original document—open in Word and it shows in the Review pane exactly like a human editor's tracked edit. **Batch mode** produces CSV + visual HTML dashboard + per-file reports. **Portfolio dashboard** with risk distribution and per-counterparty breakdown. **Best for teams wanting a scriptable, privacy-first contract analyzer** with real Word integration. |
| **[Paparusi legal-ai-agent](https://github.com/Paparusi/legal-ai-agent)** | [![Stars](https://img.shields.io/github/stars/Paparusi/legal-ai-agent?style=social&color=white)](https://github.com/Paparusi/legal-ai-agent/stargazers) | **The most localized open-source contract review agent—built for Vietnamese law.** **10 risk categories analyzed**: one-sided clauses, excessive penalties (>8% per Vietnamese law), unreasonable deadlines, missing protective clauses, law contradictions, auto-renewal traps, liability limitations, IP/confidentiality issues, dispute resolution, and force majeure. **Vietnamese law compliance check** against Civil Code, Commercial Law, and Labor Law with specific article citations. **8+ contract templates** (employment, lease, sale, service, NDA, loan, agency, business cooperation). **API**: `POST /v1/contracts/{id}/review-ai` returns risk score, level, clause-by-clause analysis, and revision suggestions. **Best for teams operating under Vietnamese jurisdiction** or wanting a reference implementation for jurisdiction-specific contract AI. |
| **[claude-for-legal-ZH](https://github.com/anthropics/claude-for-legal-ZH)** | — | **The most comprehensive open-source legal AI agent framework for Chinese law.** **12 specialized agents** covering commercial contracts, corporate M&A, privacy/data, product compliance, employment, AI governance, regulatory compliance, IP, litigation, legal clinic, law student training, and community skills. **Full Chinese legal localization**: UCC → Civil Code, GDPR → PIPL/DSL/CSL, FLSA → Labor Contract Law, FRCP → Civil Procedure Law. Tools: Westlaw → Yuandian and PKULaw. **Runs as Claude Code plugin or via Claude Managed Agents API**. **Best for Chinese legal teams** wanting a comprehensive agent framework grounded in PRC law. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Agentic Contract Review Workflow (Dapr + Claude)](https://github.com/dapr/quickstarts/blob/main/AI/workflows/external_system_interaction/anthropic/README.md)** | — | **Reference architecture for durable, agentic contract review.** Dapr Workflows orchestrate the process: Claude reviews each contract and identifies risky clauses, drafts amendments if high risk, then pauses for human approval with timeout and persistence. **Durability survives restarts and crashes**; event waiting pauses for human input. Output includes risk score, risky clauses, and structured report. **Best as a blueprint** for teams wanting to build resilient contract review workflows with human-in-the-loop approval. |
| **[legal-redline-tools](https://github.com/topics/legal-redline)** | — | **Generates tracked-changes Word docs and redline PDFs from AI contract reviews**—the same deliverables lawyers actually send. **Best as a building block** for teams assembling their own contract AI pipeline. |

**Frameworks for building custom systems**: Choose **draftLegal** for a full-lifecycle self-hosted CLM with portfolio reasoning and cited answers, **Hermes Legal Advisor** for a scriptable CLI analyzer with real Word tracked-changes redlines, or **Paparusi legal-ai-agent** if you operate under Vietnamese law or want a jurisdiction-localization reference. For durable, human-in-the-loop review workflows, use the **Dapr + Claude quickstart** as an architecture blueprint.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Contract AI suites process legally privileged and sensitive documents; **data residency is critical**—self-hosted open-source tools keep contracts on your infrastructure, while SaaS platforms require sending documents to third-party APIs. Enforce strict access controls and **always require qualified legal review** before relying on AI output.
- **Enterprise contract AI pricing is genuinely six-figure territory.** **Harvey runs ~$1,000/seat/month** on annual contracts with **no self-serve trial**—a 50-lawyer team pays **~$600,000/year**. **Icertis is quote-only** with market ranges of **$30K–$75K/year for startups** and **$176K+ for large enterprises**, before AI transaction charges and implementation. **Spellbook and CoCounsel offer lower entry points (~$360/month)** for teams wanting to compare before committing to enterprise contracts. **Open-source contract AI has matured to genuine viability**: draftLegal combines Ironclad-style execution with Harvey-style reasoning, Hermes provides real Word tracked-changes with zero required API costs (offline scanner), and Paparusi offers deep Vietnamese law localization. **Validate whether you need enterprise-grade SaaS (Harvey, Icertis), a lower-cost commercial assistant (Spellbook, CoCounsel), or a self-hosted open-source suite (draftLegal, Hermes)** before committing.

---

**Made for legal engineers, contract AI researchers, and organizations building private legal AI infrastructure.**  
Let's make generative AI contract suites more open, grounded, and legally sound.

<div align="center">

# Mubeen Saher

**Software Engineer · AI/NLP · Civic Tech · ERP Architecture**

Final Year SE @ University of Sargodha · Graduating June 2026
Targeting AI/ML MSc in Germany — October 2026

[![Email](https://img.shields.io/badge/mubeensahar07@gmail.com-grey?style=flat-square&logo=gmail)](mailto:mubeensahar07@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mubeen-saher)
[![Portfolio](https://img.shields.io/badge/Portfolio-222?style=flat-square&logo=safari&logoColor=white)](https://sahar-portfolio.mubeensahar07.workers.dev)

</div>

---

## About

I build systems at the intersection of AI safety, civic transparency, and developer tooling. Close to three years of professional experience across NLP pipelines, ERP architecture, and full-stack development. Currently leading a team of interns building a white-label SaaS ERP platform on Frappe v16.

---

## Projects

### TruthLens — AI Integrity Chrome Extension
*Final Year Project · Submission-ready · Private until June 2026*

Real-time AI safety layer that intercepts LLM responses on ChatGPT, Claude, and Gemini and runs three-signal adversarial analysis directly inside the chat UI.

```
LLM Response (streaming)
  └─ Phase 1: Rule-based — claim extraction, regex manipulation detection, fact grounding
  └─ Phase 2: NLI — DeBERTa-v3 hallucination scoring, BART-large bias/manipulation classification
  └─ Output:  { hallucination: 94%, manipulation: 12%, bias: 8% } + evidence overlay
```

`DeBERTa-v3` `BART-large-MNLI` `Zero-shot NLI` `Chrome Extension API` `HuggingFace`

No backend. No latency penalty. Runs on every AI response automatically.

---

### PaperTrail — Civic Transparency Platform
*Live · [papertraill.netlify.app](https://papertraill.netlify.app)*

Documents the gap between official Punjab government service claims and real citizen experiences. Produces a Reality Gap Score (1–9) per institution across time, cost, complexity, and reliability dimensions. Currently covers 8 cities, 35 institutions.

```
Reddit (live scraper) + Official sources
  └─ FastAPI pipeline → Gap scoring → Supabase → Upstash Redis
  └─ React / Vite frontend → Netlify
  └─ NLP clustering on HuggingFace Spaces (Docker)
```

`FastAPI` `React` `PostgreSQL` `Redis` `Supabase` `HuggingFace` `Docker` `Netlify`

Roadmap: Lahore pilot → Pakistan-wide → Global

---

### CodeDissect — VS Code Extension
*Active · Portfolio Project*

AI-powered code review inside your editor. Severity-tiered analysis with gutter decorations, hover diagnostics, git diff mode, and exportable session reports.

```
Severity tiers:  Critical → Architectural → Performance → Style
Dissect's Take:  Decision cost/benefit analysis per issue
Git diff mode:   Reviews only changed code
```

`TypeScript` `VS Code Extension API` `FastAPI` `Groq API` `Tree-sitter AST`

---
### Lore — Organisational Memory Tool

Indexes Slack messages and Jira tickets into a vector database. Plain-English queries return the exact source, author, and timestamp. Built the Slack event listener, scheduled Jira sync, and vector similarity pipeline end-to-end.

`Python` `FastAPI` `Slack Bolt` `Jira REST API` `sentence-transformers` `Supabase pgvector` `React` `Railway`

### White-Label SaaS ERP
*Active · Esthetics Solutions*

Multi-tenant ERP platform on Frappe v16 + ERPNext. Separate PostgreSQL schema per tenant, custom middleware app as API gateway, Redis as cache and event bus, CSS variable white-labelling with zero upstream forks.

`Frappe v16` `ERPNext` `PostgreSQL` `Redis` `Docker` `Azure`

---

## Stack

**AI / NLP**
`Python` `PyTorch` `HuggingFace Transformers` `DeBERTa` `BART` `NLI` `spaCy`

**Backend / Systems**
`FastAPI` `Docker` `Redis` `PostgreSQL` `Supabase` `Frappe` `ERPNext`

**Frontend / Extensions**
`React` `TypeScript` `JavaScript` `Vite` `Chrome Extension API (MV3)`

---



<div align="center">
<sub>Open to AI/ML research roles, grad opportunities, and interesting problems · mubeensahar07@gmail.com</sub>
</div>

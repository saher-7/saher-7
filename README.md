<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║      S A H E R                                               ║
║      AI/ML · Builder · Final Year SE                         ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=800&color=C9A84C&center=true&vCenter=true&width=600&lines=AI+Safety+%26+NLP+Systems;Civic+Tech+%26+Developer+Tooling;Frappe+%2F+ERPNext+Architecture;Shipping+things+that+actually+matter.)](https://git.io/typing-svg)

</div>

---

## `whoami`

```python
saher = {
    "role"        : "Final Year Software Engineering Student → AI/ML (Germany, Oct 2026)",
    "location"    : "Lahore, Pakistan · Open to Remote",
    "graduating"  : "June 2026",
    "focus"       : ["AI Safety", "Real-time NLP", "Civic Tech", "ERP Infrastructure"],
    "flagship"    : "TruthLens — real-time AI integrity layer running on ChatGPT, Claude & Gemini",
    "also"        : ["PaperTrail — civic gap analysis, live in Lahore",
                     "CodeDissect — VS Code extension for AI-powered code review",
                     "Frappe/ERPNext — white-label multi-tenant SaaS architecture"],
}
```

> *I build things that solve real problems — AI safety infrastructure, civic transparency tools, and developer tooling that ships.*

---

## 🛡️ TruthLens *(Final Year Project — Private until June 2026)*

> **Real-time AI Integrity Chrome Extension** — live on ChatGPT, Claude & Gemini

A three-signal AI safety layer that intercepts every LLM response and runs adversarial analysis in real time — directly inside the chat UI.

```
Input: LLM Response (streaming)
         ↓
┌─────────────────────────────────────────────────────┐
│  Phase 1 — Instant Rule-based Analysis              │
│  · Claim extraction (NER + dependency parsing)      │
│  · Regex manipulation & bias pattern matching       │
│  · Wikipedia + DuckDuckGo fact grounding            │
└──────────────────────┬──────────────────────────────┘
                       ↓
┌─────────────────────────────────────────────────────┐
│  Phase 2 — NLI Upgrade (async)                      │
│  · DeBERTa-v3 cross-encoder NLI (hallucination)     │
│  · BART-large zero-shot classification              │
│    (manipulation + bias, condensed assertions)      │
│  · Rule-based secondary interpretability layer      │
└──────────────────────┬──────────────────────────────┘
                       ↓
Output: { hallucination: 94%, manipulation: 12%, bias: 8% }
        + evidence + explanation — overlaid in chat UI
```

**Stack:** `DeBERTa-v3` `BART-large-MNLI` `Zero-shot Classification` `NLI` `Chrome Extension API` `JavaScript` `HuggingFace Inference API` `Wikipedia API`

**What makes it different:** Most hallucination detectors are offline eval tools. TruthLens is a live, in-browser safety layer. No backend. No latency penalty. Zero setup. Just install and it runs on every AI response automatically.

---

## 🗺️ PaperTrail *(Live — [papertraill.netlify.app](https://papertraill.netlify.app))*

> **Civic Transparency Tool** — exposing the gap between official claims and documented reality

Compares official government/institutional data against scraped public discourse for 6 Lahore institutions, producing a **Reality Gap Score (1–9 scale)** per institution.

```
Data Sources: Reddit scraper (live) · Official institution pages
Pipeline:     Parallel fetch → Gap scoring → Supabase → Upstash Redis cache
Frontend:     Vite / React → Netlify
Backend:      FastAPI → HuggingFace Spaces (Docker)
```

**Stack:** `FastAPI` `React` `Vite` `Supabase` `Upstash Redis` `Netlify` `HuggingFace Spaces`

**Roadmap:** Lahore pilot → Pakistan-wide → Global

---

## 🔍 CodeDissect *(VS Code Extension)*

> **AI-Powered Code Review** — severity-tiered analysis inside your editor

Runs LLM-backed code review directly in VS Code with gutter decorations, hover diagnostics, and git diff mode.

```
Review Output:
  · Severity tiers     — Critical / Architectural / Performance / Style
  · Ghost's Take       — architectural cost/benefit analysis
  · Review Quality     — Poor / Average / Good / Great / Excellent
  · Git diff mode      — reviews only what changed
  · Session history    — exportable markdown reports
```

**Stack:** `TypeScript` `VS Code Extension API` `FastAPI` `HuggingFace Inference API`

---

## ⚙️ Frappe / ERPNext — White-Label SaaS Architecture *(Active)*

> **Multi-tenant ERP platform** built on Frappe v16 + ERPNext

Architecting a white-label SaaS ERP with full multi-tenancy, custom middleware, and a zero-fork customisation policy.

```
Key decisions:
  · Multi-tenancy      — separate PostgreSQL schema per tenant
  · Middleware         — custom Frappe app as API gateway layer
  · Cache / Events     — Redis as both cache and Event Bus
  · White-labelling    — template shadowing, zero upstream forks
  · Team structure     — 4 intern squads: infra, DB, branding/gateway, testing
```

**Stack:** `Frappe v16` `ERPNext` `PostgreSQL` `Redis` `Docker`

---

## 🧠 Technical Stack

**AI & NLP**

![Python](https://img.shields.io/badge/Python-C9A84C?style=flat-square&logo=python&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-C9A84C?style=flat-square&logo=pytorch&logoColor=black)
![HuggingFace](https://img.shields.io/badge/HuggingFace-C9A84C?style=flat-square&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-C9A84C?style=flat-square&logoColor=black)

**Systems & Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-7A9E8B?style=flat-square&logo=fastapi&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-7A9E8B?style=flat-square&logo=docker&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-7A9E8B?style=flat-square&logo=redis&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-7A9E8B?style=flat-square&logo=postgresql&logoColor=black)
![Frappe](https://img.shields.io/badge/Frappe-7A9E8B?style=flat-square&logoColor=black)

**Frontend & Dev**

![React](https://img.shields.io/badge/React-5B8DD9?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5B8DD9?style=flat-square&logo=typescript&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-5B8DD9?style=flat-square&logo=javascript&logoColor=black)
![Chrome Extensions](https://img.shields.io/badge/Chrome_Extensions-5B8DD9?style=flat-square&logo=googlechrome&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-5B8DD9?style=flat-square&logo=linux&logoColor=black)

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=saher-7&show_icons=true&theme=transparent&hide_border=true&title_color=C9A84C&icon_color=C9A84C&text_color=F0EBE1&bg_color=080910" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saher-7&layout=compact&theme=transparent&hide_border=true&title_color=C9A84C&text_color=F0EBE1&bg_color=080910" />

</div>

---

## 📬 Let's Talk

<div align="center">

[![Email](https://img.shields.io/badge/Email-mubeensahar07@gmail.com-C9A84C?style=flat-square&logo=gmail&logoColor=white)](mailto:mubeensahar07@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saher-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mubeensahar)
[![Portfolio](https://img.shields.io/badge/Portfolio-mubeensahar.dev-7A9E8B?style=flat-square&logo=safari&logoColor=white)](https://mubeensahar.dev)

</div>

---

<div align="center">
<sub>Graduating June 2026 · Targeting AI/ML MSc in Germany · Open to opportunities</sub>
</div>

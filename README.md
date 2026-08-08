# Isaque Vergueiro

**Full-Stack Developer** — React, Next.js, TypeScript, NestJS, Python.
I build corporate systems and put AI agents to work inside real business processes.

Currently a development intern at **AIONS** (Manaus, AM), where I've shipped a whistleblower channel with TOTP + facial validation, a medical-report platform with digital signature, and an EPI lifecycle tracker — plus the n8n automations that connect them to the company's HR system.

---

### What I'm working on

| Project | What it is | Stack |
|---|---|---|
| **[SisVac 2.0](https://github.com/SecVergueiro/sisvac-cecon)** | Vacation & leave management for the public sector, implementing Amazonas State Law 1.762. Hierarchical RBAC, native PDF, daily-reset live demo. | Next.js · NestJS · Supabase · Turborepo · GitHub Actions |
| **[TranskriptorSec](https://github.com/SecVergueiro/transkriptorsec)** | Whisper transcription running **inside the browser** via WebGPU — audio never leaves the user's machine, zero API cost. | Next.js · WebGPU · Web Workers · Prisma |
| **[Queimadas AM](https://github.com/SecVergueiro/queimadas-am-sec)** | Wildfire hotspot dashboard on INPE open data. No back-end, no API key — the hard part is the data, which arrives dirty and changes without notice. | Angular 22 · Signals · Zoneless · Vitest |
| **[FitSec](https://github.com/SecVergueiro/fitsec)** | Offline-first workout PWA: optimistic writes, sync queue, and rest timers handed off to the iPhone's native timer. | Next.js · Supabase · IndexedDB · Service Worker |

Every one of them is deployed and clickable. I'd rather you open the demo than read my CV.

---

### How I work

I document decisions, not just code — each README has a section on what I chose, what I rejected, and why. When something doesn't work, it goes in the README as a limitation instead of being sold as a feature: TranskriptorSec's speaker diarization scored 57.2% against a 50% baseline, and it says so.

The parsers and sync queues are tested — 108 tests in FitSec, 23 in the Queimadas parser, including one that fails on purpose if INPE changes its CSV header.

---

### Stack

- **Front-end** — React · Next.js · Angular · TypeScript · TailwindCSS · Vite
- **Back-end** — NestJS · Node.js · Python · Django · REST APIs
- **Data** — PostgreSQL · Supabase · Prisma
- **AI & Automation** — LangChain · LangGraph · RAG · n8n · MCP · LLM orchestration
- **Ops** — GitHub Actions · Turborepo · Vercel · Vitest · Jest

---

📍 Manaus, Amazonas — open to remote

🔗 [Portfolio](https://vergueiroportfolio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/isaquevergueiro/) · secvergueiro@gmail.com

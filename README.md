# 🚀 Satish Vasikarla

**AI Product Engineer | SaaS Builder | Technical Entrepreneur**

I design and ship AI-native products end to end: knowledge systems (RAG), natural-language data interfaces, multi-agent workflows, and domain tools for finance, insurance, education and utilities. Based in India.

🌐 **Portfolio**: [vasikarlas-ai.vercel.app](https://vasikarlas-ai.vercel.app) · 📧 **Contact**: vasikarla.satish@outlook.com

---

## 🏆 Flagship Products

| Product | What it does | Built with | Links |
|---------|--------------|------------|-------|
| **CorePragyaAdvanced** | Personal AI knowledge base. Ingests URLs, PDFs, Gmail links and RSS feeds, scores new articles against your interest profile, surfaces trending themes, and turns saved material into flashcards, concept maps and Q&A. Research, tech-research and content agents write their output back into the knowledge base. | Next.js 15, Supabase + pgvector, Claude / OpenAI / Groq (switchable), Cohere embeddings, Vitest + Playwright (~400 tests) | [Live](https://core-pragya-advanced.vercel.app) · [Code](https://github.com/svasikarla/CorePragyaAdvanced) |
| **SkillPilot** | Freelance AI/ML job hub. Pulls jobs from nine boards daily, scores each for scam risk and personal fit, and uses Claude to draft platform-specific proposals, interview prep and profile audits. Includes an application tracker and a skill-gap roadmap. | Next.js 16, Supabase (RLS, pgvector), Claude API, local MiniLM embeddings, Vitest (254 tests) | [Live](https://skillpilot-mauve.vercel.app) · [Code](https://github.com/svasikarla/SkillPilot) |
| **StockAnalyst** | Forensic screening for Indian equities. Ingests NSE filings and prices, computes a YAML-defined registry of metrics and red-flag gates (Beneish, Piotroski, Altman), and runs a reverse DCF. Deliberately gives no buy/sell calls. | Python 3.12, FastAPI, SQLAlchemy, Postgres, Next.js 16, pytest (241 tests) | [Live](https://stockanalyst-xi.vercel.app) · [Code](https://github.com/svasikarla/StockAnalyst) |
| **ArthVault** | Local-first personal finance ledger for Android. Rebuilds your financial record from bank SMS on the device, with spending insights and plain-language queries. The app declares no internet permission, and a build test enforces that. | Kotlin, Jetpack Compose, Room, encrypted storage, biometric unlock | [Code](https://github.com/svasikarla/ArthVault) |
| **ConceptForge** | Adaptive learning platform for IIT JEE. A four-factor mastery model drives learning-path generation, adaptive difficulty, AI hints and solutions, and score prediction, with separate student and teacher views. | Next.js, Supabase, LLM APIs | [Live](https://concept-forge-iota.vercel.app) · private repo |
| **NLSQLPro** | Natural language to SQL for PostgreSQL, MySQL, SQLite and SQL Server, with schema caching, a business glossary, and prompt-injection defences. | Next.js, Supabase, Claude | [Live](https://nlsql-pro.vercel.app) · private repo |

---

## 🧠 AI & Knowledge Systems

- **[CorePragyaAdvanced](https://github.com/svasikarla/CorePragyaAdvanced)** — RAG knowledge base with multi-agent research, RSS interest scoring, trending insights, learning tools and a 2D/3D knowledge graph
- **[CorePragya](https://github.com/svasikarla/CorePragya)** — the first version: URL and Gmail capture, summaries, embeddings and a personal RAG chatbot
- **NLSQLPro** — natural language to SQL across four database engines
- **[LocalRAG](https://github.com/svasikarla/LocalRAG)** — fully local PDF question answering with LangChain, Chroma and Ollama
- **[WiseCache](https://github.com/svasikarla/WiseCache)** → **[wisecachepro](https://github.com/svasikarla/wisecachepro)** → **[1Pgwisecache](https://github.com/svasikarla/1Pgwisecache)** — three iterations of a link-saving knowledge cache that summarises and categorises pages, including capture by email
- **[Python](https://github.com/svasikarla/Python)** — Gradio chat UI for local Ollama models

## 💼 Careers & Markets

- **[SkillPilot](https://github.com/svasikarla/SkillPilot)** — job aggregation, scam scoring, semantic matching and Claude-written proposals for AI/ML freelancers
- **[StockAnalyst](https://github.com/svasikarla/StockAnalyst)** — point-in-time financial data, forensic metrics and reverse DCF for Indian stocks

## 💰 Finance & Insurance

- **[ArthVault](https://github.com/svasikarla/ArthVault)** — offline Android ledger built from bank SMS: recurring-charge and price-hike detection, own-account transfer handling, CSV export and encrypted backup
- **[BimaBuddyAdvanced](https://github.com/svasikarla/BimaBuddyAdvanced)** — Indian health-insurance comparison and education: plan finder, policy red flags and clause map, claim-rejection checks, and a voice advisor in 10 Indian languages. [Live](https://bima-buddy-advanced.vercel.app)
- **InsureAI (US Insurance Details)** — upload US health, dental, vision and life policies for OCR, red-flag detection and comparison. [Live](https://us-insurance-details.vercel.app)
- **Society Finance** — maintenance billing, numbered receipts, expenses, defaulter aging and audit trail for housing societies, with treasurer, committee and auditor roles
- **[SukritiHub](https://github.com/svasikarla/SukritiHub123-main)** — residential society operations: residents, visitors, guards, vendors, domestic-help attendance and bookkeeping
- **[health-insurance-india](https://github.com/svasikarla/health-insurance-india)** and **[bimabuddy](https://github.com/svasikarla/bimabuddy)** — the earlier versions that BimaBuddyAdvanced grew from

## 🌡️ Climate & Utilities

- **ThermoTwin AI** — pedestrian thermal-comfort simulator built for the FortyGuard Hackathon '26. Combines measured heat data, SOLWEIG physics and a fast surrogate model to show how albedo, trees, green roofs and building height change street-level heat stress. [Live](https://fortyguard-thermotwin.vercel.app) · [UI prototype](https://thermotwin.vercel.app)
- **AMI 2.0 Roadmap** — strategic framework for North American utilities moving from AMI 1.0 to AMI 2.0: comparison, five solution areas and a five-phase roadmap. [Live](https://ami-2-0-road-map.vercel.app)
- **[AI_RoadMap](https://github.com/svasikarla/AI_RoadMap)** — research briefing on Oracle AI for energy and water utilities, including NL2SQL and partner opportunities. [Live](https://ai-road-map-rho.vercel.app)

## 📚 Education

- **ConceptForge** — adaptive IIT JEE practice with mastery tracking and AI hints
- **[IGCSEStudentGuide](https://github.com/svasikarla/IGCSEStudentGuide)** — flashcards, quizzes and exam papers for IGCSE Grades 9–10, generated through a cost-tiered multi-provider LLM pipeline with a teacher review workflow. [Live](https://igcse-student-guide.vercel.app)

## 🪔 Culture & Heritage

- **[adishankaracharysite](https://github.com/svasikarla/adishankaracharysite)** — life, philosophy and eight translated works of Adi Shankaracharya, with interactive maps of his travels and mathas. [Live](https://adishankaracharysite.vercel.app)
- **Telugu Sahityam** — bilingual reader for Yogi Vemana and Sumathi Shatakam with Telugu text, translation, search and bookmarks. [Live](https://telugu-sahityam.vercel.app)
- **Gautama Buddha** — sourced biography with timeline, travels, key discourses and chanting. [Live](https://gauthama-buddha.vercel.app)

---

## 📊 At a Glance

- 🚀 **23** projects deployed on Vercel
- 💻 **18** public repositories, plus private product repos
- ✅ **~900** automated tests across CorePragyaAdvanced, SkillPilot and StockAnalyst
- 🧭 **7** domains: knowledge systems, careers, markets, personal finance, insurance, climate and utilities, education
- ⚡ TypeScript · Python · Kotlin

---

## 🛠️ Tech Stack

**Languages & Frameworks**
- TypeScript, React, Next.js (App Router)
- Python, FastAPI, SQLAlchemy
- Kotlin, Jetpack Compose, Room
- SQL (PostgreSQL)

**AI & LLMs**
- Claude API, OpenAI, Azure OpenAI, Gemini, Groq
- Local models with Ollama; local embeddings with transformers.js
- RAG with pgvector and Chroma, knowledge graphs, multi-agent pipelines with streaming
- Voice with ElevenLabs and Whisper

**Data & Infrastructure**
- Supabase (Postgres, Auth, row-level security, Edge Functions)
- Vercel (hosting, cron jobs), Render
- Vitest, Playwright, pytest

---

## 🎓 Areas of Expertise

| Domain | Focus | Projects |
|--------|-------|----------|
| **AI knowledge systems** | RAG, embeddings, agents, knowledge graphs | CorePragyaAdvanced, LocalRAG, WiseCache |
| **Natural-language data interfaces** | NL to SQL, schema grounding | NLSQLPro |
| **Applied LLM products** | Proposal writing, tutoring, content generation | SkillPilot, ConceptForge, IGCSEStudentGuide |
| **Financial analytics** | Forensic metrics, valuation, point-in-time data | StockAnalyst |
| **Mobile & privacy** | Offline-first Android, on-device parsing, encryption | ArthVault |
| **Insurance** | Policy comparison, document analysis, voice advice | BimaBuddyAdvanced, InsureAI |
| **Climate & utilities** | Urban heat simulation, AMI 2.0 strategy | ThermoTwin AI, AMI 2.0 Roadmap |

---

## 🤝 Open to Collaboration

- AI product development and RAG systems
- SaaS technical consulting
- Financial analytics and FinTech platforms
- EdTech and domain-specific AI tools
- Utilities and insurance technology strategy

📧 **Contact**: vasikarla.satish@outlook.com

---

*Last updated: November 2026 | Building tomorrow's AI products today*

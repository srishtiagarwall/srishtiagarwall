# Hi, I'm Srishti 👋

**Founding Engineer (Backend & AI Systems)** at [GrowthZ AI](https://growthz.ai)

I build backend systems for LLM-powered products and take them all the way to production: architecture, async pipelines, infra, and cost. For two years I've been shipping at an AI-native MarTech startup as the engineer who owns the whole thing end-to-end.

---

## What I've shipped at GrowthZ AI

- **Campaign automation engine:** REST APIs across 6 microservices (multi-tenant) that auto-generate keywords, ad groups, creatives, and extensions. Tuned the LightGBM model behind real-time bid optimization. **~70% less manual effort.**
- **LLM ad-copy pipeline:** scrapes store/website data, extracts sentiment and themes, and generates keyword-researched copy via RAG (Gemini embeddings + Google Search grounding). Static, animated, and AI-generated video creatives at **sub-60s latency**.
- **Video-to-Meta-ads pipeline:** ~1,000 uploads/day across 60+ ad accounts. Moved to direct-to-object-storage streaming, **cutting egress costs ~60%**.
- **Creative Suite:** built solo, end-to-end. **9 clients in 3 months**, opened a new monetization channel.
- **Google Ads audit service:** audits that took 3–4 hours now take **under 3 minutes** per account.
- **Infra:** AWS + Docker + Pulumi (IaC). **30% cost reduction** at 99% uptime.

---

## Featured projects

### 🛡️ [LLM Sentinel](https://llm-sentinel-dashboard.onrender.com/login): LLM observability & governance
Drop-in reverse proxy between any app and an LLM provider.
- Synchronous pre-call guardrails that stay off the client's latency path
- Async LLM-as-judge scoring (hallucination, toxicity, faithfulness) feeding a tamper-evident, hash-chained audit log, with EU AI Act Article 12-aligned reporting
- Provider fallback with per-provider circuit breakers: **p50 ~29ms / p95 ~46ms** gateway overhead under load
- `NestJS` `TypeScript` `Gemini` `Redis` `PostgreSQL` `SQS`

### 📞 [CallSense AI](https://callsense-ai-rqmp.onrender.com/): AI call-intelligence platform
- 3-provider transcription chain (Whisper, Smallest Pulse, Sarvam) with real speaker diarization (VAD + voice embeddings + clustering)
- Rubric-based LLM QA scoring with schema-validated structured outputs, sentiment analysis, and semantic search
- Live job status over SSE; every pipeline stage degrades gracefully when a provider is down
- `FastAPI` `Next.js` `Gemini` `WebRTC VAD`

---

### Tech I work with

- **Languages:** Python · TypeScript · JavaScript · SQL · C++
- **Backend:** NestJS · Node.js · Express · FastAPI · SQLAlchemy
- **AI/LLM:** LangChain · LangGraph · RAG · LLM-as-Judge · Gemini · Imagen · Veo
- **Cloud & infra:** AWS (S3, SQS, Lambda, EC2, API Gateway) · GCP (Cloud Run, Cloud SQL) · Cloudflare R2 · Docker · Pulumi
- **Data:** PostgreSQL · MongoDB · Redis · DuckDB

---

## Let's connect

📫 [agarwal11srishti@gmail.com](mailto:agarwal11srishti@gmail.com) · [LinkedIn](https://www.linkedin.com/in/srishtiagarwal-sde/) · [Portfolio](https://srishti.is-a.dev/) · [LeetCode](https://leetcode.com/u/SrishtiAgarwal/)

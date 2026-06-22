<!-- Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6366F1&height=150&section=header&text=Praveen%20Kumar&fontColor=ffffff&fontSize=44&desc=Software%20Engineer%20%C2%B7%20Co-founder%20and%20CTO%20%C2%B7%20Founding%20Engineer&descSize=17&descAlignY=64"/>

<p align="center">
  <a href="https://linkedin.com/in/mist-ic"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:mysticscholarate@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/mist-ic"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Based%20in-India-6366F1?style=flat-square"/>
</p>

---

### Summary

Software engineer who builds complete products from zero and ships them to real users fast. Co-founder and CTO of [Orchy](https://orchy.in), founding engineer at [Build with AI](https://truckingwithai.com), and the engineer who has shipped production systems handling 1M+ monthly requests. I build best for the people most software ignores: non-technical operators, the underserved, and the next billion users. 6 years with Python, 4+ years shipping production systems across B2B, consumer, and deep tech.

---

### Experience

#### [Build with AI](https://truckingwithai.com) &nbsp;·&nbsp; Founding Engineer
`2026 - Present` &nbsp;·&nbsp; *AI-first operations platform for the US trucking and construction industry. Live at [truckingwithai.com](https://truckingwithai.com).*

- Founding engineer building the product from zero: a multi-tenant platform with load dispatch, a real-time GPS pipeline powering live fleet maps and geofenced roll-call attendance, and an automated payroll and settlement engine that turns completed runs into pay and invoices.
- Built the AI layer that makes the product usable by people who have never used software: photograph a bill of lading and a vision model parses it into structured data, enter loads in plain language, and run workflows by voice instead of forms.
- Built an autonomous agent for broker queries: it resolves which load, the assigned driver, and live progress, then emails a clean status back on its own, replacing hours of manual calls and emails.
- Architected one codebase to serve multiple verticals (trucking and construction), shipping to real US fleets.

#### [Orchy](https://orchy.in) &nbsp;·&nbsp; Co-founder and CTO
`2026 - Present` &nbsp;·&nbsp; *AI-first social app that moves people from matching to meeting in real life. Live at [orchy.in](https://orchy.in).*

- Sole engineer and CTO: architected and shipped the entire stack solo, a cross-platform Flutter app, a Bun and Hono backend, and security-first infrastructure on GCP Cloud Run.
- Built a custom real-time chat system on Bun WebSockets with Redis pub/sub and server-enforced time limits, at zero per-message cost.
- Built matching on PostgreSQL with PostGIS for geospatial search and pgvector for vector similarity, behind WhatsApp OTP auth, JWT rotation, and multi-layer anti-abuse rate limiting.
- Ran keyless CI/CD with GitHub Actions and Workload Identity Federation (no stored secrets), private object storage with short-lived signed URLs, and 8+ integrations including face-liveness verification and split payments.

#### [Journalyst](https://journalyst.trade) &nbsp;·&nbsp; Lead Backend Developer
`2026` &nbsp;·&nbsp; *Compliance-ready trading journal for Indian traders (DPDP 2023, CERT-In, SEBI). Live at [journalyst.trade](https://journalyst.trade).*

- Owned backend architecture end to end: a Turborepo monorepo with type-safe tRPC APIs on Hono, PostgreSQL with TimescaleDB for high-volume time-series trade data, Drizzle ORM, and Redis.
- Designed the compliance data architecture to meet Indian data-protection and securities regulations.
- Built and led the backend team from scratch: ran 15+ technical interviews and onboarded and mentored 6 engineers shipping production fintech code.

#### MystWell &nbsp;·&nbsp; Co-founder
`2025` &nbsp;·&nbsp; *Voice-first health assistant. Shelved after market validation.*

- Co-founded and built a real-time voice pipeline (Azure STT, Gemini, speaker diarization) that records a doctor visit and auto-extracts diagnosis, medications, and follow-ups with no user input.
- Integrated the NIH RxNorm drug database and built a custom hallucination-detection layer to keep medical output safe.

#### Freelance Full-Stack and AI Engineer
`2022 - 2025`

- Shipped 5+ production systems for clients, handling 1M+ monthly requests at sub-100ms p95 latency, including a real-time price-comparison engine over 50K+ products with custom Elasticsearch analyzers and 99.5% uptime.

---

### Selected Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🕷️ [Arachne](https://github.com/mist-ic/Arachne)
**12-Service Autonomous Web Intelligence Platform**

Distributed AI system with self-healing agents, a computer-vision pipeline (SAM 3 + RF-DETR), 4-tier anti-detection (93% Cloudflare, 94% PerimeterX evasion), and multi-model routing (80% cost reduction). Temporal workflows, Redpanda streaming, ClickHouse observability.

`Python` `Temporal` `Redpanda` `ClickHouse` `SAM 3` `Docker`

</td>
<td width="50%" valign="top">

#### 👁️ [Verge](https://github.com/mist-ic/Verge)
**On-Device Assistive Navigation for the Blind**

iPhone app that speaks the path ahead using LiDAR depth and on-device AI. Fuses visual scene description with physical depth and refuses to guess when they disagree, saying "I'm not sure, slow down". 100% on-device, sub-100ms, fully private.

`Swift 6.2` `SwiftUI` `ARKit` `LiDAR` `Apple Intelligence`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📊 [RevSight](https://github.com/mist-ic/RevSight)
**Enterprise Revenue Intelligence Copilot**

5-node LangGraph pipeline with Pydantic AI agents: SQL metrics, risk classification, QBR narrative, and a governance audit trail. A numeric guardrail rejects hallucinated numbers. Live SSE streaming on GCP Cloud Run.

`LangGraph` `Pydantic AI` `FastAPI` `Next.js` `Neon` `GCP`

</td>
<td width="50%" valign="top">

#### 🗣️ [VaakSeva](https://github.com/mist-ic/VaakSeva)
**Self-Hosted Hindi Voice RAG over WhatsApp**

End-to-end voice RAG: Hindi voice in, Hindi voice out. Sarvam-30B via SGLang, faster-whisper STT (5.33% WER), Weaviate hybrid retrieval, Veena TTS. 100% self-hosted, zero commercial APIs, 88% retrieval accuracy.

`Sarvam-30B` `SGLang` `faster-whisper` `Weaviate` `FastAPI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔍 [ClearPath RAG](https://github.com/mist-ic/RAG-fromScratch)
**Production RAG From First Principles**

No LangChain, no vector databases. ONNX-quantized embeddings (32 MB), NumPy cosine retrieval, prompt-injection defense (8/8 blocked), 32/32 eval tests as a CI/CD gate. Docker 2GB to 666MB. GCP Cloud Run.

`Python` `FastAPI` `ONNX` `NumPy` `GCP` `React`

</td>
<td width="50%" valign="top">

#### 🔄 [SyncMist](https://github.com/mist-ic/SyncMist)
**P2P Encrypted Clipboard Sync (Rust Core)**

Cross-platform clipboard sync with a Rust networking core, QUIC transport, mDNS discovery, and AES-256-GCM encryption. Zero server dependency, fully peer-to-peer.

`Rust` `QUIC` `Flutter` `AES-256-GCM` `Moon Monorepo`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔥 [SevZero](https://github.com/mist-ic/SevZero)
**RL Environment for Autonomous SRE Incident Response**

RL benchmark where AI agents diagnose cascading cloud failures. Procedurally generated topologies, 8 failure types, a queueing-theory cascade engine, and circuit breakers. 37 deterministic tests. OpenEnv AI Hackathon 2026.

`Python` `FastAPI` `OpenEnv` `Pydantic` `Docker`

</td>
<td width="50%" valign="top">

#### 🤖 [GeneRush](https://github.com/mist-ic/GeneRush)
**Deep RL Agent, Perfect Locomotion Score**

Trained PPO across 40,960 parallel environments on 4x RTX 5090 GPUs. Perfect score (100.00) on the Circle task. Custom reward shaping solved the frozen-robot problem (+63% sprint improvement).

`PyTorch` `PPO` `Genesis Simulator` `Multi-GPU`

</td>
</tr>
</table>

<p align="center"><sub>More on the <a href="https://github.com/mist-ic?tab=repositories">repositories tab</a>: RetroFit (ad-to-landing-page agents), TWAX (autonomous content engine), HaqDekho (MCP server for welfare schemes), and more.</sub></p>

---

### Education

**Scaler** &nbsp;·&nbsp; MS in Computer Science &nbsp;·&nbsp; CGPA 10.0/10.0 &nbsp;·&nbsp; Expected 2028
**BITS Pilani** &nbsp;·&nbsp; BS in Computer Science &nbsp;·&nbsp; CGPA 9.5/10.0
**Y Combinator** &nbsp;·&nbsp; India Student Track (Invited and Attended)
**Apple Developer Academy** &nbsp;·&nbsp; 2026

---

### Tech

<table>
<tr>
<td align="center" width="50%">

**Languages & Frameworks**

[![Core](https://skillicons.dev/icons?i=python,ts,rust,react,nextjs,fastapi&theme=dark)](https://skillicons.dev)
[![More](https://skillicons.dev/icons?i=nodejs,flutter,swift,flask,html,css&theme=dark)](https://skillicons.dev)

</td>
<td align="center" width="50%">

**Infrastructure & Data**

[![Infra](https://skillicons.dev/icons?i=postgres,redis,docker,aws,gcp,linux&theme=dark)](https://skillicons.dev)
[![More](https://skillicons.dev/icons?i=elasticsearch,mongodb,firebase,git,github,vercel&theme=dark)](https://skillicons.dev)

</td>
</tr>
<tr>
<td align="center" colspan="2">

**AI & ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Pydantic AI](https://img.shields.io/badge/Pydantic_AI-E92063?style=flat-square&logo=pydantic&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX_Runtime-792EE5?style=flat-square&logo=onnx&logoColor=white)
![Temporal](https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white)
![Genesis](https://img.shields.io/badge/Genesis_Sim-4B5563?style=flat-square)

</td>
</tr>
</table>

---

### Activity

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mist-ic&theme=tokyonight&hide_border=true&background=0D1117&stroke=6366F1&ring=6366F1&fire=F59E0B&currStreakLabel=C9D1D9"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mist-ic/mist-ic/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mist-ic/mist-ic/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/mist-ic/mist-ic/output/github-snake-dark.svg" />
  </picture>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6366F1&height=120&section=footer"/>

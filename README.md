<!-- Wave Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6366F1&height=120&section=header"/>

<p align="center">
  <a href="https://github.com/mist-ic">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=2000&pause=1000&color=6366F1&center=true&vCenter=true&repeat=false&width=435&height=60&lines=Hey%2C+I'm+Praveen+%F0%9F%91%8B" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mist-ic&color=6366F1&style=flat-square&label=Profile+Views"/>
  <a href="https://github.com/mist-ic?tab=followers"><img src="https://img.shields.io/github/followers/mist-ic?label=Followers&style=flat-square&color=6366F1"/></a>
  <a href="https://linkedin.com/in/mist-ic"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
</p>

---

6 years Python · 4+ years shipping production systems · YC student · founding engineer who builds entire products from scratch. I build autonomous systems, multi-agent AI pipelines, production infrastructure, and ship fast.

---

### What I've Built

<table>
<tr>
<td width="50%" valign="top">

#### 💜 [Orchy](https://orchy.in)
**Offline-First Dating App (Founding Engineer)**

Built the entire product from scratch as sole engineer. Vibe-based matching, proposal-driven interactions (not swipe), real-time WebSocket chat with 24h timers, venue planning, live selfie verification (AWS Rekognition), split payments (Razorpay). Landing page live at [orchy.in](https://orchy.in).

`Flutter` `Bun/Hono` `PostgreSQL` `PostGIS` `pgvector` `Redis` `GCP`

</td>
<td width="50%" valign="top">

#### 🕷️ [Arachne](https://github.com/mist-ic/Arachne)
**12-Service Autonomous Web Intelligence Platform**

Distributed AI system with self-healing agents, computer vision pipeline (SAM 3 + RF-DETR), 4-tier anti-detection (93% Cloudflare, 94% PerimeterX evasion), multi-model routing (80% cost reduction). Temporal workflows, Redpanda streaming, ClickHouse observability.

`Python` `Temporal` `Redpanda` `ClickHouse` `SAM 3` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔥 [SevZero](https://github.com/mist-ic/SevZero)
**RL Environment for Autonomous SRE Incident Response**

RL benchmark where AI agents diagnose cascading cloud failures. Procedurally generated topologies, 8 failure types, queueing-theory cascade engine, circuit breakers. Benchmarked Llama-3.3-70B: 0.93/0.93/0.79. 37 deterministic tests. OpenEnv AI Hackathon 2026.

`Python` `FastAPI` `OpenEnv` `Pydantic` `Docker`

</td>
<td width="50%" valign="top">

#### 🤖 [GeneRush](https://github.com/mist-ic/GeneRush)
**Deep RL Agent, Perfect Locomotion Score**

Trained PPO across 40,960 parallel environments on 4x RTX 5090 GPUs. Perfect score (100.00) on Circle task. Custom reward shaping solved frozen-robot problem (+63% sprint improvement).

`PyTorch` `PPO` `Genesis Simulator` `Multi-GPU`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🗣️ [VaakSeva](https://github.com/mist-ic/VaakSeva)
**Self-Hosted Hindi Voice RAG over WhatsApp**

End-to-end voice RAG: Hindi voice in, Hindi voice out. Sarvam-30B via SGLang, faster-whisper STT (5.33% WER), Weaviate hybrid retrieval, Veena TTS. 100% self-hosted, zero commercial APIs. 88% retrieval accuracy.

`Sarvam-30B` `SGLang` `faster-whisper` `Weaviate` `FastAPI`

</td>
<td width="50%" valign="top">

#### 🎯 [RetroFit](https://github.com/mist-ic/RetroFit)
**6-Agent Ad to Landing Page Personalization**

LangGraph pipeline: vision ad analysis + page scraping in parallel, CRO strategy, copywriting, deterministic DOM patching (LLMs output JSON, not HTML), 5-layer QA with auto-retry. Live on GCP Cloud Run.

`LangGraph` `Gemini 3.1 Pro` `Playwright` `Next.js` `GCP`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📡 [TWAX](https://github.com/mist-ic/TWAX)
**Autonomous AI Content Engine (Built in 5 Days)**

Ships 5-7 posts/day across X, Bluesky, and Mastodon autonomously. Aggregates 100+ articles/day, AI scoring, semantic dedup (MiniLM embeddings), engagement-driven self-optimization. Zero-cost infrastructure.

`FastAPI` `Gemini 3` `sentence-transformers` `PostgreSQL` `Next.js`

</td>
<td width="50%" valign="top">

#### 🔍 [ClearPath RAG](https://github.com/mist-ic/RAG-fromScratch)
**Production RAG From First Principles**

No LangChain, no vector databases. ONNX-quantized embeddings (32 MB), NumPy cosine retrieval, prompt injection defense (8/8 blocked). 32/32 eval tests as CI/CD gate. Docker 2GB to 666MB. GCP Cloud Run.

`Python` `FastAPI` `ONNX` `NumPy` `GCP Cloud Run` `React`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📊 [RevSight](https://github.com/mist-ic/RevSight)
**Enterprise Revenue Intelligence Copilot**

5-node LangGraph pipeline with Pydantic AI agents: SQL metrics, risk classification, QBR narrative, governance audit trail. Numeric guardrail rejects hallucinated numbers. Live SSE streaming. GCP Cloud Run.

`LangGraph` `Pydantic AI` `FastAPI` `Next.js` `Neon` `GCP Cloud Run`

</td>
<td width="50%" valign="top">

#### 🔄 [SyncMist](https://github.com/mist-ic/SyncMist)
**P2P Encrypted Clipboard Sync (Rust Core)**

Cross-platform clipboard sync with Rust networking core, QUIC transport, mDNS discovery, AES-256-GCM encryption. Zero server dependency, fully P2P.

`Rust` `QUIC` `Flutter` `AES-256-GCM` `Moon Monorepo`

</td>
</tr>
</table>

---

### Tech I Use

<table>
<tr>
<td align="center" width="50%">

**Languages & Frameworks**

[![Core](https://skillicons.dev/icons?i=python,ts,rust,react,nextjs,fastapi&theme=dark)](https://skillicons.dev)
[![More](https://skillicons.dev/icons?i=nodejs,flutter,flask,html,css,js&theme=dark)](https://skillicons.dev)

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
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

</td>
</tr>
</table>

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mist-ic&theme=tokyonight&hide_border=true&background=0D1117&stroke=6366F1&ring=6366F1&fire=F59E0B&currStreakLabel=C9D1D9"/>
</p>

---

### Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mist-ic/mist-ic/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mist-ic/mist-ic/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/mist-ic/mist-ic/output/github-snake-dark.svg" />
  </picture>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=6366F1&height=120&section=footer"/>
</p>

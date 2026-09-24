## Hi, I'm Murat 👋

**Senior AI/ML & Backend Engineer. I build production ML systems in Python and Go.**

I have 19 years in software and 10+ years shipping machine learning to production. I built speech-AI platforms that process **2.5M+ calls per month** (Whisper, LLMs, Kubernetes, GCP) and, most recently, a full-stack **computer-vision product end to end as co-founder and sole engineer at [Machine Mode](https://machinemode.studio)**. I led an AI lab of 15 engineers, and I choose to stay hands-on: designing, coding, deploying and measuring.

📍 Izmir, Türkiye · open to remote · [LinkedIn](https://www.linkedin.com/in/-murat-saglam) · muratsaglam0x1@gmail.com

---

### 🔧 What I work with

**Languages:** Python · Go · TypeScript · SQL · C (WebAssembly)
**AI / ML:** PyTorch · Hugging Face Transformers · Whisper · pyannote · NVIDIA NeMo · YOLO · ByteTrack · SigLIP · scikit-learn
**LLMs:** Claude · Gemini · GPT · RAG · multi-agent systems · structured outputs · pgvector · ChromaDB
**Backend:** FastAPI · gRPC · REST · WebSockets · PostgreSQL · Redis · RabbitMQ · Pub/Sub · Elasticsearch · MongoDB · BigQuery
**Cloud & MLOps:** GCP (Cloud Run, Vertex AI, BigQuery ML, Cloud SQL) · AWS · Kubernetes · Docker · GitHub Actions · GitLab CI · Jenkins · Prometheus · Grafana
**Real-time audio:** SIP · RTP · WebRTC · Asterisk · streaming ASR · RNNoise

---

### 📌 Featured work

| Project | What it shows |
|---|---|
| [**ai-drill-manager-case-study**](https://github.com/murat-saglam/ai-drill-manager-case-study) | Football video analytics I built alone: YOLO + ByteTrack + pitch calibration → event mining → MILP planner, on Cloud Run GPU workers. Includes how a hand-labelled gold set and an open-source model cut position error **5x (4.15 m → 0.78 m)**. |
| [**call-insights-mini**](https://github.com/murat-saglam/call-insights-mini) | Runnable reference version of a production speech-analytics pattern: audio → Whisper → Claude structured outputs → FastAPI, with a labelled evaluation in CI. |
| [**the-watch-agent**](https://github.com/murat-saglam/the-watch-agent) | 11 LLM agents that run a YouTube channel, from trend to publication: event-driven state machine, RAG memory, model tiering, human-in-the-loop approval. |

### 🏭 Production highlights (AloTech / Call Center Studio, 2015–2025)

- **CX Insights:** transcription, diarization and LLM categorization of **2.5M calls/month at $0.20/call** (Whisper Large v3, Gemini, BigQuery ML, Cloud Run)
- **~15 s** end-to-end analysis of a 5-minute call, down from minutes, on a Kubernetes Whisper cluster
- Conversational IVR and chatbots with **75–87% self-service containment**
- **99.5%** model-serving uptime after introducing MLOps (CI/CD, retraining, Prometheus/Grafana)
- Browser noise suppression: RNNoise compiled to **WebAssembly** in the WebRTC audio path
- 🎤 Keynote, **Google Cloud Data & AI Day**, Doha · 🥇 World #1 Gold, *Best Technology Innovation*

### 🧭 How I work

> Measure before building. Report what you could not measure as loudly as what you did. Ship behind a switch, then let the numbers decide.

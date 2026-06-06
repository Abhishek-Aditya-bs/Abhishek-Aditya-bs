# Hi, I'm Abhishek 👋

Software Engineer II at JPMorgan Chase building backend systems for FX trading applications. I work on distributed systems, event-driven architectures, and lately, tools that help developers work better with AI.

## Quick Facts

- Building trading systems at JPMorgan Chase
- Published researcher in AI/ML
- Innovation Week Global hackathon finalist (7th place worldwide)
- AWS Certified Solutions Architect

## Published Research

**[SWIFT: Lightweight Image Super-Resolution Using Transformers and Fourier Convolutions](https://doi.org/10.47852/bonviewAIA42021930)**
*Artificial Intelligence and Applications, 2024*

A hybrid transformer architecture that achieves state-of-the-art image super-resolution with 34% fewer parameters and up to 60% faster inference. Built with PyTorch.

[![SWIFT](https://img.shields.io/badge/Code-SWIFT-blue?style=flat-square&logo=github)](https://github.com/Abhishek-Aditya-bs/SWIFT)
[![Paper](https://img.shields.io/badge/Paper-DOI-green?style=flat-square)](https://doi.org/10.47852/bonviewAIA42021930)

## Recent Projects

| Project | Description | Tech | Website |
|---------|-------------|------|---------|
| [AEGIS](https://github.com/Abhishek-Aditya-bs/Aegis) | Self-healing distributed coordination service — Raft-grade locks, leases and a versioned key-value store, with an LLM operations agent confined to the *control plane*: it reads telemetry, proposes config fixes as GitHub PRs, and drafts postmortems, but never touches consensus. Ships ConsensusOps-Bench (33 labelled Raft incidents) and a technical paper. | Java 25 · Apache Ratis · Spring Boot · gRPC · Python · LangGraph · OpenRouter · Prometheus · Grafana · Redis · Docker | [aegis-controlplane-website.pages.dev](https://aegis-controlplane-website.pages.dev) |
| [Conclave](https://github.com/Abhishek-Aditya-bs/Conclave) | Real-time multi-agent risk detection — four specialized agents deliberate over every event and return a calibrated, explainable verdict. One architecture, two domains: payment fraud and security/SOC. | Java 25 · Spring Boot · Kafka Streams · Neo4j · pgvector · Python · LangGraph · gRPC · React | [conclave-website.pages.dev](https://conclave-website.pages.dev) |
| [Warden](https://github.com/Abhishek-Aditya-bs/Warden) | Self-hosted LLM gateway — multi-provider routing, semantic cache, and a multi-stage prompt-injection defense cascade, with a nightly cost-optimizer control loop. | Java 25 · Spring Boot · Spring AI · pgvector · Redis · ONNX · LangGraph · Next.js | [warden-website.pages.dev](https://warden-website.pages.dev) |
| [CodeGraph](https://github.com/Abhishek-Aditya-bs/CodeGraph) | A GraphRAG system that turns any codebase into a queryable Neo4j knowledge graph of its files, classes, functions and interfaces, layers OpenAI vector embeddings on top, and answers natural-language questions by combining graph traversal with semantic search — all through a Streamlit UI. | Python · Neo4j · LangChain · OpenAI · Streamlit | [codegraph-website.pages.dev](https://codegraph-website.pages.dev) |
| [SWIFT](https://github.com/Abhishek-Aditya-bs/SWIFT) | Lightweight single-image super-resolution that pairs a transformer backbone with Fourier convolutions for global receptive fields — matching state-of-the-art PSNR/SSIM with 34% fewer parameters and up to 60% faster inference. Published in *AI and Applications*, 2024. | PyTorch · Transformers | [swift-website.pages.dev](https://swift-website.pages.dev) |
| [Vantage](https://github.com/Abhishek-Aditya-bs/vantage) | Turns a room full of phones into one synchronized, multi-angle camera — scan a QR to join a *space*, everyone's photos stream onto a shared live wall, and anyone can fire a **Moment**: every connected phone runs a clock-synced countdown and shoots the *same instant* from every angle, played back as a vertical recap reel. Runs entirely on the Cloudflare edge and, by design, entirely on the free tier — no origin server, no R2, no credit card. | React 19 · TypeScript · Cloudflare Workers · Durable Objects (SQLite) · Hono · D1 · KV · Workers AI · Drizzle | [vantage.abhishek-aditya10.workers.dev](https://vantage.abhishek-aditya10.workers.dev) |
| [SWARMOS](https://github.com/Abhishek-Aditya-bs/swarmos) | An operating system for AI-agent fleets — treats an agent as a first-class *schedulable, budgetable, pageable* OS process and runs tens of thousands on a single box. Virtual-thread (Loom) runtime, a fair-share scheduler + resource governor that kills runaways, rate-limited provider pools, and a demand-paged context hierarchy (off-heap → RocksDB → S3). **157× fewer OS threads and 7.5× faster** than thread-per-agent; ships a live operator console, FleetBench benchmarks and a [systems paper](https://github.com/Abhishek-Aditya-bs/swarmos/blob/main/paper/swarmos.pdf). | Java 25 · Project Loom · Spring Boot 4 · Panama FFM · gRPC · Redpanda · ClickHouse · RocksDB · Python · Pydantic AI | [swarmos-website.pages.dev](https://swarmos-website.pages.dev) |

## Tech I Use

```
Languages:    Java • Python • TypeScript • SQL • JavaScript
Backend:      Spring Boot • Spring AI • Kafka • Redpanda • gRPC • Hono • GraphQL • REST
AI / LLM:     LangGraph • LangChain • Pydantic AI • PyTorch • TensorFlow • ONNX • RAG (pgvector)
Data:         Oracle • PostgreSQL • pgvector • Redis • Neo4j • ClickHouse • RocksDB
Frontend:     React • Next.js • Vite • Tailwind CSS
Cloud / Ops:  AWS (Solutions Architect certified) • Cloudflare Workers • Durable Objects • Docker • Kubernetes • Grafana • OpenTelemetry
```

## Certifications

<a href="https://www.credly.com/badges/7c7e21c3-df75-4ad2-953e-16196d9c873b/public_url">
  <img src="https://images.credly.com/size/110x110/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" alt="AWS Solutions Architect" width="100"/>
</a>
<a href="https://www.credly.com/badges/c6f42ee9-aaa1-4321-b8cc-a86b187e29e2/public_url">
  <img src="https://images.credly.com/size/110x110/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png" alt="AWS Cloud Practitioner" width="100"/>
</a>

## Get in Touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhishek--aditya--bs-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/abhishek-aditya-bs-9a8984126/)
[![Email](https://img.shields.io/badge/Email-abhishek.aditya10@gmail.com-D14836?style=flat-square&logo=gmail)](mailto:abhishek.aditya10@gmail.com)

---

*Currently exploring the intersection of enterprise systems and AI. Open to interesting conversations.*

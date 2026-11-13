# Altan Çetin Çelik

### AI Systems · LLM Evaluation · Adaptive Inference · Backend & Edge AI

**[altancelik.dev](https://altancelik.dev)** · [LinkedIn](https://www.linkedin.com/in/altan-celik-004bb1248/) · [GitHub](https://github.com/AltanCetinCelik)

I'm an Electrical-Electronics Engineering student focused on building **AI/ML systems that make better decisions about computation, tools, memory, and real-world actions**.

My work currently sits at the intersection of:

- adaptive LLM inference,
- conditional computation and model routing,
- local-first AI agents,
- RAG and memory systems,
- backend infrastructure,
- edge computing,
- industrial telemetry and automation.

I care more about **systems that actually run, measure, fail visibly, and improve** than isolated AI demos.

---

## Currently building

### [SelectiveLLM](https://github.com/AltanCetinCelik/SelectiveLLM)

**Adaptive model-capacity orchestration for language models.**

SelectiveLLM explores whether model capacity can be treated as a runtime resource instead of keeping every available capability resident for every request.

```text id="lxqivk"
request
   ↓
capacity controller
   ↓
Which model?
Which expert?
Which adapter?
How much capacity?
What should remain resident?
   ↓
minimum sufficient computation
```

Current work includes:

- PEFT / LoRA capacity routing,
- runtime loading and eviction,
- memory-budget-aware planning,
- cache-aware execution,
- real MPS / accelerator telemetry,
- reproducible routing benchmarks,
- causal dense-capacity experiments,
- learned and calibrated routing research.

The project preserves positive, negative, and contradictory experimental results rather than hiding failed hypotheses.

**Python · PyTorch · Transformers · PEFT · ML Systems · Conditional Computation**

---

## Selected work

### [seed-showcase](https://github.com/AltanCetinCelik/seed-showcase)

A clean, dependency-free distillation of my larger local-first AI agent architecture.

It demonstrates:

- LLM routing and provider failover,
- hybrid memory,
- tool and capability abstraction,
- human approval gates,
- risk-aware execution,
- recoverable self-editing.

Every side effect passes through an explicit approval layer.

**Python · AI Agents · RAG · Memory · Guardrails · Human-in-the-loop**

---

### [My-Projects](https://github.com/AltanCetinCelik/My-Projects)

A public engineering portfolio covering AI, edge computing, industrial monitoring, backend systems, and automation.

Includes a sanitized industrial IoT / telemetry stack with:

- synthetic machine telemetry,
- edge-side data handling,
- FastAPI services,
- monitoring dashboards,
- industrial communication concepts,
- testable backend components.

**Python · FastAPI · Edge Computing · Industrial IoT · Telemetry · Automation**

---

### [ROTA](https://github.com/AltanCetinCelik/rota)

Non-custodial Solana Pay cross-border payment request platform (Crypto World's Fair 2026 / Superteam Türkiye × Arf) with on-chain receipts and live FX comparison against SWIFT, Wise, and Western Union.

**Next.js 16 · TypeScript · @solana/web3.js · Solana Pay**

---

### [luna-companion](https://github.com/AltanCetinCelik/luna-companion)

An interactive, memory-driven web companion prototype built to explore stateful UX, character interaction, and responsive frontend architecture.

**React · TypeScript · Vite · Tailwind · Framer Motion**

---

## Research interests

```text id="mt8n03"
Adaptive inference
Conditional computation
Model / expert / adapter routing
Efficient LLM systems
Agent orchestration
RAG and memory
Decision systems
Local-first AI
Edge AI
Industrial intelligence
```

I'm particularly interested in systems that can answer questions such as:

> What is the minimum computation required for this request?

> Which model, expert, context, or tool is actually useful here?

> When should an AI system abstain, escalate, or ask for approval?

> How can capable AI systems run reliably under real memory, latency, hardware, and safety constraints?

---

## Engineering stack

**Languages**

`Python` · `TypeScript` · `C` · `C++` · `SQL`

**AI / ML**

`PyTorch` · `Transformers` · `PEFT / LoRA` · `LLM Evaluation` · `Benchmarking` · `RAG` · `LLM Routing` · `Agent Systems` · `Ollama`

**Backend / Systems**

`FastAPI` · `asyncio` · `Pydantic` · `Pandas` · `Docker` · `Linux` · `pytest` · `GitHub Actions` · `REST` · `WebSockets`

**Edge / Industrial**

`Raspberry Pi` · `STM32` · `ESP32` · `MQTT` · `Modbus` · `OPC UA` · `Industrial Telemetry`

---

## How I approach projects

I try to build AI systems with explicit boundaries between:

```text id="y5nmal"
decision
execution
memory
risk
resource cost
measurement
```

That usually means:

- deterministic controls around probabilistic components,
- measurable baselines,
- explicit failure modes,
- human approval for high-impact actions,
- reproducible experiments,
- keeping negative results instead of optimizing only for demos.

---

## Contact

[altancelik.dev](https://altancelik.dev) · [LinkedIn](https://www.linkedin.com/in/altan-celik-004bb1248/) · [GitHub](https://github.com/AltanCetinCelik)

**Current focus:** SelectiveLLM, adaptive inference, agent systems, and edge AI.

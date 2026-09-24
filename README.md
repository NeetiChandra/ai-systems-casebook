# AI Systems Casebook

Architecture, data, and measurement design for large-scale AI systems delivered in an enterprise research and advisory setting — documented here as system case studies. No proprietary code or client data; each entry describes the architecture, the design decisions, and the measured outcome.

**Jump to a case:**
[Enterprise Research AI Platform](#enterprise-research-ai-platform) · [Self-Service Demand Analytics](#self-service-demand-analytics) · [NLP Thematic Coding Engine](#nlp-thematic-coding-engine) · [Agentic Research Commissioning Tool](#agentic-research-commissioning-tool) · [Executive Intelligence Systemisation](#executive-intelligence-systemisation) · [Voice-of-Customer Analytics Transformation](#voice-of-customer-analytics-transformation)

---

<a id="enterprise-research-ai-platform"></a>
## 🔍 Enterprise Research AI Platform

A retrieval-augmented research platform unifying six differently-structured proprietary data sources into a single AI-ready pipeline. Each source carries a reliability weighting in its metadata, so the retrieval layer never treats a single unverified opinion with the same trust as a validated benchmark study — the failure mode that makes most RAG systems confidently wrong.

**Result:** 85%+ retrieval precision on a 200-query benchmark, with full data lineage and confidence scoring live at go-live.

```mermaid
flowchart LR
    A[6 proprietary data sources] --> B[Source-specific normalisation]
    B --> C[AI-ready quality gates]
    C --> D[Reliability-weighted metadata layer]
    D --> E[RAG retrieval]
    E --> F[LLM-generated, sourced answer]
```

`RAG Architecture` `Data Governance` `Multi-Source Integration` `Confidence Scoring`

---

<a id="self-service-demand-analytics"></a>
## 📊 Self-Service Demand Analytics

A self-service analytics dashboard replacing multi-day manual data pulls, built on a standardised taxonomy spanning 40,000+ inquiry key phrases. Content leaders query demand signals directly instead of filing a request and waiting.

**Result:** 75% reduction in downstream dataset size through taxonomy standardisation; changed how research priorities get set.

```mermaid
flowchart LR
    A[40,000+ inquiry key phrases] --> B[Taxonomy standardisation]
    B --> C[Self-service dashboard]
    C --> D[Priorities set directly by content leaders]
```

`Demand Analytics` `Taxonomy Design` `Self-Service BI`

---

<a id="nlp-thematic-coding-engine"></a>
## 🧠 NLP Thematic Coding Engine

An in-house NLP platform replacing outsourced qualitative coding — extracting themes, entities, and sentiment from unstructured research text while retaining the domain context that external vendors lacked.

**Result:** Eliminated 100% of outsourced coding cost, with faster turnaround.

```mermaid
flowchart LR
    A[Unstructured research text] --> B[Topic modelling]
    A --> C[Named entity recognition]
    A --> D[Sentiment + importance weighting]
    B --> E[Structured thematic output]
    C --> E
    D --> E
```

`NLP` `Thematic Analysis` `Cost Elimination`

---

<a id="agentic-research-commissioning-tool"></a>
## 🤖 Agentic Research Commissioning Tool

An agentic AI tool that keeps client context intact from first conversation through to research delivery — weighting stakeholder input by domain relevance so briefs don't drift from what was actually asked. A first-of-its-kind build for its programme.

```mermaid
flowchart LR
    A[Client conversation / intake] --> B[Context capture]
    B --> C[Agentic weighting by stakeholder + domain relevance]
    C --> D[Research brief generation]
    D --> E[Commissioned study reflects original intent]
```

`Agentic AI` `Research Ops` `Stakeholder Weighting`

---

<a id="executive-intelligence-systemisation"></a>
## 📈 Executive Intelligence Systemisation

A monthly intelligence product re-engineered from a manual, inconsistent process into a systemised production model — 30+ reusable research themes standardised, then a dashboard and AI chatbot layered on top of the now-repeatable process.

**Result:** Tripled monthly output with zero added headcount; adopted directly by the client advisory community.

```mermaid
flowchart LR
    A[4 data layers: demand, research, benchmarking, analyst notes] --> B[30+ standardised themes]
    B --> C[Systemised monthly production]
    C --> D[Dashboard]
    C --> E[AI chatbot]
    D --> F[Advisory community]
    E --> F
```

`Process Design` `AI-Enabled Publishing` `Adoption Measurement`

---

<a id="voice-of-customer-analytics-transformation"></a>
## 🌐 Voice-of-Customer Analytics Transformation

Six analytical models turning noisy customer-review data across 250+ markets into a trusted commercial product — benchmarking, momentum tracking, competitive positioning, win-loss patterns, and perception-shift measurement, each built for a different commercial question.

**Result:** ~40% faster delivery cycle; became the firm's top sales-enablement asset within 12 months.

```mermaid
flowchart LR
    A[Raw reviews, 250+ markets] --> B[6 analytical models]
    B --> C[Benchmark Index]
    B --> D[Momentum Tracker]
    B --> E[Importance-Impact Matrix]
    B --> F[Competitive Positioning Map]
    B --> G[Win-Loss Analyser]
    B --> H[Pre/Post Perception Shift]
    C --> I[Trusted commercial product]
    D --> I
    E --> I
    F --> I
    G --> I
    H --> I
```

`VoC Analytics` `Analytical Architecture` `Commercial Design`

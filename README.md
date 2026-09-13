<div align="center">

# Nishant Mishra

### AI Systems Architect • Distributed Inference & Orchestration • Client-Embedded Engineering

<p align="center">
  <a href="https://linkedin.com/in/nishantm14"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:nishant.mishra123t@outlook.com"><img src="https://img.shields.io/badge/Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Pune%2C%20India-1E293B?style=for-the-badge&logo=google-maps&logoColor=38BDF8" alt="Location" />
  <img src="https://img.shields.io/badge/Focus-Enterprise%20AI%20Mesh-0F172A?style=for-the-badge&logo=target&logoColor=818CF8" alt="Focus" />
</p>

</div>

---

## 🛰️ Production AI Topology & Control Plane

```mermaid
flowchart TD
    classDef clientLayer fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#f8fafc;
    classDef orchLayer fill:#0f172a,stroke:#818cf8,stroke-width:2px,color:#f8fafc;
    classDef evalLayer fill:#0f172a,stroke:#34d399,stroke-width:2px,color:#f8fafc;
    classDef infraLayer fill:#0f172a,stroke:#fbbf24,stroke-width:2px,color:#f8fafc;
    classDef storageLayer fill:#0f172a,stroke:#c084fc,stroke-width:2px,color:#f8fafc;

    subgraph Client ["Client & Visualization Plane"]
        A["Next.js / React Control UI"]:::clientLayer
        B["D3.js Real-Time Stream Visualizer"]:::clientLayer
    end

    subgraph Orchestration ["Agentic Mesh & State Control"]
        C["A2A State Machine Engine"]:::orchLayer
        D["FastMCP Protocol & Context Router"]:::orchLayer
    end

    subgraph Gateway ["Deterministic Verification Gateway"]
        E["Langfuse Continuous Tracing & Latency Gates"]:::evalLayer
        F["NIST RMF / EU AI Act Automated Compliance"]:::evalLayer
    end

    subgraph Compute ["Low-Carbon Inference Infrastructure"]
        G["Domain-Quantized Vector Embeddings"]:::infraLayer
        H["AWS Bedrock / Azure AI Foundry Hybrid"]:::infraLayer
    end

    subgraph Data ["Enterprise Data Fabric"]
        I["Databricks Unity Catalog | GreenplumDB | S3"]:::storageLayer
    end

    A <-->|WebSocket Stream| C
    B <-->|Telemetry Feed| D
    C -->|Intent Scoping| D
    D -->|Deterministic Eval| E
    D -->|Vector Retrieval| G
    E -->|Safety Assertion| F
    G -->|Optimized Compute| H
    H <-->|ETL Ingestion| I
```

---

## 🏛️ Architectural Pillars

<table>
<tr>
<td width="50%" valign="top">

### 1. Agentic Mesh & State Orchestration
<img src="https://img.shields.io/badge/Status-Production%20Grade-818CF8?style=flat-square" /> <img src="https://img.shields.io/badge/Stack-LangGraph%20%7C%20FastMCP-0F172A?style=flat-square" />

- **State-Machine Governance**: Architected resilient agent-to-agent (A2A) topologies with deterministic state transitions, replacing fragile ad-hoc chains with verifiable workflows.
- **Enterprise Data Federation**: Deployed unified context-routing layers across disparate data architectures including Salesforce Lightning, AWS S3, GreenplumDB, and Databricks Unity Catalog.
- **Unified Runtime**: Standardized multi-model execution across Azure AI Foundry and Amazon Bedrock.

</td>
<td width="50%" valign="top">

### 2. Deterministic Evaluation & Observability
<img src="https://img.shields.io/badge/Status-Continuous%20Eval-34D399?style=flat-square" /> <img src="https://img.shields.io/badge/Stack-Langfuse%20%7C%20NIST%20RMF-0F172A?style=flat-square" />

- **Continuous Tracing**: Integrated **Langfuse** tracing, custom assertions, and latency monitors into automated CI/CD verification gates.
- **Automated Regression Benches**: Validated multi-step agent reasoning across 200+ edge-case test fixtures for clinical and quantitative financial systems.
- **Regulatory Frameworks**: Operationalized policy enforcement compliant with **NIST RMF**, **EU AI Act**, and **GDPR** at model runtime and boundary layers.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 3. Sustainable, Low-Latency Inference
<img src="https://img.shields.io/badge/Status-30%25%20Latency%20Cut-FBBF24?style=flat-square" /> <img src="https://img.shields.io/badge/Stack-Quantized%20Embeddings-0F172A?style=flat-square" />

- **Quantized Embedding Pipelines**: Engineered domain-specific embedding representations, reducing inference latency by **30%** and significantly trimming active GPU compute footprint.
- **Semantic Caching & Pruning**: Deployed vector similarity caches and token pruning to eliminate redundant inference calls and minimize energy draw.
- **High-Throughput Ingestion**: Architected distributed ETL pipelines for zero-loss real-time data synchronization across cloud boundaries.

</td>
<td width="50%" valign="top">

### 4. Reactive Client-Facing Control Planes
<img src="https://img.shields.io/badge/Status-Sub--Second%20Telemetry-38BDF8?style=flat-square" /> <img src="https://img.shields.io/badge/Stack-Next.js%20%7C%20D3.js-0F172A?style=flat-square" />

- **Quantitative Risk Dashboards**: Built real-time **Next.js & D3.js** calculation platforms for Monte Carlo, Parametric, and Historical VaR simulations, reducing insight generation latency by **~40%**.
- **Human-in-the-Loop Visualizers**: Designed reactive state-machine streaming interfaces for live agent trace telemetry, dynamic graph rendering, and executive steering.
- **Zero-Layout-Shift Systems**: Engineered modular, high-density component libraries in React and Tailwind CSS.

</td>
</tr>
</table>

---

## 🧪 Selected Production Implementations

### 1. MediMind: Deterministic Clinical Decision Architecture

```mermaid
flowchart LR
    classDef comp fill:#0f172a,stroke:#38bdf8,stroke-width:1.5px,color:#f8fafc;
    classDef check fill:#0f172a,stroke:#34d399,stroke-width:1.5px,color:#f8fafc;

    A["Clinical Corpus"]:::comp --> B["Domain Embeddings (-30% Latency)"]:::comp
    B --> C["Hybrid Vector / Graph Store"]:::comp
    C --> D["LangChain Agentic State Graph"]:::comp
    D --> E["200+ Case Deterministic Test Gate"]:::check
    E --> F["90% Diagnostic Accuracy Output"]:::check
```

- **Core Capabilities**: Multi-step clinical reasoning engine combining medical ontologies, semantic embeddings, and automated boundary checking.
- **Verification Gate**: Validated against an automated 200+ case regression test bench to guarantee deterministic diagnostic recommendations.

---

### 2. Enterprise Quantitative Market Risk (VaR) Engine

```mermaid
flowchart LR
    classDef comp fill:#0f172a,stroke:#818cf8,stroke-width:1.5px,color:#f8fafc;
    classDef out fill:#0f172a,stroke:#fbbf24,stroke-width:1.5px,color:#f8fafc;

    A["Multi-Asset Book"]:::comp --> B["BCBS FRTB SA/IMA Calculator"]:::comp
    B --> C["Monte Carlo & Parametric Simulation"]:::comp
    C --> D["Python Analytical Stream"]:::comp
    D --> E["Next.js + D3.js Visual Control Plane"]:::out
    E --> F["-40% Desk Latency"]:::out
```

- **Core Capabilities**: High-throughput risk simulation engine automating BCBS FRTB Standardized and Internal Model Approach capital charge computations.
- **Performance**: Interactive D3.js visualizers streamlined sensitivity backtesting, cutting analysis latency by ~40%.

---

### 3. Biosignal Neural Diagnostic Pipeline (Microsoft Learn Societal Impact Finalist)

```mermaid
flowchart LR
    classDef comp fill:#0f172a,stroke:#c084fc,stroke-width:1.5px,color:#f8fafc;
    classDef res fill:#0f172a,stroke:#34d399,stroke-width:1.5px,color:#f8fafc;

    A["Raw Multi-Channel Cardiac Signals"]:::comp --> B["FFT / MFCC Spectral Transform"]:::comp
    B --> C["SMOTE Synthetic Balancing"]:::comp
    C --> D["Deep CNN Multi-Class Classifier"]:::comp
    D --> E["90% Accuracy Across 5 Pathologies"]:::res
```

---

## 🛠️ Systems & Technology Matrix

| Architectural Layer | Core Stack & Technologies |
| :--- | :--- |
| **Agentic Mesh & State Control** | `LangGraph` `LangChain` `LlamaIndex` `FastMCP` `WebSockets` `Python` `TypeScript` |
| **Verification & Observability** | `Langfuse` `NIST RMF` `EU AI Act` `GDPR Compliance` `Automated Assertions` |
| **Inference & Green Infrastructure** | `Amazon Bedrock` `Azure AI Foundry` `AWS S3` `Quantized Embeddings` `Semantic Caching` |
| **Data Fabric & Topologies** | `Databricks Unity Catalog` `Neo4j (Cypher)` `PostgreSQL` `GreenplumDB` `MySQL` |
| **Visualization & Front-End** | `Next.js` `React` `Tailwind CSS` `D3.js` `State-Driven UI` `High-Density Telemetry` |

---

## 🎖️ Technical Honors & Validations

<table>
<tr>
<td width="50%" valign="top">

#### Competitive Benchmarks
- **Top 100 Global Rank** — Amazon ML Challenge 2025
- **Zonal Finalist** — Smart India Hackathon 2024
- **Top 10 Finalist** — Microsoft Learn Societal Impact Initiative

</td>
<td width="50%" valign="top">

#### Technical Specializations & Programs
- **Anthropic**: AI Fluency for Builders
- **NVIDIA**: Fundamentals of Deep Learning
- **McKinsey & Company**: Forward Scholar
- **BCG**: Data Science & Advanced Analytics
- **Yale University**: Financial Markets

</td>
</tr>
</table>

---

<div align="center">
  <sub>Nishant Mishra • Enterprise AI Systems & Distributed Architecture</sub>
</div>

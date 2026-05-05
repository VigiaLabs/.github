<div align="center">
  <!-- Pro-tip: Add a 1500x500 VIGIA banner image here -->
  <h1>🌐 VIGIA</h1>
  <p><b>Autonomous Road Intelligence Ecosystem | Edge AI • Serverless Cloud</b></p>
  
  [![Website](https://img.shields.io/badge/Website-vigia.ai-blue?style=flat-square)](#)
</div>

---

## 🚀 The Mission
VIGIA is decentralizing road intelligence. We transform passive municipal fleets into a live hazard nervous system. By bridging compute-constrained edge hardware with highly optimized, serverless cloud infrastructure, we deliver real-time predictive maintenance data for modern smart cities before infrastructure decay leads to massive liabilities.

## 🧩 The Ecosystem Architecture
Our architecture operates on a strict spec-driven development philosophy, utilizing edge-first compute to bypass redundant cloud processing and achieve sub-penny unit economics ($0.028 per node/month).

### 1. Edge Perception (`/vigia-raspi`)
The physical ingestion layer. Optimized natively for ARM Cortex architectures, this C++ pipeline concurrently runs INT8 quantized models (YOLO & MiDaS) at ~9 FPS. It utilizes **Edge-First Spatial Hashing** via Uber's H3 library, natively assigning a Resolution 12 Hex ID to hazard telemetry before transmission to eliminate cloud-side distance matrix computations.

### 2. Serverless Infrastructure (`/vigia-amazon`)
The central nervous system. A strictly serverless AWS backend engineered for massive ingestion throughput. It utilizes zero-compute API Gateway routing and DynamoDB NoSQL conditional logic (`attribute_not_exists`) to strictly deduplicate incoming H3 Hex IDs, maintaining atomic reliability and aggressively low FinOps overhead.

### 3. Enterprise Command Center (`/VIGIAWEB`)
The B2G (Business-to-Government) client interface. A high-fidelity, real-time dispatch dashboard utilized by municipal public works departments to visualize road intelligence, track active fleet status, and automate repair ticketing.

---

## 🏆 Traction & Recognition
Our architecture has been pressure-tested and recognized across top-tier global engineering platforms:
* 🥇 **1st Place** — i.mobilothon 5.0 (Volkswagen Group)
* 🥇 **Winner (PS3)** — Bharat AI-SoC Student Challenge (ARM & MeitY)
* 🌍 **Top 50 Global Finalist** — AWS AIdeas 10,000

---

## 🛠️ Core Technology Stack
* **Edge Compute:** C++, OpenVINO, NEON SIMD, INT8 Quantization, H3-js
* **Cloud & Infra:** AWS Serverless Primitives, DynamoDB, REST/WebSocket APIs
* **Web Client:** React, Next.js, TailwindCSS

<br>

<div align="center">
  <i>Building the physical infrastructure network of tomorrow.</i> <br>
  <b>Led by Tom Mathew</b>
</div>

# ScieTechQMS — Functional Overview

**The Cognitive Quality Layer for Life Sciences**

Official portal: [rabbittrix.github.io/ScieTechQMS.io](https://rabbittrix.github.io/ScieTechQMS.io/)  
Downloads & releases: [github.com/rabbittrix/ScieTechQMS.io/releases](https://github.com/rabbittrix/ScieTechQMS.io/releases)  
License enquiries: [rabbittrix@hotmail.com](mailto:rabbittrix@hotmail.com)

---

This document describes **how ScieTechQMS works for your organisation** — from regulatory positioning and daily workflows to data integrity, audit readiness, and licensing. It is written for **Quality Managers**, **Regulatory Auditors**, and **C-level executives** evaluating enterprise-ready quality infrastructure.

---

## 1. Product Vision

ScieTechQMS is positioned as a **Cognitive Quality Layer** — a Quality 4.0 platform that extends traditional QMS capabilities with local artificial intelligence, visual traceability, and cryptographically secured audit evidence. Rather than replacing your quality culture, it provides a controlled digital environment in which every regulated action is attributable, reviewable, and defensible under inspection.

The system is designed to support organisations operating under:

| Framework | Functional alignment |
| --------- | -------------------- |
| **ISO 13485** | Document control, CAPA, risk management, and traceable linkages across the quality management system |
| **21 CFR Part 11** | Electronic records, electronic signatures, audit trails, and access controls suitable for FDA-regulated environments |
| **ALCOA+** | Attributable, Legible, Contemporaneous, Original, Accurate records — with Completeness, Consistency, Enduring, and Available evidence |

ScieTechQMS is deployed as a **native desktop application** on your own infrastructure. There is no mandatory cloud tenancy, no external data processor for regulated content, and no dependency on continuous internet connectivity for core quality operations. This model supports **data sovereignty**, **risk mitigation**, and **audit readiness** for medical device, pharmaceutical, and life-sciences manufacturers.

---

## 2. Core Operational Pillars

### True AI-on-the-Edge (Embedded Cognitive Core)

**Headline:** True AI-on-the-Edge: Zero Cloud. Zero Latency. Absolute Sovereignty.

Our key differentiator is **AI-on-the-Edge**. While competitors rely on expensive servers and constant internet connectivity, ScieTechQMS features an **embedded pharmaceutical intelligence engine** (Microsoft Phi-3 Mini via `llama-server`) directly within the binary. The system operates flawlessly in production bunkers and isolated laboratories — **audit-ready in dark facilities** — with zero latency and maximum security.

> **Note:** ScieTechQMS includes an embedded 2.3GB Cognitive AI Core. No internet or external AI installation (like Ollama) is required. Secure, private, and audit-ready out of the box.

From a governance perspective, this means:

- **Intellectual property remains under your control** at all times — no data ever leaves your device.
- **Validation and privacy assessments** are simplified — AI inference occurs within the same controlled boundary as your QMS data.
- **Regulatory confidence** is preserved: AI-assisted reviews produce recommendations locally, with full human oversight retained and `Engine: Embedded-Phi3-Local` recorded in the immutable audit trail.

### Offline Resilience

ScieTechQMS is an **edge-native, native desktop application** with a high-performance core engineered for reliability under operational stress. Quality operations — document review, electronic signatures, CAPA updates, audit logging, and validation exports — **continue during network outages**.

This is critical for manufacturing and laboratory environments where connectivity cannot be guaranteed. Your QMS remains **available, auditable, and compliant** whether the facility is online or offline. When connectivity returns, no synchronisation conflict arises because authoritative records reside locally from the outset.

### Visual Traceability

Regulatory inspections frequently require proof that documents, CAPAs, risks, and corrective actions are **correctly linked** across the quality system. ScieTechQMS provides an **interactive linkage graph** that maps these relationships visually — reducing hours of manual cross-referencing to seconds of navigable evidence.

Quality Managers and Auditors can:

- Trace a CAPA back to its originating document or risk record.
- Demonstrate ISO 13485 structural compliance during HPRA, FDA, or notified-body reviews.
- Export traceability views as part of a broader validation or inspection package.

This pillar directly supports **data integrity** and **inspection efficiency**.

---

## 3. User Roles & Workflow

ScieTechQMS implements role-based access aligned with typical life-sciences organisational structures. Each role sees only the functions required for its responsibilities, supporting least-privilege access and clear accountability.

### Standard User (Operator)

**Primary focus:** Execution of assigned quality tasks.

Typical activities include:

- Creating and updating quality records within authorised scope.
- Reviewing controlled documents and completing assigned actions.
- Executing workflows and providing electronic signatures where permitted.
- Viewing personal task queues and record status.

Standard Users contribute to **data integrity** through structured data entry; they do not configure system-wide policies or manage licensing.

### Admin / Quality Manager

**Primary focus:** Oversight, configuration, and continuous improvement.

Typical activities include:

- Managing document control, CAPA lifecycle, and risk registers.
- Configuring users, roles, and organisational structure (after initial provisioning).
- Monitoring open CAPAs, overdue actions, and quality metrics on the **Quality Dashboard**.
- Initiating investigations, approvals, and closure of corrective actions.
- Overseeing license status and user administration via **License & Users**.

The Quality Manager role is the operational owner of **audit readiness** and **risk mitigation** within the platform.

### Auditor Mode (Inspector Portal)

**Primary focus:** Independent verification for third-party inspection.

Auditor Mode provides a dedicated **Auditor Portal** — a read-oriented command centre designed for HPRA, FDA, and notified-body inspectors. It enables:

- **Live audit stream** monitoring of system activity.
- **Chain of Trust** integrity verification — confirming that the audit ledger has not been altered.
- **Record timelines** and signature history for selected entities.
- **Validation report** and **audit snapshot** exports for offline inspector review.
- **Guardian AI integrity scans** to highlight patterns warranting further investigation.

Auditor Mode is structured to give inspectors **regulatory confidence** without granting write access to production records — preserving both **transparency** and **control**.

---

## 4. The Chain of Trust Integrity Model

At the heart of ScieTechQMS data integrity is the **Chain of Trust** — a sequential, tamper-evident audit ledger that records every material action in the quality system.

### How it works (functional description)

1. **Every regulated action** — create, update, approve, sign, or status change — generates an immutable audit entry.
2. Each entry includes a **cryptographic fingerprint** (hash) derived from the action details, user identity, timestamp, and the fingerprint of the **preceding** entry.
3. Entries are linked in chronological order, forming a continuous chain. Altering any historical record would break the chain at that point.
4. The system performs **integrity verification** on demand, reporting whether the chain is intact or whether anomalies — such as missing links, temporal inconsistencies, or ALCOA+ field violations — are detected.

### What this means for your organisation

| Concern | Chain of Trust response |
| ------- | ----------------------- |
| Backdating records | Detected — timestamps and chain sequence are cryptographically bound |
| Silent deletion or alteration | Detected — hash mismatch breaks chain continuity |
| Attribution disputes | Resolved — every entry is tied to an authenticated user |
| Inspection evidence | Defensible — integrity status can be demonstrated live to auditors |

This model supports **21 CFR Part 11** expectations for secure, computer-generated, time-stamped audit trails and strengthens **regulatory confidence** during validation and inspection.

---

## 5. Licensing & Activation Process

ScieTechQMS uses a transparent, hardware-bound licensing model suitable for controlled GxP deployments. Evaluation is available before commitment; full regulated write capabilities unlock upon activation.

### Step 1 — Download & Explore

Download the latest installer from the [public releases page](https://github.com/rabbittrix/ScieTechQMS.io/releases/latest) — **Latest Version: 1.1.4 (Edge Intelligence Edition)**:

| Platform | Installer (versioned release history) |
| -------- | --------- |
| Windows 10 / 11 (NSIS) | `ScieTechQMS_v{VERSION}_x64-setup.exe` |
| Windows 10 / 11 (MSI) | `ScieTechQMS_v{VERSION}_x64_en-US.msi` |
| Linux (Ubuntu / Debian) | `ScieTechQMS_v{VERSION}_amd64.deb` |

Example for v1.1.4: `ScieTechQMS_v1.1.4_x64_en-US.msi`.

Install locally and explore document control, audit trails, traceability views, and Guardian AI — **no license key is required for evaluation**.

### Step 2 — Generate Unique Hardware Hash

When your organisation is ready to proceed, open **License & Users** within the application and copy your **Unique Hardware Hash**. This identifier binds the license to your deployment environment and supports controlled activation.

### Step 3 — Request Activation

Submit a license request via the [portal license form](https://rabbittrix.github.io/ScieTechQMS.io/#license) or email [rabbittrix@hotmail.com](mailto:rabbittrix@hotmail.com) with:

- Company / institution name and contact details
- Desired license period (1 Month · 6 Months · 1 Year)
- Your generated Hardware Hash
- Any deployment notes relevant to validation planning

### Step 4 — Receive Signed License Key

ScieTechQMS issues a **cryptographically signed license key** matched to your hardware hash and contracted period. Tampered or expired keys are rejected by the application.

### Step 5 — Unlock Full GxP Features

Paste the signed key into **License & Users** to activate your license period. Regulated write operations — including electronic signatures, CAPA closure, and controlled record changes — are enabled for the duration of your contract.

---

## 6. System Requirements

ScieTechQMS is engineered for a **minimal hardware footprint** while delivering enterprise-grade performance through its native, high-efficiency core.

| Requirement | Specification |
| ----------- | ------------- |
| **Operating system** | Windows 10 or Windows 11 (64-bit); Linux — Ubuntu 20.04+ or Debian 11+ |
| **Processor** | 64-bit x86 processor; dual-core or higher recommended |
| **Memory** | 8 GB RAM minimum; 16 GB recommended when Guardian AI is active |
| **Storage** | 2 GB available disk space for application and local database; additional space for audit exports and AI models |
| **Display** | 1280 × 800 minimum resolution |
| **Network** | Not required for core QMS operations; internet optional for license activation and release updates |
| **Embedded Cognitive Core** | Embedded 2.3GB Cognitive AI Core — no internet or external AI (e.g. Ollama) required; secure, private, and audit-ready out of the box |

For validated environments, include ScieTechQMS in your **Installation Qualification (IQ)** documentation using the above baseline. Performance remains stable on standard quality-office and shop-floor workstations.

---

## Regulatory Positioning Summary

ScieTechQMS is **Designed for GxP, ISO 13485, and 21 CFR Part 11 validation workflows**. It prioritises:

- **Data Integrity** — ALCOA+ aligned records with tamper-evident audit trails  
- **Audit Readiness** — live integrity verification and inspector-focused export tools  
- **Risk Mitigation** — local deployment, offline resilience, and role-based access control  
- **Regulatory Confidence** — traceability, attributable signatures, and defensible evidence chains  

For product demonstrations, downloads, and license requests, visit the [official web portal](https://rabbittrix.github.io/ScieTechQMS.io/).

---

## Repository Note (Maintainers)

This repository hosts the **ScieTechQMS public web portal** (static marketing site and download hub), deployed to GitHub Pages at `/ScieTechQMS.io`. Application installers are published via GitHub Releases on this repository. The ScieTechQMS desktop application itself is developed and validated separately; this README describes **functional system behaviour** for stakeholders evaluating the product.

### GitHub Pages (fix 404)

If `https://rabbittrix.github.io/ScieTechQMS.io/` shows **404 — There isn't a GitHub Pages site here**:

1. In **rabbittrix/ScieTechQMS.io** → **Settings** → **Pages** → set **Source** to **Deploy from branch** → branch **`main`** → folder **`/ (root)`** → Save.
2. On the private **ScieTechQMS** repo, set secret **`API_TOKEN_STQMS`** (PAT with `repo` scope on `ScieTechQMS.io`).
3. Push to **`main`** on the private repo — **Release and Deploy** validates on ScieTechQMS, then deploys the site to ScieTechQMS.io.
4. To publish installers, run **Release and Deploy** with **Publish installers** enabled, or push tag **`v*`** (e.g. `v1.0.2`). Installers are released on ScieTechQMS first, then mirrored to ScieTechQMS.io.
5. Wait 1–2 minutes; confirm `index.html`, `.nojekyll`, and `_next/` exist at the root of public repo **`main`**, and release assets at [ScieTechQMS.io releases](https://github.com/rabbittrix/ScieTechQMS.io/releases).

**Contact:** [rabbittrix@hotmail.com](mailto:rabbittrix@hotmail.com)  
**Copyright © 2026 ScieTechQMS · Roberto de Souza · All rights reserved.**

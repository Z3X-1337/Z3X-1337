<div align="center">

# `Z3X-1337`

### ZAID HIJAZI · DEFENSIVE SECURITY ENGINEERING

**Cybersecurity student focused on SOC operations, threat-hunting fundamentals, detection engineering, and Python security automation.**

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-z3x--1337.github.io-66f2b4?style=for-the-badge&labelColor=05070b)](https://z3x-1337.github.io/) [![GitHub](https://img.shields.io/badge/GITHUB-Z3X--1337-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Z3X-1337) [![LinkedIn](https://img.shields.io/badge/LINKEDIN-Zaid%20Hijazi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zaid-hijazi-a34b97278/) [![Bugcrowd](https://img.shields.io/badge/BUGCROWD-Z3X-F26822?style=for-the-badge)](https://bugcrowd.com/h/Z3X)

</div>

```text
┌──────────────────────────────────────────────────────────────────────────┐
│ Z3X / SECURITY PROFILE                                                   │
│                                                                          │
│ PRIMARY VECTOR   SOC  →  THREAT HUNTING                                 │
│ ENGINEERING      Python / SQLite / CLI / Testing / GitHub Actions        │
│ DETECTION        Deterministic / Evidence-backed / Explainable           │
│ DATA HANDLING    Local-first / Sanitized evidence / Explicit boundaries  │
└──────────────────────────────────────────────────────────────────────────┘
```

## Mission

Build practical defensive-security systems that make analyst work more structured, reproducible, and reviewable.

The immediate goal is an **entry-level SOC role**. The longer path is **threat hunting**: forming a hypothesis, identifying the telemetry required to test it, preserving an evidence chain, and communicating confidence and limitations clearly.

## Public engineering evidence

| Repository | What it demonstrates |
|---|---|
| **[SOC CaseForge](https://github.com/Z3X-1337/soc-caseforge)** | Local-first SOC workflow: evidence ingestion → normalized timeline → IOC extraction → deterministic findings → Markdown/JSON reports. SQLite-backed, 24 tests, Python 3.10–3.12 CI. |
| **[Auth Log Analyzer](https://github.com/Z3X-1337/auth-log-analyzer)** | OpenSSH authentication analysis for repeated failures, password-spray-style behavior, invalid users, accepted logins, IPv4/IPv6, and multiple SSH methods. 12 tests. |
| **[IOC Sanitizer](https://github.com/Z3X-1337/ioc-sanitizer)** | Deterministic IOC extraction, validation, normalization, defanging/refanging, and traceable JSON/CSV output. 13 tests. |
| **[Security Header Auditor](https://github.com/Z3X-1337/security-header-auditor)** | Authorized HTTP response-header review with CSP observations, redirect handling, deterministic CI thresholds, and 16 tests. |

### Current evidence surface

- **65+ tests** across the public defensive tooling.
- GitHub Actions coverage for **Python 3.10, 3.11, and 3.12**.
- Installable `v0.1.0` Python CLIs with versioned packaging, changelogs, roadmaps, MIT licensing, and security policies.
- Public projects use sanitized evidence and explicitly document detection limitations.

## Blue Team focus

**SOC operations** — case handling, evidence preservation, authentication telemetry, incident reporting, and analyst-oriented outputs.

**Detection engineering** — threshold-based observations, reproducible rules, evidence-backed findings, ATT&CK assistance, and false-positive awareness.

**Threat hunting** — hypothesis formation, telemetry requirements, evidence chains, confidence language, and iterative investigation workflows.

**Security automation** — small Python systems that are installable, testable, deterministic, and useful from the command line.

## Training

### National Cyber Security Center (Jordan) — Cyber Warriors

- 40-hour CTF training for university students — completed **2026**.
- 40-hour CTF training for university students — completed **2024**.

### Immersive Labs — Continuing Professional Education

**23 CPE hours · 47 hands-on labs · 6720 points** covering threat hunting and IOC analysis, incident response, digital forensics, network traffic analysis, reverse-engineering fundamentals, Splunk detection workflows, web-security fundamentals, and security investigation methodologies.

### Green Circle For Software Solutions — Cyber Security Associate Course

Training covering cybersecurity fundamentals, core security concepts, and defensive security principles.

[View certificates →](https://z3x-1337.github.io/assets/certificates)

## Engineering principles

```text
01  Scope before implementation.
02  Preserve evidence and provenance.
03  Prefer deterministic security logic before enrichment.
04  Every finding should expose evidence, confidence, limitations, and next actions.
05  Tests, CI, packaging, and documentation are part of the security artifact.
06  Public claims should be traceable to code, tests, CI, or documentation.
07  Use authorized and sanitized data only.
```

## Current build direction

**SOC CaseForge** is the central engineering track. The next phase prioritizes evidence integrity and analyst decisions over superficial feature growth:

- timezone-aware timestamps;
- CSV and generic JSON adapters;
- analyst notes and dispositions;
- suppression / allowlist policies;
- SHA-256 evidence manifests;
- representative false-positive datasets.

## Contact

| Channel | Use |
|---|---|
| [GitHub](https://github.com/Z3X-1337) | Code, issues, project history |
| [LinkedIn](https://www.linkedin.com/in/zaid-hijazi-a34b97278/) | Professional opportunities |
| [Email](mailto:z3x1337@gmail.com) | Direct project communication |

> **Security boundary:** do not send credentials, customer data, production logs, tokens, or confidential incident material through public channels.

<div align="center">

`Z3X-1337` // observe · normalize · explain · validate

</div>

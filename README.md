# Zaid Hijazi

**Final-year Cybersecurity student focused on Blue Team operations, SOC analysis, threat hunting, and Python security automation.**

[![Portfolio](https://img.shields.io/badge/Portfolio-z3x--1337.github.io-0f766e?style=flat-square)](https://z3x-1337.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Zaid%20Hijazi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zaid-hijazi-a34b97278/)
[![GitHub](https://img.shields.io/badge/GitHub-Z3X--1337-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Z3X-1337)

## Focus

- SOC alert triage, evidence handling, and incident reporting.
- Authentication-log analysis and explainable detection logic.
- IOC extraction, normalization, and safe evidence sharing.
- Threat-hunting fundamentals and defensive automation.
- Installable Python tooling with structured output, SQLite, tests, and CI.

## Selected Projects

| Project | What it does | Current evidence |
| --- | --- | --- |
| **[SOC CaseForge](https://github.com/Z3X-1337/soc-caseforge)** | Connects evidence ingestion, timeline preservation, IOC extraction, deterministic detections, case storage, and analyst reporting in one local-first workflow. | Primary project; installable `v0.1.0` CLI, SQLite, OpenSSH ingestion, JSON/Markdown reports, 24 tests, [demo report](https://github.com/Z3X-1337/soc-caseforge/blob/main/docs/demo-report.md) |
| [Auth Log Analyzer](https://github.com/Z3X-1337/auth-log-analyzer) | Parses OpenSSH authentication logs and identifies repeated failures, password-spray behavior, and suspicious source activity. | Installable `v0.1.0` CLI, 12 tests, IPv4/IPv6, JSON/Markdown, ATT&CK rationale |
| [IOC Sanitizer](https://github.com/Z3X-1337/ioc-sanitizer) | Extracts, validates, normalizes, defangs, and refangs standard and commonly defanged indicators. | Installable `v0.1.0` CLI, 13 tests, IPv4/IPv6, JSON/CSV, source traceability |
| [Security Header Auditor](https://github.com/Z3X-1337/security-header-auditor) | Reviews selected HTTP response security headers for authorized targets and CI quality gates. | Installable `v0.1.0` CLI, 16 tests, redirects, CSP baseline, stable exit codes |

The portfolio contains **65 unit, CLI, storage, and local integration tests**. Every project:

- runs GitHub Actions against Python 3.10, 3.11, and 3.12;
- validates package installation and the installed console command;
- includes MIT licensing, Semantic Versioning metadata, a changelog, and an engineering roadmap;
- documents scope, limitations, and analyst-validation requirements.

## Current Direction

I am preparing for an entry-level SOC role while building toward threat hunting. My main engineering focus is SOC CaseForge: a local-first case workflow that turns sanitized evidence into structured timelines, indicators, explainable findings, and reviewable reports.

- [Review the sanitized end-to-end demonstration](https://github.com/Z3X-1337/soc-caseforge/blob/main/docs/demo-report.md)
- [Track the evidence-integrity and analyst-decision roadmap](https://github.com/Z3X-1337/soc-caseforge/issues/2)

## Working Principles

- Defensive and authorized use only.
- Sanitized samples instead of real credentials or customer data.
- Deterministic results before AI-assisted enrichment.
- Findings should include evidence, confidence, limitations, and a clear next action.
- Public claims must be supported by code, tests, CI, or documentation.

# Zaid Hijazi

**Final-year Cybersecurity student focused on Blue Team operations, SOC analysis, threat hunting, and Python security automation.**

[![Portfolio](https://img.shields.io/badge/Portfolio-z3x--1337.github.io-0f766e?style=flat-square)](https://z3x-1337.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Zaid%20Hijazi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zaid-hijazi-a34b97278/)
[![GitHub](https://img.shields.io/badge/GitHub-Z3X--1337-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Z3X-1337)

## Focus

- SOC alert triage, evidence handling, and incident reporting.
- Authentication-log analysis and detection logic.
- IOC extraction, normalization, and safe sharing.
- Threat-hunting fundamentals and defensive automation.
- Python CLI tooling with tests, structured output, and CI.

## Selected Projects

| Project | What it does | Current evidence |
| --- | --- | --- |
| [Auth Log Analyzer](https://github.com/Z3X-1337/auth-log-analyzer) | Parses OpenSSH authentication logs and identifies repeated failures, password-spray behavior, and suspicious source activity. | 12 unit/CLI tests, IPv4/IPv6, JSON/Markdown reports, ATT&CK rationale |
| [IOC Sanitizer](https://github.com/Z3X-1337/ioc-sanitizer) | Extracts, normalizes, defangs, and refangs common indicators of compromise. | 6 unit/CLI tests, grouped output, standard-library implementation |
| [Security Header Auditor](https://github.com/Z3X-1337/security-header-auditor) | Reviews common HTTP response security headers for authorized targets. | 7 unit/CLI tests, policy-based findings, JSON output |

The portfolio currently contains **25 unit and CLI tests**. All three repositories run automated tests through GitHub Actions against Python 3.10, 3.11, and 3.12.

## Current Direction

I am preparing for an entry-level SOC role while building toward threat hunting. My current engineering priority is to turn small defensive utilities into stronger analyst workflows with better parsing, detection rationale, test coverage, and reporting.

## Working Principles

- Defensive and authorized use only.
- Sanitized samples instead of real credentials or customer data.
- Deterministic results before AI-assisted enrichment.
- Findings should include evidence, limitations, and a clear next action.
- Public claims must be supported by code, tests, or documentation.

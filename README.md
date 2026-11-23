# Artem Kalinin

## IT Support · Application Support · QA Automation · Python Backend

Technical troubleshooting, application support, Linux, log analysis, REST APIs, SQL and test automation.

I work with technical issues by narrowing down symptoms, checking dependencies, validating the result and documenting repeatable solutions. My portfolio includes hands-on labs and independently built projects across support engineering, API testing and Python automation.

**[Support & engineering portfolio](https://github.com/blvxx/portfolio)** · **[Engineering showcase](https://blvxx.github.io/portfolio/engineering/)** · **[Web development portfolio](https://blvxx.github.io/web-development-portfolio/)**

[![FinTech QA](https://github.com/blvxx/portfolio/actions/workflows/fintech-qa-platform.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/fintech-qa-platform.yml)
[![API Automation](https://github.com/blvxx/portfolio/actions/workflows/api-automation.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/api-automation.yml)
[![Linux Support Lab](https://github.com/blvxx/portfolio/actions/workflows/support-engineering-lab.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/support-engineering-lab.yml)
[![Incident Operations](https://github.com/blvxx/portfolio/actions/workflows/incident-ops.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/incident-ops.yml)
[![Web Portfolio Validation](https://github.com/blvxx/web-development-portfolio/actions/workflows/portfolio-validation.yml/badge.svg)](https://github.com/blvxx/web-development-portfolio/actions/workflows/portfolio-validation.yml)

---

## Core skills

| Area | Tools / evidence |
|---|---|
| **Technical Support / Service Desk** | Troubleshooting workflow, incident triage, user-facing communication, diagnostics and runbooks |
| **Systems** | Linux, Windows fundamentals, systemd, journalctl, Nginx, DNS, TLS, networking concepts |
| **Application Support** | HTTP, REST, webhooks, logs, SQL diagnostics, incident investigation and RCA |
| **QA / API Testing** | pytest, Requests, Postman, JSON Schema, positive/negative tests, API contracts |
| **Automation** | Python, Playwright, scripting, test automation |
| **Data** | SQL, PostgreSQL, pandas, CTEs, window functions |
| **Tools & delivery** | Git, GitHub Actions, Docker, CI, technical documentation |

## Start here — support and troubleshooting

### [Linux Support Engineering Lab](https://github.com/blvxx/portfolio/tree/main/support-engineering-lab)
A hands-on troubleshooting lab with 10 incident playbooks and a Python log-triage CLI.
- systemd service failures, disk/inode pressure, Nginx 502/504, DNS, TLS, OOM, PostgreSQL connection pools, permissions and port conflicts.
- Severity-ranked findings with source-line evidence.
- Repeatable diagnostic steps, unit tests and CI report artifact.

### [Incident Investigation Lab — Payment Webhook Failure](https://github.com/blvxx/portfolio/tree/main/incident-lab)
A simulated incident investigation from initial symptoms through recovery.
- Log analysis and HTTP/webhook diagnostics.
- SQL checks for duplicate provider IDs and payment/order state mismatches.
- Timeline, impact, root cause analysis and recovery/reconciliation runbooks.

### [AI Support Triage Agent](https://github.com/blvxx/portfolio/tree/main/ai-support-triage-agent)
Support triage assistant built around retrieved runbook evidence.
- Structured severity, category, hypotheses, read-only checks and response draft.
- Evidence validation and escalation safeguards.
- Offline tests; live model evaluation requires an API key and is not claimed.

## QA and API testing

### [FinTech QA Engineering Platform](https://github.com/blvxx/portfolio/tree/main/fintech-qa-platform)
Payment/Ledger sandbox with API, integration and browser-level checks, PostgreSQL, Docker Compose, Allure and CI.

### [Python API Automation](https://github.com/blvxx/portfolio/tree/main/api-automation)
REST API automation with CRUD contracts, JSON Schema, negative scenarios, unit tests, bounded pagination and safe retry boundaries. CI: 62 passing tests on Python 3.10 and 3.12.

### [Checkout Regression QA](https://github.com/blvxx/portfolio/tree/main/qa-cases/checkout-regression/)
24 Playwright browser scenarios for cart, checkout, validation, stock/promotion boundaries and duplicate submissions.

### [Booking API QA](https://github.com/blvxx/portfolio/tree/main/qa-cases/api-contract-negative/)
31 pytest cases covering API contracts, pagination, validation, conflicts, idempotency and access control.

### [Playwright UI Automation Lab](https://github.com/blvxx/playwright-qa-lab)
8 authored automated scenarios and 17 documented manual test cases for a task-tracker UI.

## Python Backend and analytics

- **[Telegram Business Assistant](https://github.com/blvxx/portfolio/tree/main/telegram-business-assistant)** — asynchronous Python application with PostgreSQL, Redis, webhook profile, transactional outbox, idempotency, health checks and metrics. CI verifies service integration, PostgreSQL backup/restore, Prometheus rules and Docker build; the current profile is not publicly deployed.
- **[Customer Retention & Sales Analytics](https://blvxx.github.io/portfolio/customer-retention-analytics/)** — public dataset analysis, RFM segmentation, cohorts and dashboard.
- **[Subscription Revenue & Retention](https://blvxx.github.io/portfolio/subscription-revenue-analytics/)** — PostgreSQL BI model, MRR/ARR, GRR/NRR and data-quality checks.
- **[Support Operations Analytics](https://github.com/blvxx/portfolio/tree/main/support-operations-analytics)** — SLA, ticket backlog, priority mix and workload analysis with SQL.

## Frontend / Web Development

- **[Web Development Portfolio](https://blvxx.github.io/web-development-portfolio/)** — five responsive HTML/CSS/JavaScript concepts: business websites, studio/fitness/coffee concepts and a demo storefront. Chromium CI covers mobile overflow, keyboard navigation, filters, cart, interactive brief and form scenarios: **10 browser tests + 5 structural checks**. These are demo concepts, not paid client deliveries.

## How I approach incidents

1. Clarify scope, symptoms and user impact.
2. Check the simplest causes first and collect evidence.
3. Isolate whether the issue is client-side, network, application, dependency or access-related.
4. Apply a safe fix or escalate with useful findings.
5. Verify recovery and document what happened.

## Transparency

These are independent portfolio projects and labs. Incident and payment scenarios are simulated; the projects are not presented as commercial client deliveries or production employment. Each project documents its scope and limitations.

## Contact

- **Email:** [blvx8x@gmail.com](mailto:blvx8x@gmail.com)
- **Telegram:** [@blvlxx](https://t.me/blvlxx)

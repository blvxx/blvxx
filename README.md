# Artem Kalinin

## Python Automation & Application Engineering

Python · API Integrations · Workflow Automation · QA Engineering · Systems Reliability

I build and investigate software workflows with an emphasis on clear boundaries, predictable failure handling, automated verification and operational documentation.

**[Engineering portfolio](https://blvxx.github.io/portfolio/engineering/)** · **[GitHub repositories](https://github.com/blvxx?tab=repositories)** · **[Web development portfolio](https://blvxx.github.io/web-development-portfolio/)**

[![Telegram Business Assistant](https://github.com/blvxx/portfolio/actions/workflows/telegram-business-assistant.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/telegram-business-assistant.yml)
[![FinTech QA Platform](https://github.com/blvxx/portfolio/actions/workflows/fintech-qa-platform.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/fintech-qa-platform.yml)
[![Python API Automation](https://github.com/blvxx/portfolio/actions/workflows/api-automation.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/api-automation.yml)

---

## Engineering focus

| Area | Practical evidence |
|---|---|
| **Python application development** | Async Telegram application, validation, persistence, configuration and deployment |
| **API and workflow automation** | REST clients, request validation, retry boundaries, webhook investigation and integration tests |
| **Quality engineering** | pytest, Playwright, API contracts, negative scenarios, test strategy and CI |
| **Systems and incident analysis** | Linux troubleshooting, log triage, incident timelines, SQL reconciliation and recovery runbooks |
| **Data and SQL** | PostgreSQL, CTEs, window functions, data validation, cohort and revenue analysis |
| **Engineering delivery** | Git, GitHub Actions, Docker Compose, technical documentation and architecture decision records |

## Selected engineering projects

### 1. [Telegram Business Assistant](https://github.com/blvxx/portfolio/tree/main/telegram-business-assistant)

An independently developed and deployed Python Telegram bot MVP for collecting structured business enquiries.

- aiogram 3, asynchronous handlers, finite-state workflow and input validation.
- SQLite transactions, a typed application-service boundary and replay-safe lead creation keyed by Telegram chat/message identity.
- Transactional notification outbox with lease-token fencing, bounded retries and dead-letter state.
- Forward-only schema migrations, private-chat administrator access checks, Docker Compose hardening and CI quality gates.
- Architecture decision records, threat model, operations runbook and evidence-based engineering roadmap.

**Live demo:** [@blvlxxbot](https://t.me/blvlxxbot)

**Project status:** deployed portfolio MVP. Host persistence for the live deployment is not verified; the project is not represented as a production client system.

### 2. [FinTech QA Engineering Platform](https://github.com/blvxx/portfolio/tree/main/fintech-qa-platform)

A multi-service payment sandbox used to demonstrate API, integration and browser-level quality engineering.

- Payment and Ledger services with PostgreSQL persistence.
- pytest API/integration coverage and Playwright end-to-end flows.
- Docker Compose, Postman, Allure and GitHub Actions.
- Observability and a guarded local dependency-outage/recovery exercise.

**Stack:** Python · FastAPI · pytest · Playwright · PostgreSQL · Docker.

### 3. [Python API Automation](https://github.com/blvxx/portfolio/tree/main/api-automation)

A reusable REST API test suite with positive and negative scenarios.

- CRUD contract checks and JSON Schema validation.
- Explicit timeouts, bounded pagination and conservative retries for idempotent methods.
- Mocked unit tests, Postman collection and CI.

**Stack:** Python · requests · pytest · jsonschema · Postman.

### 4. [Linux Support Engineering Lab](https://github.com/blvxx/portfolio/tree/main/support-engineering-lab)

A reproducible troubleshooting lab with 10 incident playbooks and a Python log-triage CLI.

- systemd, Nginx, DNS, TLS, disk/inode, OOM and PostgreSQL connection scenarios.
- Severity-ranked findings with source-line evidence.
- Unit tests and CI-generated JSON reports.

### 5. [Incident Investigation Lab — Payment Webhook Failure](https://github.com/blvxx/portfolio/tree/main/incident-lab)

A simulated payment incident taken from initial symptoms through investigation and recovery.

- Python log analysis and HTTP/webhook diagnostics.
- SQL reconciliation for duplicate provider IDs and payment/order state mismatches.
- Incident timeline, RCA and recovery runbooks.

### 6. [Playwright UI Automation Lab](https://github.com/blvxx/playwright-qa-lab)

A small browser application with 8 authored Playwright scenarios and 17 documented manual test cases.

- Form validation, keyboard interaction, state changes and persistence across reload.
- Test execution report and bug report templates.
- GitHub Actions execution.

## Data and BI case studies

- [Customer Retention & Sales Analytics](https://blvxx.github.io/portfolio/customer-retention-analytics/) — public UCI Online Retail dataset, transaction cleaning, RFM segmentation, cohort retention and aggregate dashboard.
- [Subscription Revenue & Retention](https://blvxx.github.io/portfolio/subscription-revenue-analytics/) — PostgreSQL subscription lifecycle model, MRR/ARR, GRR/NRR and data-quality assertions.
- [Support Operations Analytics](https://github.com/blvxx/portfolio/tree/main/support-operations-analytics) — SQL analysis of SLA, backlog, priority mix and workload.

## How I approach engineering work

1. Clarify the requirement, constraints and expected behaviour.
2. Identify system boundaries, dependencies and failure modes.
3. Choose the simplest design that meets the requirements.
4. Verify behaviour with automated tests and reproducible checks.
5. Document operational constraints, trade-offs and recovery steps.

## Current engineering direction

The Telegram Business Assistant now has a framework-independent application service, selected handler and authorization tests, a transactional notification outbox with bounded retries and lease fencing, versioned SQLite migrations, and Ruff + pytest + Docker checks in CI. The next milestones are verifying persistent storage and backup/restore on the live host, completing full conversation/callback integration tests, adding operational metrics and alerts, and only then evaluating an AI workflow extension against a deterministic baseline.

The current project status and planned work are documented separately:
- [Architecture and current-state analysis](https://github.com/blvxx/portfolio/blob/main/telegram-business-assistant/docs/engineering/architecture.md)
- [Security threat model](https://github.com/blvxx/portfolio/blob/main/telegram-business-assistant/docs/engineering/security/threat-model.md)
- [Engineering roadmap](https://github.com/blvxx/portfolio/blob/main/telegram-business-assistant/docs/engineering/roadmap.md)

## Project transparency

The projects above are independent portfolio work. FinTech payment flows and incident records are simulated; the subscription analytics fixture is fictional; the customer-retention case uses the attributed public UCI Online Retail dataset. These projects are not presented as commercial client deliveries or employment history. Each repository documents its own scope and limitations.

## Contact

- **Email:** [blvx8x@gmail.com](mailto:blvx8x@gmail.com)
- **Telegram:** [@blvlxx](https://t.me/blvlxx)

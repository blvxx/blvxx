# Artem Kalinin

**QA Engineer · API Testing · Python Automation · Playwright**

I design and automate checks for REST APIs, browser workflows and service integrations. My independent QA portfolio focuses on risk-based test design, API contracts, negative and boundary scenarios, state verification, defect reporting and reproducible CI evidence.

**Target roles:** Junior QA Engineer · API Tester · QA Automation Engineer (Python)

**[QA portfolio — start here](https://github.com/blvxx/portfolio/blob/main/qa-portfolio.md)** · [Engineering portfolio](https://github.com/blvxx/portfolio) · [Email](mailto:blvx8x@gmail.com) · [Telegram](https://t.me/blvlxx)

[![Python API Automation](https://github.com/blvxx/portfolio/actions/workflows/api-automation.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/api-automation.yml)
[![Booking API QA](https://github.com/blvxx/portfolio/actions/workflows/qa-booking-api.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/qa-booking-api.yml)
[![Checkout UI Regression](https://github.com/blvxx/portfolio/actions/workflows/qa-checkout-regression.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/qa-checkout-regression.yml)
[![FinTech QA Platform](https://github.com/blvxx/portfolio/actions/workflows/fintech-qa-platform.yml/badge.svg)](https://github.com/blvxx/portfolio/actions/workflows/fintech-qa-platform.yml)
[![Playwright UI QA](https://github.com/blvxx/playwright-qa-lab/actions/workflows/playwright.yml/badge.svg)](https://github.com/blvxx/playwright-qa-lab/actions/workflows/playwright.yml)

## QA evidence at a glance

| Focus | Project evidence | What it demonstrates |
|---|---|---|
| **Python API testing** | [API Automation](https://github.com/blvxx/portfolio/tree/main/api-automation) — 62 tests; CI matrix on Python 3.10 and 3.12 | REST CRUD, JSON Schema, negative cases, pagination, timeout handling and safe retry boundaries |
| **API test design** | [Booking API QA](https://github.com/blvxx/portfolio/tree/main/qa-cases/api-contract-negative) — 31 tests; 100% statement coverage for two authored modules | Contracts, validation, access control, idempotency, booking invariants and traceability |
| **Web E2E** | [Checkout Regression](https://github.com/blvxx/portfolio/tree/main/qa-cases/checkout-regression) — 24 browser scenarios | Cart, pricing, promotions, stock, checkout validation, duplicate submission and responsive smoke |
| **Manual + UI automation** | [Playwright QA Lab](https://github.com/blvxx/playwright-qa-lab) — 11 E2E tests and 20 documented manual cases | Functional regression, accessibility, persistence, corrupted storage and defect reporting |
| **Integration testing** | [FinTech QA Platform](https://github.com/blvxx/portfolio/tree/main/fintech-qa-platform) | API/service integration, PostgreSQL, Docker Compose, ledger invariants and controlled failure/recovery checks |

## Selected projects

### 1. API Automation — Python / pytest
Reusable HTTP client and test suite for CRUD contracts, response schemas, parametrized positive and negative cases, pagination boundaries and transport resilience. Unit tests use mocks; local fault injection verifies safe retry behavior.

[Project README](https://github.com/blvxx/portfolio/tree/main/api-automation) · [Successful CI run — 23 Nov 2026](https://github.com/blvxx/portfolio/actions/runs/45102695248)

### 2. Booking API — Risk-Based Contract Testing
A fictional booking API with 31 automated tests covering validation, pagination, authorization, overlapping reservations, cancellation and idempotency. CI enforces 100% statement coverage for the authored `app.py` and `store.py` modules.

[Project README](https://github.com/blvxx/portfolio/tree/main/qa-cases/api-contract-negative) · [Test matrix](https://github.com/blvxx/portfolio/blob/main/qa-cases/api-contract-negative/test-matrix.md) · [Successful CI run — 22 Nov 2026](https://github.com/blvxx/portfolio/actions/runs/44993766677)

### 3. Checkout & Cart — Playwright / pytest
24 browser scenarios for a fictional storefront: cart and stock boundaries, price calculations, promotions, delivery changes, field validation and duplicate-submit protection. CI retains JUnit results, Playwright traces and failure screenshots.

[Project README](https://github.com/blvxx/portfolio/tree/main/qa-cases/checkout-regression) · [Test plan](https://github.com/blvxx/portfolio/blob/main/qa-cases/checkout-regression/test-plan.md) · [Successful CI run — 22 Nov 2026](https://github.com/blvxx/portfolio/actions/runs/44993763830)

### 4. Playwright UI Automation Lab
11 automated browser scenarios, 20 documented manual test cases, an execution report, responsive exploratory check and two accessibility findings fixed with regression coverage.

[Repository](https://github.com/blvxx/playwright-qa-lab) · [Test cases](https://github.com/blvxx/playwright-qa-lab/blob/main/docs/test-cases.md) · [Execution report and environment limitations](https://github.com/blvxx/playwright-qa-lab/blob/main/docs/test-execution-report.md) · [Successful CI run — 23 Nov 2026](https://github.com/blvxx/playwright-qa-lab/actions/runs/45155361776)

### 5. FinTech QA Engineering Platform
A fictional Payment/Ledger sandbox with pytest API and integration checks, PostgreSQL, Docker Compose, Playwright smoke flows, ledger invariants and a guarded dependency-outage/recovery drill.

[Project overview](https://github.com/blvxx/portfolio/blob/main/fintech-qa-platform/overview.html) · [Source and setup](https://github.com/blvxx/portfolio/tree/main/fintech-qa-platform) · [Successful CI run — 23 Nov 2026](https://github.com/blvxx/portfolio/actions/runs/45100258032)

## QA toolkit

**Languages and automation:** Python · pytest · requests · JavaScript · Playwright  
**API and data:** Postman · HTTP / REST · JSON · JSON Schema · SQL · PostgreSQL  
**Test engineering:** test plans · test cases · traceability · risk-based testing · positive / negative / boundary testing · regression · exploratory checks · defect reports  
**CI and environments:** GitHub Actions · Docker Compose · Allure · JUnit XML · Playwright traces

## How I work

1. Clarify expected behavior, constraints and business impact.
2. Identify high-risk paths, dependencies and failure modes.
3. Design positive, negative, boundary and state-transition checks.
4. Prepare isolated test data and reproducible setup.
5. Execute tests at API, integration and UI levels.
6. Record evidence, report reproducible defects and verify fixes.
7. Summarise coverage, limitations and remaining risk.

## Additional strength: Application Support

I also have portfolio evidence in Linux troubleshooting, log analysis, SQL diagnostics, incident investigation and recovery documentation — useful for QA roles close to support, integrations and production systems.

- [Linux Support Engineering Lab](https://github.com/blvxx/portfolio/tree/main/support-engineering-lab)
- [Incident Investigation Lab](https://github.com/blvxx/portfolio/tree/main/incident-lab)

## Transparency

These are independent practice projects and authored test targets, not commercial client deliveries or production employment. Payment, booking, checkout and incident scenarios are simulated. JSONPlaceholder simulates write operations. The Booking API uses an in-memory store and simplified test authentication. Checkout has no real payment or inventory backend. The Playwright manual report documents its isolated browser harness and limitations. Coverage percentages apply only to the named modules and metric; they do not imply complete branch, system or production coverage.

---

**Artem Kalinin** · [GitHub](https://github.com/blvxx) · [Email](mailto:blvx8x@gmail.com) · [Telegram](https://t.me/blvlxx)

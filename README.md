# Hi, I'm Rakesh K 👋

I build native iOS applications and practical AI systems with a focus on privacy, reliability, evidence, and maintainable architecture.

My portfolio demonstrates SwiftUI and Swift Concurrency, offline-first mobile design, agent security, responsible AI evaluation, FastAPI services, Docker, automated testing, and secure delivery pipelines.

## Featured projects

### Native iOS

#### [OutageKit](https://github.com/Talk2rakesh-1/outage-kit-ios)

An offline SwiftUI household supply tracker with user-selected stock targets and expiry dates.

- Validated, versioned JSON storage with atomic writes and iOS file protection
- Eight core unit tests; native simulator-SDK builds verified
- Search, editing, confirmed deletion, and explicit storage-failure handling
- Live simulator, device, and accessibility validation remain documented follow-ups

[![OutageKit CI](https://github.com/Talk2rakesh-1/outage-kit-ios/actions/workflows/ci.yml/badge.svg)](https://github.com/Talk2rakesh-1/outage-kit-ios/actions/workflows/ci.yml)

#### [PrivateMark](https://github.com/Talk2rakesh-1/private-mark-ios)

An on-device SwiftUI utility that reviews text for common sensitive-data patterns and creates a sanitized copy without sending content to a backend.

- Swift 6, SwiftUI, MVVM, protocol-driven dependency injection
- Deterministic email, phone, payment-card, and IPv4 detection
- Luhn and IP-range validation, accessibility, and privacy-by-design
- Five unit tests, native Xcode build, CI, and full-history secret scanning

[![PrivateMark CI](https://github.com/Talk2rakesh-1/private-mark-ios/actions/workflows/ci.yml/badge.svg)](https://github.com/Talk2rakesh-1/private-mark-ios/actions/workflows/ci.yml)

#### [Recall Ready](https://github.com/Talk2rakesh-1/recall-ready-ios)

An offline-capable SwiftUI app for official NHTSA vehicle safety-recall searches, saved vehicles, and cached results.

- SwiftUI, URLSession, actors, Codable, MVVM, and dependency injection
- Typed networking errors, retry behavior, atomic caching, and offline fallback
- Unit and UI tests with a verified simulator screenshot
- No API key, analytics SDK, advertising SDK, or third-party runtime dependency

[![Recall Ready CI](https://github.com/Talk2rakesh-1/recall-ready-ios/actions/workflows/ci.yml/badge.svg)](https://github.com/Talk2rakesh-1/recall-ready-ios/actions/workflows/ci.yml)

### Applied and Agentic AI

#### [QueueCompass](https://github.com/Talk2rakesh-1/queue-compass)

A local machine-learning CLI for human-reviewed support-ticket routing with explicit abstention.

- Multinomial Naive Bayes, word-level evidence, and bounded JSON inputs
- Eleven tests, synthetic evaluation, model card, and no runtime dependencies
- CI, full-history secret scanning, and dependency auditing
- Small synthetic results are regression checks, not production accuracy claims

[![QueueCompass CI](https://github.com/Talk2rakesh-1/queue-compass/actions/workflows/ci.yml/badge.svg)](https://github.com/Talk2rakesh-1/queue-compass/actions/workflows/ci.yml)

#### [ChangeLens](https://github.com/Talk2rakesh-1/policy-change-lens)

A local-first document intelligence API that identifies section-level changes and returns evidence-linked findings with measurable citation coverage.

- Python, FastAPI, Pydantic, local retrieval, evaluation, and observability
- Deterministic added, removed, and modified change classification
- Responsible-AI guardrails that treat document instructions as untrusted data
- Seven unit/API tests, 99% statement coverage, Docker, CI, and secret scanning

[![ChangeLens CI](https://github.com/Talk2rakesh-1/policy-change-lens/actions/workflows/ci.yml/badge.svg)](https://github.com/Talk2rakesh-1/policy-change-lens/actions/workflows/ci.yml)

#### [Agent Guard Eval](https://github.com/Talk2rakesh-1/agent-guard-eval)

A local-first prompt-injection evaluation harness and least-privilege policy gate for tool-using AI agents.

- FastAPI, Pydantic, pytest, Ruff, mypy, Docker, and structured audit logs
- Deterministic attack fixtures and measurable evaluation output
- Explicit tool permissions, input validation, and responsible-AI boundaries
- No paid API or external model required

[![Agent Guard Eval CI](https://github.com/Talk2rakesh-1/agent-guard-eval/actions/workflows/ci.yml/badge.svg)](https://github.com/Talk2rakesh-1/agent-guard-eval/actions/workflows/ci.yml)

## Technical focus

| Area | Skills |
|---|---|
| iOS | Swift, SwiftUI, Swift Concurrency, MVVM, protocol-oriented design, URLSession, local persistence, accessibility, XCTest and Swift Testing |
| Applied AI | Retrieval, evaluation, guardrails, evidence and citation design, prompt-injection defense, responsible AI |
| Backend | Python, FastAPI, Pydantic, REST APIs, validation, structured logging |
| Delivery | Git, GitHub Actions, Docker, Dependabot, secret scanning, automated linting and tests |

## Engineering principles

- Build functional, testable MVPs instead of empty demonstrations.
- Keep secrets, personal data, and paid-service requirements out of portfolio projects.
- Prefer local or open implementations with explicit trust boundaries.
- Attach evidence to AI-generated or AI-adjacent conclusions.
- Document limitations and unverified behavior honestly.

## Current direction

I am continuing to expand this portfolio with independent native iOS and applied-AI projects that explore new platform capabilities and industry problems without repeating previous work.

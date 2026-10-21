# Alejandro Aguirre Luna

**Senior Software Engineer & AI Engineer** · Hoorn, the Netherlands · 15+ years in software

I build Java and Spring Boot backends, TypeScript and Node.js services, and LLM features that are tested, evaluated and allowed to fail safely. I started as a Java developer in 2011, worked as a senior backend engineer on banking platforms, spent several years leading delivery as a Scrum Master and Release Train Engineer, and now work freelance through my own company.

[Website](https://alejandrolunatech.com/) · [LinkedIn](https://www.linkedin.com/in/alejandro-aguirre-luna-10435596/) · [Book an intro call](https://cal.com/alejandrolunatech/intro-call)

## How I build

**Deterministic core, probabilistic edge.** Money, state, permissions and deadlines live in plain, tested code. A language model works at the edge, where the input is messy human text, and everything it returns is validated before the system acts on it. When the model is slow, wrong or unavailable, the system falls back to rules or a human review queue.

I use AI coding agents (Claude Code, GitHub Copilot) as implementers. I own the design, review every pull request, and treat CI, tests and evals as the gate.

## Start here

| Repository | What it shows |
| --- | --- |
| [payment-disputes-spring-boot](https://github.com/alejandrolunatech/payment-disputes-spring-boot) | A Spring Boot 4 service with a hexagonal core: an LLM reads the customer's complaint and proposes a reason, and tested code decides. Idempotency keys, optimistic locking, PII masking, a circuit breaker with a rules fallback, and an eval harness |
| [invoice-intake-api](https://github.com/alejandrolunatech/invoice-intake-api) | A TypeScript, Express 5 and Zod API: an LLM extracts invoice fields, and plain code verifies the IBAN and VAT checksums, the KvK number and the sums in integer cents before anything is paid |
| [modern-java-design-patterns](https://github.com/alejandrolunatech/modern-java-design-patterns) | The classic GoF patterns rewritten with records, sealed types and pattern matching, and the same patterns used to keep an LLM in check |
| [ai-engineering-labs](https://github.com/alejandrolunatech/ai-engineering-labs) | Production-minded AI engineering: a bounded PR-review agent with evals, a zero-trust MCP gateway with OPA policies, and ChangeBrief, an LLM service with cost, latency and abuse controls |

## Stack

- **Backend:** Java, Spring Boot, Spring MVC, JPA and Hibernate, REST API design, PostgreSQL, SQL and PL/SQL
- **TypeScript:** Node.js, Express, Next.js, Zod
- **LLM engineering:** structured output, evals, guardrails, cost and latency tracking, MCP
- **Delivery:** Docker, Kubernetes, CI/CD with GitHub Actions and Jenkins, TDD and BDD
- **Ways of working:** Scrum (PSM II), SAFe (as a Release Train Engineer), remote teams across Europe and the Americas

English and Spanish.

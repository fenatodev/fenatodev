# Fernando Nascimento

**Independent Software Engineer · AI Coding & Agent Evaluation · Code Review · Technical Automation**

I build and evaluate software systems with a strong focus on **AI-assisted development, coding agents, debugging, testing, secure automation, and local-first LLM workflows**.

My work is centered on turning ambiguous technical problems into reproducible results: inspect the system, identify failure modes, define boundaries, implement the smallest reliable change, and validate it with tests and evidence.

## Professional focus

- AI coding evaluation and code review
- Coding-agent and tool-use evaluation
- Debugging and failure reproduction
- Test design and regression coverage
- Backend systems, APIs, and integrations
- LLM applications and agentic workflows
- Local-first AI infrastructure
- Security-conscious automation

## Selected projects

### [lai-harness](https://github.com/fenatodev/lai-harness)

Local-first, auditable coding harness for OpenAI-compatible local LLM servers.

The project explores practical engineering problems around coding agents: deterministic repository context, bounded tool use, policy decisions, safe workspaces, review/promotion flows, sandboxed execution, observability, validation gates, and explicit authority boundaries.

**Signals:** Python · testing · code review · agent tooling · sandboxing · security · local LLMs · developer tooling

### [ai-coding-evaluation](https://github.com/fenatodev/ai-coding-evaluation)

Executable portfolio for AI coding evaluation, code review, debugging, test design, and agent assessment.

It contains synthetic failure cases with intentionally buggy implementations, minimal fixes, reproducible tests, review reports, a scoring rubric, and CI. Cases cover cross-tenant authorization, concurrency, semantic regression, coding-agent authority traces, and multi-file PR review with idempotency and failure-path analysis.

**Signals:** AI coding evaluation · debugging · code review · adversarial testing · concurrency · security · benchmarks

### [lai-gateway](https://github.com/fenatodev/lai-gateway)

Companion gateway and local workbench for the LAI harness.

It separates UI/client channels from execution authority and experiments with explicit authorization, local model routing, controlled integrations, mobile access, and operator-facing workflows.

**Signals:** Python · APIs · system integration · authorization design · agent UX · local AI

### [business-automation](https://github.com/fenatodev/business-automation)

Reusable backend foundation for business automation, CRM, AI integrations, and operational workflows.

The repository is being developed from real operational use cases while keeping the core configurable and separating product logic from external systems and automation engines.

**Signals:** Python · FastAPI · APIs · data modeling · integrations · automation · tests

### [interpreter-workstation](https://github.com/fenatodev/interpreter-workstation)

Public fork used for hands-on experimentation and integration work around Open Interpreter Workstation.

This is **not an original project of mine**. I use the fork to study, test, adapt, and validate workstation/agent behavior while preserving upstream attribution.

## Engineering approach

I prefer evidence over assumptions:

```text
problem
→ reproduce
→ inspect
→ isolate
→ implement
→ test
→ review
→ measure
```

For AI-generated code, the same principle applies: a plausible answer is not enough. I look for hidden failure modes, incorrect assumptions, missing tests, unsafe authority boundaries, regressions, and behavior that can be demonstrated rather than merely described.

## Core stack

**Languages:** Python · JavaScript · TypeScript  
**Backend:** FastAPI · Node.js · REST APIs  
**Engineering:** Git · GitHub · Linux · Docker · CI/testing · debugging  
**AI:** LLM applications · coding agents · tool calling · local models · evaluation workflows  
**Security:** application security · API security · least-authority design · secrets hygiene

## Current direction

I am building a public body of work around:

- AI Coding Evaluation
- Code Review
- Agent Evaluation
- Software Testing
- Technical QA
- AI/LLM Engineering

The goal is to make the repositories themselves demonstrate how I investigate, validate, review, and ship technical work.

## Contact

- LinkedIn: [linkedin.com/in/fenatodev](https://www.linkedin.com/in/fenatodev/)
- GitHub: [github.com/fenatodev](https://github.com/fenatodev)

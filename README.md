# Filip Nowak

**AI Implementation Specialist** in Harlow, Essex. Active UK SC clearance.

I build AI systems for document-heavy, regulated work: document intake and extraction, checks against official sources, and a human sign-off wherever a mistake would matter. Before this I spent 20 months on the Home Office passport service at XBP Europe, processing legally sensitive documents to strict accuracy standards, so I know where documents and data go wrong.

I build with AI coding agents (Claude Code, Codex, Cursor). I define what each system must do and how to check it, direct the agents, review the output and run what's live.

---

## Featured projects

### [MorphIQ](https://github.com/swsOG/MorphIQ): document AI for letting-agency compliance

Scans and uploads go through OCR, Gemini classifies each document and extracts its fields, a person verifies the result, and verified records feed a tenant-scoped portal that tracks every certificate as valid, expiring, expired or missing.

- CI-gated offline evaluation on a 132-case synthetic golden set across 6 document types
- Pre-launch security review and hardening: fail-closed tenant isolation, login lockout, weak-secret boot guard, each covered by regression tests
- Document types and compliance rules are configuration, not code
- 102 tests, Playwright smoke test, and a synthetic demo you can run in two commands

`Python` `Flask` `SQLite` `Gemini` `OCR` `pytest` `Playwright` · Pre-launch, paused June 2026

### [Local Hospitality Lead Engine](https://github.com/swsOG/lead-engine-demo): lead research with human approval

Finds and researches local businesses, ranks them, drafts outreach through a Gemini, OpenAI and Anthropic fallback chain, and holds every lead in an approval queue. Rejected, do-not-contact and unverified contacts are blocked from export or outreach tools.

`Python` `Flask` `SQLite` `LLM APIs` `SerpAPI` `Tavily` `Hunter` `Instantly` · Working prototype, 48 tests

### [AI Intel Pipeline](https://github.com/swsOG/ai-intel-pipeline): ranked AI news briefings

Pulls 15 feeds, uses Gemini to assess each item, applies local trust and freshness rules and delivers a short ranked digest by email and Telegram. Its July 2026 weekly runs cut 145 to 175 items down to 15 picks.

`Python` `Flask` `Gemini` `Telegram Bot API` `SMTP` · Ran July 2026, paused, 66 tests

---

## Also building (private)

- **Mara**, my personal AI agent on my own Ubuntu server, built on Nous Research's Hermes Agent: Telegram and desktop access, a governed knowledge base that keeps each project's facts separate, and scheduled jobs including a daily job search that only recommends roles verified on the employer's own site.
- **An operations dashboard** for the agent (FastAPI, React, TypeScript) with approval-gated drafts, covered by 394 tests.
- **The back office for [Plain Welcome Studio](https://plainwelcomestudio.co.uk)**, my small web studio for local businesses: a website review generator, a lead desk and inbox alerts.

---

## Looking for

AI implementation and automation roles, especially in regulated and public-sector work. Hybrid around London, Essex and Hertfordshire.

[LinkedIn](https://www.linkedin.com/in/filip-nowak) · [GitHub](https://github.com/swsOG)

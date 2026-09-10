---
title: "TarrotCardWebSite — Coding Standards"
application_id: "tarrotcardwebsite"
repository: "R3almEcosystem/TarrotCardWebSite"
application_version: "0.1.0"
document_status: "Baseline"
last_reviewed: "2026-09-10"
next_review: "2026-12-10"
---

# Coding Standards

> TarrotCardWebSite · Platform · Pre-Alpha

TarrotCardWebSite is cataloged as a Platform application focused on interactive card-reading experiences.

> **Baseline notice:** This document defines the expected operating standard. It does not claim that a control, integration, model, or certification is already implemented; verify the code, configuration, and production evidence before release.

## Project standard

Follow the formatter, linter, compiler, and test conventions committed in the repository.

## Required practices

- Validate untrusted data at every system boundary.
- Make authorization checks server-side and close to the protected operation.
- Keep functions cohesive; name domain states and transitions explicitly.
- Handle expected failures as typed or structured outcomes.
- Redact secrets, tokens, personal data, and raw content from logs.
- Add tests for happy paths, invalid input, authorization, retries, and partial failure.
- Keep configuration environment-specific and fail fast when required values are absent.
- Prefer maintained dependencies; record justification for privileged or high-risk packages.

## Naming and documentation

Names should express domain meaning rather than UI position or implementation accident. Public contracts, complex invariants, security-sensitive logic, migrations, and surprising tradeoffs require documentation. Comments explain why, not what syntax already states.

## Quality gate

The repository's formatter, linter, compiler or type checker, tests, security checks, and build must pass. Temporary suppression requires an owner, reason, expiry condition, and linked follow-up.

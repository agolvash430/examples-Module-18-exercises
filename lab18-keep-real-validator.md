# Lab 18 — When to Keep Real Validator

## Mock repo?
Yes — the repository is mocked because persistence is not under test. The repo only needs to simulate “exists / does not exist” and return canned entities so the service logic can run without touching storage.

## Real validator?
Yes — keep the real validator because validation *is* part of the domain rules being exercised. Using the real validator ensures that illegal state, malformed fields, and rule violations are caught exactly as they would be in production.

## Mock notifier?
Yes — the notifier is mocked because external side‑effects (emails, events, messages) are not part of the service’s correctness. Tests should assert that the notifier was *called*, not that it actually delivers anything.

## Rule
Keep real components only when they enforce domain invariants. Mock everything that represents infrastructure, persistence, or side‑effects. The service test must prove business rules, not IO.

## Scope
Pre-lab only.

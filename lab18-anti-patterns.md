# Lab 18 — Mockito Anti-Patterns

| Anti-pattern | Better |
| --- | --- |
| Mock the SUT | Mock collaborators only |
| Unnecessary stubbing | Stub only what the service actually calls |
| verifyNoMoreInteractions always | Use only when the interaction surface truly matters |

## AI reject rule
Reject any suggestion that mocks `CustomerService` while testing `CustomerService`. Always keep the SUT real and use fixtures like Ravi, Amina, and CUS‑9999 as appropriate.

## Scope
Pre-lab only.

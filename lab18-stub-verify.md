# Lab 18 — Stub vs Verify

## Stub (arrange)
Provide canned responses from collaborators so the service can run its logic without depending on real behavior. Stubbing sets up “what the collaborator returns” to drive the service down the intended path.

## Verify (assert collaboration)
Check that the service called the collaborator with the correct method, correct arguments, and correct number of invocations. Verification asserts “how the service interacted,” not what the collaborator returned.

## One sentence — both roles
Stubs shape the path the service takes; verifies prove the service actually performed the expected collaboration.

## Scope
Pre-lab only.

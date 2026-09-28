
# Lab 18 — ArgumentCaptor Preview

## Declare
Instantiate `ArgumentCaptor<Customer>` to capture the exact object passed into the repository.

## Verify + capture
Call `verify(repo).save(captor.capture())` to both assert the collaboration and retrieve the saved `Customer`.

## Assert
Check that `captor.getValue().getStatus()` equals `ACTIVE`, confirming Ravi was activated before persistence.

## Scope
Pre-lab only.

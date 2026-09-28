# Lab 18 — Fill Activate Interaction Sequence TODOs

1) stub findById(CUS-1002) → ravi PROSPECT
2) call service.activate(CUS-1002)
3) verify repo.save(customer)
4) verify notifier.notifyActivated(customer) // if present
5) assert status ACTIVE
6) ArgumentCaptor status field ACTIVE

## Captor sentence
The captor proves that the `Customer` passed to `repo.save(...)` already carried the `ACTIVE` status.

## Scope
Pre-lab only.

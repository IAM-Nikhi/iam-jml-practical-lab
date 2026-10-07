# IAM JML Practical Lab

Hands-on Joiner-Mover-Leaver lab covering HR triggers, identity correlation, birthright access, Active Directory / Entra provisioning, mover access recalculation, termination, disconnected applications and reconciliation.

## Scenario
Nina Patel starts in Finance, moves to Treasury, then terminates.

## Joiner
1. HR record received
2. Identity correlated
3. AD / Entra account created
4. Birthright access evaluated
5. Baseline access provisioned
6. Optional access uses request/approval
7. Target state reconciled

## Mover
Remove Finance role access, add Treasury role access, retain enterprise baseline access, review manually granted access and check SoD conflicts.

## Leaver
Disable accounts, remove groups and application access, validate disconnected apps, reconcile target state and retain audit evidence.

See `data/` for practical source and expected-state files.

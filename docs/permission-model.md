# Permission Model

ATGF separates capability from authority.

## Observer

Can:
- read
- analyze
- report

Cannot:
- modify systems

## Worker

Can:
- modify sandbox environments
- run tests
- create artifacts

Cannot:
- deploy production
- access secrets

## Operator

High-impact actions require explicit approval and audit records.
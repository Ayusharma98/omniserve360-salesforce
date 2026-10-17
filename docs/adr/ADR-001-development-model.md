# ADR-001: Development Model

## Status

Accepted

## Decision

OmniServe360 will use a source-driven Salesforce DX development model
with Git as the source-control system.

Development will use scratch organizations where Dev Hub access is
available.

## Repository

omniserve360-salesforce

## Branch Strategy

main
  ↓
develop
  ↓
feature branches

## Reason

This provides:

- Version control
- Code review
- Traceability
- CI/CD readiness
- Easy rollback
- Parallel development
- Deployment automation

## Consequences

Developers must commit metadata changes to Git and should avoid
treating a Salesforce org as the permanent source of truth.
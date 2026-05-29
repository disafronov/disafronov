# Engineering Principles

## Constraints

- Contracts must be explicit and enforceable
- Configuration is part of the system contract
- Operational behavior must be observable

## System Properties

- Portability is a system property
- Observability is architecture, not tooling
- Schemas are operational artifacts
- Configuration is validated before execution

## Operational Assumptions

- Applications should not depend on reading their own runtime state
- Integration boundaries must be explicit
- State minimization is preferred over state synchronization
- Invalid configuration must fail fast

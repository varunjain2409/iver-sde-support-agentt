# Architecture - iver-sde-support-agentt

## Overview

An experimental iteration of the SDE support agent - exploring intent classification, grounded reply drafting and escalation logic.

## Layers

| Layer          | Responsibility                                |
|----------------|-----------------------------------------------|
| Presentation   | UI / CLI entry points                         |
| Application    | Orchestration and use-case handling            |
| Domain         | Core logic and data models                     |
| Infrastructure | External services, storage and configuration   |

## Design Principles

1. Keep domain logic free of framework dependencies.
2. Externalise configuration - never hard-code secrets.
3. Test every layer independently.

## Development Workflow

1. Branch from the default branch.
2. Implement and test the change locally.
3. Open a pull request describing the change.

## License

MIT - see [LICENSE](../LICENSE).
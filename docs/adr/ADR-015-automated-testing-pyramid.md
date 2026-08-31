## ADR 015: Automated Testing Strategy

### Status
Accepted

### Context
Fast feedback is needed in CI/CD without requiring slow emulator spin-ups.

### Decision
Implement pure JVM unit tests for all domain calculation and serialization logic.

### Consequences
- Sub-minute CI test execution
- High test coverage on critical financial math

## ADR 017: Functional Result Wrapping

### Status
Accepted

### Context
Database and file operations can encounter unexpected I/O exceptions.

### Decision
Wrap repository operations in Kotlin Result<T> or custom DomainResult.

### Consequences
- No unhandled runtime crashes
- User-friendly error messages in UI

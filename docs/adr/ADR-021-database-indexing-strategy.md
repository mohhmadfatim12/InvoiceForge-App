## ADR 021: Database Indexing Strategy

### Status
Accepted

### Context
Invoice queries by client ID and issue date must remain fast as records grow.

### Decision
Annotate Room entities with indices on clientId, issueDate, and status.

### Consequences
- O(log N) query performance
- Instant dashboard aggregation

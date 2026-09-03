## ADR 024: Cascade Deletion for Data Hygiene

### Status
Accepted

### Context
Deleting a client must cleanly handle associated historical invoices.

### Decision
Support either cascade deletion with warning or soft-archive flag.

### Consequences
- Clean database hygiene
- Prevention of orphan invoice item records

## ADR 022: Payment Status State Machine

### Status
Accepted

### Context
Invoice statuses (Draft -> Sent -> Partially Paid -> Paid -> Overdue) require strict rules.

### Decision
Calculate status dynamically based on total amount, paid balance, and due date.

### Consequences
- Elimination of stale status flags
- Automatic overdue notifications

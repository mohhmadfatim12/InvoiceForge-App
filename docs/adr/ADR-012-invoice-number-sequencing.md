## ADR 012: Auto-Incrementing Invoice Numbering

### Status
Accepted

### Context
Tax authorities mandate sequential, non-duplicated invoice numbers.

### Decision
Combine configurable prefix (e.g. 'INV-') with zero-padded sequence numbers derived from database max records.

### Consequences
- Compliance with statutory audit rules
- User flexibility to reset or change prefix

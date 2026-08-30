## ADR 010: JSON Backup Validation

### Status
Accepted

### Context
Users need to safely backup and restore business records without data corruption.

### Decision
Backups are serialized as human-readable JSON accompanied by schema versioning and record counts.

### Consequences
- Cross-device portability
- Safeguards against schema mismatch

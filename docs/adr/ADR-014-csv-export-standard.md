## ADR 014: RFC 4180 Compliant CSV Export

### Status
Accepted

### Context
Accountants and bookkeeping software (Excel, QuickBooks) require clean CSV tables.

### Decision
All string fields with commas or quotes are escaped according to RFC 4180.

### Consequences
- Seamless spreadsheet imports
- No column shifting on special characters

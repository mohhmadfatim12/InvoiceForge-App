## ADR 001: Room Persistence Library

### Status
Accepted

### Context
InvoiceForge requires a robust, 100% offline relational database for invoices, clients, items, and business profiles.

### Decision
We choose Room over raw SQLite and SQLDelight due to first-class Android Jetpack support, compile-time SQL verification, and seamless Kotlin Coroutines/Flow integration.

### Consequences
- Strong compile-time type safety
- Automatic schema migration support
- Minimal boilerplate with DAOs

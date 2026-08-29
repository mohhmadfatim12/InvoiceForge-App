## ADR 007: Clean Architecture Layering

### Status
Accepted

### Context
Maintainability requires decoupling business rules from Android framework components.

### Decision
Separate code into domain (pure Kotlin calculations), data (Room entities, DAOs, repositories), and presentation (Compose UI).

### Consequences
- Independent testability of calculations
- Swappable data sources

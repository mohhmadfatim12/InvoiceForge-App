## ADR 025: Lightweight ViewModel Provider Factories

### Status
Accepted

### Context
Avoid heavy reflection-based DI libraries like Dagger/Hilt for small offline apps.

### Decision
Use manual AppContainer injection with viewModelFactory DSL.

### Consequences
- Faster compilation times
- Zero reflection runtime overhead

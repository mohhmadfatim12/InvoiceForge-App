## ADR 008: Jetpack DataStore for Settings

### Status
Accepted

### Context
SharedPreferences is legacy and lacks coroutine safety.

### Decision
Use Preferences DataStore for app theme, default currency, and numbering prefix settings.

### Consequences
- Asynchronous, non-blocking I/O
- Coroutine Flow API

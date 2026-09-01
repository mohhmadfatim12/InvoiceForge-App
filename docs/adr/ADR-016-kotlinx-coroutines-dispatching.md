## ADR 016: Coroutine Dispatcher Injection

### Status
Accepted

### Context
Hardcoded Dispatchers.IO complicates unit testing.

### Decision
Inject CoroutineDispatcher via constructor parameters or AppContainer.

### Consequences
- Deterministic test execution with TestDispatcher
- Structured concurrency guarantee

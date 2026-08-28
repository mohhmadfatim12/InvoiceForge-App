## ADR 006: Unidirectional Data Flow (UDF)

### Status
Accepted

### Context
Complex invoice editing flows with line items require predictable state transitions.

### Decision
ViewModels expose StateFlow<UiState> and handle UI events sequentially.

### Consequences
- Clear state separation
- Easy unit testing of ViewModel state streams

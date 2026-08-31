## ADR 013: Material 3 Dynamic Color Support

### Status
Accepted

### Context
Deliver native visual polish matching user system theme.

### Decision
Use dynamicLightColorScheme and dynamicDarkColorScheme when SDK >= 31, falling back to brand navy/cyan palette.

### Consequences
- Modern Android ecosystem feel
- Automatic dark mode compatibility

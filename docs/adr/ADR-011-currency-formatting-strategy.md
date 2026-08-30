## ADR 011: Currency Formatting Strategy

### Status
Accepted

### Context
Global users require localized symbols and decimal separators ($1,234.56 vs 1.234,56 €).

### Decision
Combine ISO currency codes with java.text.NumberFormat and custom symbol overrides.

### Consequences
- International compliance
- User-customizable decimal precision

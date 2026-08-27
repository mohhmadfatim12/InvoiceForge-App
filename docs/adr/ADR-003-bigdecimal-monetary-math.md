## ADR 003: BigDecimal for Financial Math

### Status
Accepted

### Context
Floating point primitives (Double/Float) suffer from binary precision issues during multi-item invoice summing, tax computation, and currency discounts.

### Decision
All currency values, item prices, discounts, tax rates, and totals must strictly use java.math.BigDecimal with explicit RoundingMode.HALF_UP.

### Consequences
- 100% accurate financial accounting
- Zero penny-rounding errors

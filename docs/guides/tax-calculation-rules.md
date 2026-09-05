# Tax Calculation Rules

### Precision
All calculations use `BigDecimal` with 4 decimal places during intermediate steps and rounded to 2 places for display.

### Formula
`Tax = ItemTotal * (TaxRate / 100)`

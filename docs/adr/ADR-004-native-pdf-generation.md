## ADR 004: Native Android PDF Generation

### Status
Accepted

### Context
Users need instant PDF invoices without relying on cloud services or bloated external binary libraries (e.g. iText commercial licenses).

### Decision
Implement custom vector canvas drawing using Android's native android.graphics.pdf.PdfDocument.

### Consequences
- Zero external network calls
- 100% privacy and offline operation
- Ultra-small APK footprint

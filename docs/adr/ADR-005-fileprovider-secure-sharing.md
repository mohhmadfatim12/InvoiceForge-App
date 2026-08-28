## ADR 005: FileProvider for Scoped Document Sharing

### Status
Accepted

### Context
Invoices and backup files must be shared via WhatsApp, Email, and Cloud Drives without granting broad storage permissions.

### Decision
Use androidx.core.content.FileProvider with cache and files paths.

### Consequences
- Full compliance with Android 11+ scoped storage
- Secure URI grant permissions

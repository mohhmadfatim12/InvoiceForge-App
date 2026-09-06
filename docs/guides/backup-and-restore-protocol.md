# Backup and Restore Protocol

### Backup Format
Encodes business profile, client directory, and all invoices into a single JSON file with metadata header containing:
- `version`: Database schema version
- `exportDate`: ISO-8601 timestamp
- `recordCount`: Total records verification count

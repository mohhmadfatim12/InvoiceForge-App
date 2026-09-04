# Architecture Overview

InvoiceForge follows an offline-first, clean architectural model:

1. **Presentation Layer:** Jetpack Compose, Material 3, ViewModels
2. **Domain Layer:** Pure Kotlin calculation engines, business entities
3. **Data Layer:** Room SQLite Database, DataStore Preferences, Repositories

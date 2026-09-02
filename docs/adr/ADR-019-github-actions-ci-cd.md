## ADR 019: GitHub Actions Cloud CI/CD

### Status
Accepted

### Context
Developers building from mobile/Termux need reliable cloud compilation of Android binaries.

### Decision
Configure automated workflow on ubuntu-latest with JDK 17 and Gradle caching.

### Consequences
- 1-minute automated APK builds
- Automated test gate before APK release

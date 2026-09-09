# Performance Tuning

- Use `@Immutable` and `@Stable` annotations on domain models
- Avoid allocating new objects inside `@Composable` drawing loops
- Use `derivedStateOf` for calculated UI flags

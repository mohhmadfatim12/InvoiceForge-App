## ADR 018: Multi-Layer Adaptive App Icons

### Status
Accepted

### Context
Android launchers require separate background and foreground vector layers.

### Decision
Provide ic_launcher_background.xml and ic_launcher_foreground.xml with 108dp viewport.

### Consequences
- Parallax launcher effects
- Perfect icon masking across all OEM skins

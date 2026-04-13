```md
# Architecture Overview

## High-level modules

### app
Owns startup, main loop, update, render, and shutdown.

### platform
Handles window creation and platform-facing integration through GLFW.

### renderer
Owns Vulkan setup and rendering responsibilities.

### simulation
Owns particle state, emitter behavior, and update logic.

### presets
Stores reusable emitter configurations.

### util
Common helpers such as logging, timing, and math utilities.

## Design goals
- Keep simulation and rendering responsibilities separate
- Keep changes small and issue-scoped
- Preserve cross-platform support for Windows and Linux
- Prefer clear incremental milestones over large refactors
```

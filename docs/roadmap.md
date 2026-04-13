```md
# Roadmap

## Phase 0 - Project Bootstrap
- Create repository structure
- Add CMake scaffold
- Add Windows and Linux build notes
- Add GLFW and Vulkan dependency plan

## Phase 1 - App Skeleton
- Create main loop
- Create window through GLFW
- Add logging and timing utilities
- Add clean shutdown path

## Phase 2 - Vulkan Base
- Create Vulkan instance
- Select physical device
- Create logical device
- Create swapchain
- Add render pass scaffold
- Add frame synchronization

## Phase 3 - Rendering Baseline
- Render clear color frame
- Render test triangle
- Add camera utility
- Add simple particle draw path

## Phase 4 - Particle Simulation
- Add particle data structure
- Add fixed-size particle pool
- Add spawn/update/despawn logic
- Add CPU-to-GPU upload path

## Phase 5 - Emitters and Presets
- Add fountain preset
- Add explosion preset
- Add smoke preset
- Add preset switching

## Phase 6 - Tooling
- Add FPS counter
- Add particle stats
- Add debug controls
- Add screenshots or demo captures

## Phase 7 - Advanced
- Add multithreaded particle update
- Benchmark large particle counts
- Prototype GPU compute particle path
```

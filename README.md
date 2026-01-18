# Desktop Postflop

**Desktop Postflop** is a free, open-source GTO solver for Texas hold'em poker.

 # Rounding Solver (Desktop)

 A native desktop front-end and packaging for the postflop solver engine.

 This repository bundles the UI and Tauri wrapper around the solver engine. The core solver engine is included as a Rust dependency; recent updates improved rounding and numerical stability in the solver and reduced memory overhead in common workloads.

 If you only need the pure solver library, see the engine repository used by this project.
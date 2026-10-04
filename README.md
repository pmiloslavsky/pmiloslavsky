# Philip Miloslavsky

Interactive simulations, visualizations and algorithm experiments, mostly in C++ and the browser. Several are rebuilt or extended with AI-assisted development.

## Live demos

| Project | What it is |
|---|---|
| **[Rough-In Plumbing Lab](https://pmiloslavsky.github.io/plumbinglab/)** · [code](https://github.com/pmiloslavsky/plumbinglab) | A plumbing and heating simulator in one HTML file. Lay out supply, drain and vent piping in a house cutaway, turn the water on, and a built-in inspector checks it against the 2021 IRC. A separate Boiler lab installs an oil boiler with four zones and an indirect water heater. |
| **[Strange Attractor Visualizer](https://pmiloslavsky.github.io/strange_attractor_visualizer/)** · [code](https://github.com/pmiloslavsky/strange_attractor_visualizer) | Real-time 3D strange attractors in the browser: thousands of particles with glowing trails across nine systems (Lorenz, Rössler, Chua, Newton–Leipnik and more). Built with Vite, TypeScript and Three.js. |

## Repositories

### [aidemo](https://github.com/pmiloslavsky/aidemo)
AI-assisted demo code. It currently holds **fractals**, a C++/SFML/TGUI/CUDA fractal explorer (Mandelbrot, Julia, Newton, Nova, Buddhabrot and more). It renders on every CPU core and on an NVIDIA GPU when one is present, and ships as a single executable for Windows and Linux.

### [demo](https://github.com/pmiloslavsky/demo)
The original collection of demonstration programs, mostly C++:
- **fractals**: the threaded, CUDA-accelerated fractal explorer that `aidemo/fractals` was ported from
- **ode_simulation**: 3D particle-and-trail simulation of strange attractors (SFML/TGUI), the ancestor of the web visualizer
- **hex**: the game of Hex with a threaded Monte Carlo player
- **astar**: two-sided Dijkstra and A* on real US highway data, with KML output for Google Maps
- **parallel_algorithms**: C++17 STL `sort`, `reduce` and `for_each` under each execution policy, plus what makes code unparallelizable
- **max_connected_color_count** and **maximum_path_sum**: algorithm puzzles (union-find flood fill, binary-tree path sums)
- **ssl_example_qat**: a minimal OpenSSL client/server example

### [plumbinglab](https://github.com/pmiloslavsky/plumbinglab)
The source for Rough-In Plumbing Lab: 11 house lessons, 5 boiler lab steps, a sandbox, and a test that checks every lesson is solvable.

### [strange_attractor_visualizer](https://github.com/pmiloslavsky/strange_attractor_visualizer)
The source for the attractor visualizer, with a companion history of each system and links to the original papers.

### [hnswlib](https://github.com/pmiloslavsky/hnswlib) (fork)
A fork of [nmslib/hnswlib](https://github.com/nmslib/hnswlib), the header-only C++ library for fast approximate nearest-neighbor search (HNSW) with Python bindings.

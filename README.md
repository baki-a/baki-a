# Anass Baki Achkoukar

**Computer Engineering @ Universitat de Barcelona** · Graduating 2027 · Barcelona, Spain 🇪🇸

I work close to the metal and care about performance — C/C++, bare-metal ARM, concurrent networking — and I'm increasingly focused on the **systems side of machine learning**: distributed runtimes, throughput, and reinforcement learning.

Most of my projects live at the intersection of **algorithms and systems**: a ray tracer built for speed, a P2P protocol built for concurrency, embedded firmware with no RTOS, and RL agents solving NP-hard optimization under real-world constraints.

🔭 **Going deeper on:** ML systems & performance, distributed training/inference, and reinforcement learning.

---

## Featured work

### [Multi-Agent Proof-of-Useful-Work Consensus](https://github.com/baki-a/Multi-Agent-PoUW-Consensus) · Python
Blockchain consensus that swaps wasteful hash mining for *useful* computation — solving NP-hard Vehicle Routing across 20+ TSPLIB maps. Four competing agents (A\*, Expectimax, Minimax + alpha-beta, Q-learning RL) in a three-layer stochastic environment with an adversarial pursuit layer. **The RL agent cut routing cost ~33% vs. an A\* baseline** over a 22-round benchmark.

### [TracerToy — 3D Ray Tracing Engine](https://github.com/baki-a/tracertoy-graphics) · C++17 · GLM · CMake
Recursive ray tracer from scratch: reflections, refractions (Snell's law + total internal reflection), Blinn–Phong shading, stochastic anti-aliasing, and AABB acceleration structures. JSON-driven scene loader with HDRI environment maps.

<!-- Make this repo public, then link it here: https://github.com/baki-a/ares-p2p-protocol -->
### ARES — P2P File-Sharing Protocol · Java · TCP/IP
Custom binary opcode protocol over TCP/IP; asynchronous multithreaded server with a `ConcurrentHashMap` registry; 8 KB chunked transfers routed through a central tracker with graceful disconnect handling.

<!-- Make this repo public, then link it here: https://github.com/baki-a/msp432-wall-following-robot -->
### MSP432 Wall-Following Robot · Bare-Metal C · ARM Cortex-M4F
Autonomous robot in bare-metal C with no RTOS: interrupt-driven UART (Dynamixel @ 500 kbps), hardware timers, IR sensors, and a hierarchical reactive state machine with a proportional controller.

---

## Toolbox
`C` · `C++` · `Python` · `Java` · `ARM Assembly` · `SQL` · `Linux` · `Git` · `CMake`

## Reach me
📧 Renz.anass@gmail.com &nbsp;·&nbsp; 🔗 *add your LinkedIn URL here*

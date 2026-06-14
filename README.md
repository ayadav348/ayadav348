VR is real and the industry will take off in like 3 years trust

Cars r cool (3rd Gen NC Miata 🩷)

Everyone should be driving self driving cars or miatas no inbetween

neovim arch user cause i like pacman -Syu and for aura farming purposes

---
nerd stuff:  

### Focus: Spatial Computing, Embedded Inference, Real-Time Rendering Pipelines, & Robotics State Estimation. ###

---

## 🛠️ Repositories & Active Infrastructure

### 🚀 Spatial Computing & Computer Vision
* **[Sim-to-Real BEV Perception Engine](https://github.com/ayadav348/spatial-bev-pipeline)** (C++, Eigen3, OpenCV, PyTorch)
    * *Result:* Dropped vehicle tracking latency from 425.5ms to 3.22ms (**132x execution speedup**) using boot-time memory-mapped Look-Up Tables (LUTs) for Inverse Perspective Mapping.
    * *State Estimation:* Implemented a heap-allocation-free 4D Kalman Filter from scratch to maintain dynamic object tracking tracking trajectories through 500ms sensor occlusions.
* **[Spatial 3D Scene Discovery & Volumetric Retrieval Engine](https://github.com/ayadav348/VR-WhiteBoard)** (Python, FastAPI, PostgreSQL, pgvector, Ollama)
    * *Mechanism:* Serializes time-series 3D bounding box dimensions, camera extrinsics $[R|t]$, and ego-vehicle telemetry into a Spatial RAG architecture.
    * *Performance:* Indexes large-scale datasets (nuScenes/Waymo) via `pgvector` cosine distance metrics to achieve sub-5ms lookup speeds for automated state-space simulation initialization.

### 🎮 Graphics, Rendering & Extended Reality
* **[Shader Optimized Driving Simulator](https://github.com/ayadav348/drivingsim)** (Godot, GLSL)
    * Procedural driving simulator executing a custom programmable GLSL vertex/fragment distortion shader pipeline to simulate high-velocity peripheral motion cues, reducing graphics memory load by 50%.

### 📟 System Telemetry & Tooling
* **[git-vector](https://github.com/ayadav348/git-vector)** (Node.js, Asynchronous Event Loops) | **[Available on npm](https://www.npmjs.com/package/git-vector)**
    * *Architecture:* A low-latency multi-repository CLI telemetry and drift analysis engine that models localized workspace structures as coordinate fields to calculate directional ahead/behind state deltas.
    * *Concurrency:* Leverages parallel sub-process threads to fetch multi-repo status markers simultaneously, integrating process-level environment variables (`GIT_TERMINAL_PROMPT=0`) to isolate and suppress interactive authentication blocks cleanly.

### 🌐 System Infrastructure & Web Assets
* **[RU Origami Club Core Platform](https://github.com/ayadav348/origamiclub)** (HTML, Tailwind CSS, JavaScript)
    * Production deployment and DNS routing via Vercel for event coordination metrics.

---

<p align="left">
  <img src="contributions.svg" alt="Git Activity Metrics Pipeline" />
</p>

# Awesome-Physics-Simulation-Engine-Game-Physics

## Top Physics Simulation Engine & Game Physics Ecosystem



**Curated List of SaaS/Commercial Engines & Open-Source GitHub Projects**  

*Focused on 2D/3D Rigid-Body Dynamics, Real-Time Collision Detection, Destruction/Cloth/Fluid Solvers & Deterministic Multiplayer Physics*  

**Last updated: November 2026**



This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Physics Simulation Engine & Game Physics**. These tools power high-frame-rate 2D and 3D rigid-body simulations, continuous collision detection (CCD), vehicle dynamics, ragdoll animation, soft-body/cloth physics, and rollback-compatible deterministic multiplayer physics.



**Examples** include Havok Physics, NVIDIA PhysX, Bullet Physics, Box2D, Chipmunk2D, Unity Physics, Unreal Chaos, Godot Physics, Newton Game Dynamics, Open Dynamics Engine, and `jrouwe/JoltPhysics` (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for multi-threaded C++/Rust/JS game physics engines, deterministic rollback engines, 2D rigid-body solvers, and real-time fluid/destruction libraries — ideal for game engine programmers, indie developers, WebGPU/WebAssembly game builders, and simulation engineers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Havok Physics & Cloud Services (Microsoft)](https://havok.com)**  

  Industry-standard commercial 3D rigid-body physics, collision detection, and destruction middleware powering major AAA games and cloud simulation backends.



- **[Unity Physics & Havok Physics for Unity](https://unity.com)**  

  Commercial DOTS/ECS-native stateless deterministic physics engine integrated with Unity Cloud build and multiplayer netcode services.



- **[Unreal Engine Chaos Physics (Epic Games)](https://unrealengine.com)**  

  High-performance real-time physics, fracture/destruction, cloth, and vehicle dynamics subsystem built into Unreal Engine and Pixel Streaming cloud workflows.



- **[NVIDIA Omniverse & PhysX Cloud](https://nvidia.com)**  

  Cloud-accelerated real-time GPU physics, destruction (`Blast`), and fluid (`Flow`) simulation infrastructure for interactive 3D worlds.



- **[PlayCanvas Physics Cloud (Ammo.js / Rapier Web)](https://playcanvas.com)**  

  Cloud-hosted 3D web game engine offering integrated rigid-body physics, raycasting, and collaborative browser testing.



- **[Roblox Physics Engine (Cloud Server Simulation)](https://roblox.com)**  

  Cloud-authoritative distributed rigid-body, constraint, and aerodynamic physics engine simulating millions of concurrent multiplayer experiences.



- **[BeamNG.tech / BeamNG.drive Soft-Body Cloud](https://beamng.tech)**  

  Commercial real-time node-beam soft-body vehicle and structural deformation physics platform for games and virtual proving grounds.



- **[ Algoryx Dynamics (AGX Dynamics)](https://algoryx.com)**  

  Commercial high-fidelity real-time multi-body, cable, and granular terrain physics engine bridging gaming engines and heavy-machinery simulators.





## Open-Source GitHub Projects



- **[jrouwe/JoltPhysics](https://github.com)**  

  Modern, multi-core friendly open-source C++ rigid-body physics and collision detection engine used in AAA titles (*Horizon Forbidden West*) and Godot Engine.



- **[Bullet Physics (`bullet3`)](https://github.com)**  

  Veteran open-source C++ real-time collision detection and multi-body dynamics library supporting rigid bodies, soft bodies, constraints, and GPU acceleration.



- **[NVIDIA PhysX SDK (Open-Source)](https://github.com)**  

  NVIDIA's flagship open-source real-time rigid-body, articulation, vehicle, and GPU-accelerated particle/cloth physics engine.



- **[Box2D](https://github.com)**  

  The gold-standard open-source 2D rigid-body physics engine in C (v3 with SIMD multithreading), powering countless 2D indie games, Unity 2D, and Godot.



- **[Rapier (Dimforge)](https://github.com)**  

  Blazing-fast, cross-platform, deterministic 2D and 3D open-source physics engine written in Rust with native WebAssembly, Bevy, and JavaScript/TypeScript support.



- **[Chipmunk2D](https://github.com)**  

  Fast, lightweight, portable open-source 2D rigid-body physics library written in C with clean collision callbacks and spatial hashing.



- **[Newton Game Dynamics](https://github.com)**  

  Cross-platform open-source C++ real-time physics simulation library renowned for deterministic solver stability and accurate joint constraints.



- **[ODE (Open Dynamics Engine)](https://bitbucket.org)**  

  Classic, lightweight open-source C/C++ rigid-body dynamics and collision detection engine featuring articulated joint types and built-in collision primitives.



- **[Godot Physics (Godot Engine)](https://github.com)**  

  Built-in open-source 2D and 3D physics engines inside Godot Engine, complemented by native Jolt Physics integration for 3D games.



- **[BepuPhysics v2](https://github.com)**  

  Pure C#, SIMD-accelerated open-source 3D rigid-body physics library engineered for extreme throughput in .NET and custom C# game engines.



- **[Cannon-es](https://github.com)**  

  Actively maintained open-source 3D physics engine written in TypeScript/JavaScript tailored for Three.js, React Three Fiber, and WebGL/WebGPU browser games.



- **[Matter.js](https://github.com)**  

  Popular open-source 2D rigid-body physics engine for the web featuring sleeping bodies, composite constraints, concave hulls, and canvas debugging.



- **[Planck.js](https://github.com)**  

  Clean, idiomatic JavaScript/TypeScript rewrite of Box2D engineered for cross-platform HTML5 and mobile 2D game development.



- **[Avian (formerly Bevy XPBD)](https://github.com)**  

  ECS-driven open-source 2D and 3D physics engine built natively for the Bevy game engine in Rust using Extended Position-Based Dynamics (XPBD).



- **[React Physics 3D](https://github.com)**  

  Lightweight, dependency-free open-source C++ 3D physics engine featuring discrete collision detection, rigid bodies, joints, and raycasting.



- **[Ammo.js](https://github.com)**  

  Direct Emscripten/WebAssembly port of Bullet Physics bringing full C++ 3D rigid-body and soft-body physics directly into web browsers.



- **[LiquidFun (Google)](https://github.com)**  

  Open-source 2D rigid-body and particle-based fluid simulation engine extending Box2D for real-time water, wave, and soft-body mechanics.



### Additional Strong Open-Source Options



- **[Verlet-js](https://github.com)** and **[PBD / XPBD Cloth & Soft-Body Solvers](https://github.com)** for lightweight rope, cloth, and deformable mesh physics.

- **[NPhysics / Parry (Dimforge)](https://github.com)** for standalone 2D and 3D geometric collision detection, raycasting, and convex decomposition in Rust.

- **[V-HACD](https://github.com)** for Volumetric Hierarchical Approximate Convex Decomposition, turning complex 3D game meshes into fast convex collision hulls.

- **[SPLISHSPLASH](https://github.com)** for open-source Smoothed Particle Hydrodynamics (SPH) real-time and offline fluid simulation.

- Many community **JoltPhysics C/Rust/C#/JS bindings (`JoltC`, `jolt-physics-rs`, `JoltPhysics.js`)**, **fixed-point deterministic math crates**, and **rollback netcode (`GGRS`) physics wrappers**.



**Frameworks for building custom systems**: Combine **jrouwe/JoltPhysics** or **Rapier** (for 3D), **Box2D** or **Chipmunk2D** (for 2D), **V-HACD**, and **Parry** with **Godot / Bevy / Three.js** for deterministic, multi-threaded game physics pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Networked multiplayer games using rollback netcode or lockstep simulation require cross-platform bit-exact determinism (fixed-point math or strict IEEE-754 floating-point compiler flags); verify determinism guarantees before selecting a physics engine for competitive multiplayer.

- High-speed projectiles and thin colliders require Continuous Collision Detection (CCD) and fixed-timestep accumulators to prevent tunneling.



---



**Made for game engine programmers, indie game developers, WebGPU/Wasm builders, and physics simulation engineers.**  

Let's make real-time game physics faster, deterministic, and open.

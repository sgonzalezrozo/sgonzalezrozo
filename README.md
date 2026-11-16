# Hi, I'm Santiago González Rozo

**Lead Unity Client Engineer | Client Architecture & Technical Leadership**

I have 17 years of experience across four studios, shipping six free-to-play games on mobile and PC, including *FIFA Rivals* and *World War Doh*. I've led client teams of up to 8 engineers, and I specialize in client architecture, mobile performance, multiplayer systems, and live-ops infrastructure.

📍 Bogotá, Colombia · Full US hours overlap · Open to relocation (EU/UK/US) | [santiago.gonzalezrozo@outlook.com](mailto:santiago.gonzalezrozo@outlook.com)

## My Open-Source Unity Toolchain

I build and maintain tools that solve architecture and performance bottlenecks in Unity:

- **[Fast IoC](https://github.com/sgonzalezrozo/unity-fast-ioc)**: A dependency injection framework for Unity with edit-time code generation and no runtime reflection. Benchmarked on four phones in IL2CPP: 3,000 bindings and 1,500 injected objects start in under 125 ms.
- **[UI Tweens](https://github.com/sgonzalezrozo/unity-ui-tweens)**: A pooled animation engine for Unity UI, built on LeoECS. Benchmarked on four phones: no garbage collections across 17 scenarios.
- **[Unity Architecture Agents](https://github.com/sgonzalezrozo/unity-architecture-agents)**: Strict MVC architecture rules, Roslyn analyzers, and verification scripts for AI coding assistants (Claude Code, Cursor, Copilot).
- **Screen System** *(Coming Soon)*: A layer-based UI navigation manager for Unity 6 supporting uGUI and UI Toolkit simultaneously, with automatic Addressables cleanup and blurred modal snapshots that disable background rendering. Benchmarked on Pixel 5 and Galaxy A02s in IL2CPP: 2.6 ms cached screen show, flat memory across 12 scene changes, and zero leaked Addressables handles.
- **Slot List** *(Coming Soon)*: A virtualized scrolling and layout engine for Unity 6 uGUI (lists, grids, bento layouts, expandable rows, and pagination). Benchmarked on Pixel 5 and Galaxy A02s in IL2CPP: 0.12–0.28 ms per frame and 0 B GC allocations while scrolling 100,000 items.

## Tech Stack

**Core:** C#, Unity 6, iOS/Android (IL2CPP)  
**Architecture:** MVC, Dependency Injection (Fast IoC, Zenject), ECS (LeoECS), State Synchronization  
**Performance:** Memory Management, GC Allocation Optimization, Addressables  
**Workflows:** Roslyn Analyzers, Code Generation, CI/CD (Jenkins), Claude Code / Cursor

**Let's connect on [LinkedIn](https://www.linkedin.com/in/sgonzalezrozo).**

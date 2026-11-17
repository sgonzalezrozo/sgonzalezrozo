# Hi, I'm Santiago González Rozo

**Lead Unity Client Engineer | Client Architecture & Technical Leadership**

I have 17 years of experience across four studios, shipping six free-to-play games on mobile and PC, including *FIFA Rivals* and *World War Doh*. I've led client teams of up to 8 engineers, and I specialize in client architecture, mobile performance, multiplayer systems, and live-ops infrastructure.

📍 Bogotá, Colombia · Full US hours overlap · Open to relocation (EU/UK/US) | [santiago.gonzalezrozo@outlook.com](mailto:santiago.gonzalezrozo@outlook.com)

## My Open-Source Unity Toolchain

I build and maintain tools for the architecture and performance problems of mobile Unity games:

- **[Screen System](https://github.com/sgonzalezrozo/unity-screen-system)**: a layer-based UI manager for uGUI and UI Toolkit. Screens share layers with automatic draw order, only what's visible renders, and everything unloads on scene change. On four phones (IL2CPP): 1–5 ms cached shows, flat memory across 12 scene changes, zero leaked Addressables handles.
- **[Fast IoC](https://github.com/sgonzalezrozo/unity-fast-ioc)**: dependency injection with edit-time code generation and no runtime reflection. 3,000 bindings and 1,500 injected objects start in under 125 ms on four phones.
- **[UI Scroller](https://github.com/sgonzalezrozo/unity-ui-scroller)**: a zero-allocation recycling scroll view: lists, grids, bento layouts, sections, carousels, nested scrolling and paging. 0.07–0.25 ms per scroll event at 100,000 items on five phones and WebGL.
- **[Unity Architecture Agents](https://github.com/sgonzalezrozo/unity-architecture-agents)**: strict MVC rules, 14 Roslyn analyzers and verification scripts that keep AI coding assistants (Claude Code, Cursor, Copilot, Rider) on architecture.
- **[UI Tweens](https://github.com/sgonzalezrozo/unity-ui-tweens)**: pooled UI animation on LeoECS, no garbage collections across 17 scenarios on four phones.

### Tech Stack
**Core:** C#, Unity 6, iOS/Android/WebGL (IL2CPP)
**Architecture:** MVC, Dependency Injection (Fast IoC, Zenject), ECS (LeoECS), State Synchronization
**Performance:** Memory Management, Zero-GC Code, Rendering, Addressables, Device Benchmarking
**Workflows:** Roslyn Analyzers, Code Generation, UPM Packages, CI/CD (Jenkins), Claude Code / Cursor

**Let's connect on [LinkedIn](https://www.linkedin.com/in/sgonzalezrozo).**

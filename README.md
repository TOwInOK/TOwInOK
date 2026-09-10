<!--
  GLYPH SPECIFICATION:
  ✦ Tier 1 ▪ Selected Systems & Core Architecture
  ▲ Tier 2 ▪ Specialized Tools, Launchers & Runtimes
  ◈ Protocols, Network Drivers & State Machines
  ◇ Web Platforms, Client Applications & Upcoming
  ● Active / Production release
  ○ Archived / Stable legacy
  ▪ Technical invariant & Architecture detail
-->

# TOwInOK ▪ software engineer · systems & tools

Hey. I design and build reliable software systems and tooling. Focused on explicit contracts, fault tolerance, and predictable behavior across the stack.

---

### ◈ Core Domains

* **Systems & Protocols** ▪ Fault-tolerant network clients, message-passing architectures, hardware drivers, and deterministic protocol FSMs.
* **Tooling & Runtimes** ▪ Application & instance lifecycle management, versioned runtime launchers, headless runtime automation, and developer CLI utilities.
* **AI Systems & Integration** ▪ Production LLM integration, prompt engineering contracts, and resilient pre/post-processing systems.
* **Web Platforms & Wasm** ▪ Full-stack TypeScript ecosystems, reactive WebAssembly SPAs, and browser-based graphic tools.

---

### ✦ Tier 1 ▪ Selected Systems

* #### [MultiVC](https://github.com/lost-umbrella-dev/MultiVC) `[Rust]`
  ▲ *High-performance instance launcher and runtime manager for [VoxelCore](https://github.com/MihailRis/voxelcore).*
  ▪ **Atomic state snapshots:** Version updates never mutate running environments; supports instant rollback on failure.
  ▪ **Deduplicated cache:** Global content-addressable storage for shared core binaries and game assets across instances.
  ▪ **Hybrid runtime:** Unified headless CLI engine alongside a responsive GUI in portable standalone mode.

* #### [matroskin](https://github.com/TOwInOK/matroskin) `[Rust]`
  ◈ *Async, fault-tolerant client library for WhatsMiner ASIC mining fleets.*
  ▪ **Supervised actor model:** Isolates physical TCP socket drops and reconnection logic within a dedicated Tokio actor.
  ▪ **Strict state machine:** Enforces non-overlapping command-response lifecycles, replacing fragile raw socket polling.
  ▪ **Production-ready API:** Typed command abstractions verified directly against physical mining hardware.

* #### [SSS-rs](https://github.com/TOwInOK/SSS-rs) `[Rust · Leptos · Wasm]`
  ◇ *Zero-backend reactive developer portfolio and identity card generator.*
  ▪ **Client-side execution:** Compiles directly to WebAssembly with live reactive DOM updates and zero backend reliance.
  ▪ **Template engine:** Dynamic Jinja-like template expansion with real-time preview rendering in the browser.
  ▪ **Direct export pipeline:** In-memory generation of optimized WebP, PNG, and static HTML artifacts.

---

### ▲ Tier 2 ▪ Specialized Tools & Engines

* ● **[tee-morphosis](https://github.com/PulseClient-ddnet/tee-morphosis)** `[Rust]` — Binary UV map parser and runtime skin reconstruction pipeline for DDNet. Eliminates unnecessary heap allocations during sprite decomposition.
* ● **[passutil-web](https://obsidian-empire.github.io/passutil-web/)** `[React · TypeScript · Python · Tailwind]` — In-browser passport composer with WebP export and automated asset minification tooling.
* ● **[cirno](https://github.com/TOwInOK/cirno)** `[Rust]` — Minimalist terminal startup injector. Sub-millisecond initialization, zero external dependencies, dual-language layout.
* ○ **[Minecraft-Dependency-Manager](https://github.com/TOwInOK/Minecraft-Dependency-Manager)** `[Rust]` *(archived)* — Staging updater for Minecraft server cores and plugins. Automates dependency sync with progress tracking, locking verified states in `lock.toml` for production deploy.

---

### ◇ Upcoming

* **[tonometr](https://github.com/TOwInOK/tonometr)** `[Rust · Telegram · Vision AI]` — Telegram bot for blood pressure diary tracking powered by Vision AI photo analysis.

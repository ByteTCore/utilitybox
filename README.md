# UtilityBox (v2.x)

A high-performance, lightweight, and mission-critical desktop application for developers. UtilityBox consolidates fragmented terminal commands into a sleek, unified GUI powered by Tauri and Rust.

## 🚀 Core Modules

- **🐋 Docker Orchestrator**: 
  - Comprehensive dashboard for Containers, Images, Volumes, and Networks.
  - **Live Management**: Start, stop, restart, and remove resources with real-time status updates.
  - **Image Tools**: Pull from Docker Hub or build local images from source context.
  - **Bridge to Browser**: 1-Click access to exposed web services via `127.0.0.1:[port]`.
  - **Advanced Ops**: Integrated terminal (Attach Shell), detailed resource inspection, and bulk cleanup (Stop All, Prune).
- **🚀 Project Engine**: Manage isolation for Node.js and PHP project environments. Rapidly toggle versions and launch terminal-ready environments.
- **🧹 Project Janitor**: Scan and instantly purge heavy build artifacts (`node_modules`, `dist`, `vendor`) across scattered projects to reclaim disk space.
- **🛠 Dev Utils Pocket**: A collection of offline-first tools:
  - JSON Formatter/Validator
  - Base64 & URL Encoder/Decoder
  - Hash Generator (MD5, SHA, etc.)
  - JWT Debugger, Regex Tester, UUID Generator, and Timestamp Converter.
- **📝 Hosts Manager**: Edit and manage system DNS overrides with native privilege elevation (Admin/Sudo).
- **🔌 Port Killer**: Detect and terminate stubborn processes bound to system ports in 1-click.
- **🎬 Media Suite**: Batch image optimization and video transcoding powered by FFmpeg.

## 🛠 Tech Stack

- **Frontend Core**: [Vue 3](https://vuejs.org/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/)
- **UI System**: [DaisyUI](https://daisyui.com/), [Tailwind CSS](https://tailwindcss.com/)
- **Desktop Framework**: [Tauri v2](https://v2.tauri.app/), [Rust](https://www.rust-lang.org/)
- **Engine Dependencies**: [Docker](https://www.docker.com/), [FFmpeg](https://ffmpeg.org/)

## 📋 Prerequisites

- **Docker Desktop**: Required for Docker Orchestrator module.
- **Node.js** & **npm**: Standard development dependencies.
- **Rust**: For compiling the high-performance backend.
- **FFmpeg**: For media conversion functionality (automated setup available).

## ⚙️ Setup & Development

1. **Clone & Install:**
   ```bash
   git clone <your-repository-url>
   npm install
   ```

2. **FFmpeg Sidecar (Windows/macOS):**
   Run the setup script to provision the required native binaries for media conversion:
   ```powershell
   npm run setup-win
   ```

3. **Start Running:**
   ```bash
   npm run tauri dev
   ```

## 📦 Distribution

- `npm run tauri build`: Compiles optimized, signed production binaries. Output available in `src-tauri/target/release/bundle/`.

## 📄 License

Licensed under the Apache License, Version 2.0.

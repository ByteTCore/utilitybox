# UtilityBox 🚀

**UtilityBox** is a powerful, lightweight, and mission-critical desktop application for developers. It consolidates fragmented terminal commands and local tools into a single, modern, and lightning-fast Graphical User Interface (GUI), built on **Tauri v2** and **Rust**.

---

## ✨ Key Highlights (V2 Upgrades)
- **Modern & Futuristic UI:** Transitioned from Neobrutalism to a sleek, high-contrast, minimalist design with seamless Dark/Light Mode synchronization. Features dynamic font scaling and smooth state persistence across application restarts.
- **Customizable Auto-Updater:** Automated patch and feature delivery system with support for custom standalone installation paths.
- **Optimized Architecture:** Ultra-smooth frontend rendering with zero lag. Heavy lifting is securely delegated to the Rust backend, executing operations stealthily without triggering disruptive, flashing terminal windows (especially on Windows).

---

## 🛠 Core Modules & Deep Features

### 1. 🐋 Docker Orchestrator
A comprehensive management and monitoring dashboard tailored for the Docker ecosystem.
- **Comprehensive Control:** Seamlessly monitor and manage Containers, Images, Volumes, and Networks.
- **Live Management:** Start, stop, restart, or remove resources with real-time status updates without dropping a beat.
- **Integrated Console Bridge:** Embedded xterm.js powered console to instantly attach to container shells, orchestrate image builds, or fire up system-wide prunes.

### 2. 🎨 Color Forge
A specialized playground for color analysis and design.
- Features real-time, bi-directional conversion across an extensive range of technical color formats: **RGB, HEX, sRGB, HSV, and CMYK**.

### 3. ⚙️ Background Managers
Stealthily orchestrate local development utilities via CLI wrappers without invoking annoying popup consoles:
- **Nginx Engine:** Local routing and reverse proxy management.
- **Mailpit:** Local mail delivery tester.
- **MediaConverter (FFmpeg):** Rapid video and image format conversion and sizing.

### 4. 🧹 Node/PHP Project Janitor
- Instantly scan scattered directories for massive disk-hogging dependencies like `node_modules`, `dist`, or `vendor`. Reclaim gigabytes of storage with a single click.

### 5. 🧰 Dev Utils Pocket
A massive toolbox running *100% offline*:
- JSON Formatter & Validator.
- Base64 & URL Encoder/Decoder.
- Hash Fingerprint Generator (MD5, SHA, etc.).
- JWT Debugger, Regex (Regular Expression) Tester, UUID Generator, and Epoch Timestamp Converter.

### 6. 🔌 Network & System Monitors
- **Hosts Manager:** Directly manage your OS `hosts` file for DNS overrides, utilizing elevated privileges (Admin/Sudo) right from the interface.
- **Port Killer:** Accurately identify the rogue PIDs hogging stubborn network ports and forcibly terminate them.

---

## 💻 Tech Stack In Action
The UtilityBox engine is driven by breakthrough 2025 performance technologies:
- **Client Render (Frontend):** [Vue 3](https://vuejs.org/), [TypeScript](https://www.typescriptlang.org/), [Vite 6](https://vitejs.dev/)
- **Design System:** [Tailwind CSS v4](https://tailwindcss.com/) paired with [DaisyUI v5](https://daisyui.com/) (Native Dark Theme Ready).
- **Core Engine (Backend/Desktop):** [Tauri v2](https://v2.tauri.app/) and the high-performance language [Rust](https://www.rust-lang.org/).
- **Supporting Components:** Xterm.js for the embedded terminal, paired with SystemInfo crate for deep system diagnostics.

---
*Reinvented for standardized workflows, UtilityBox strips away the mundane chores, accelerating your productivity to its absolute limit.*

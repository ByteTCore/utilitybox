# 🧰 UtilityBox

UtilityBox is a local-first desktop workspace for developers who need fast, practical tools for daily engineering work. It combines data utilities, runtime controls, project maintenance, file inspection, system helpers, and media conversion into one focused application.

The app is built for workflows that usually require several separate tools: formatting JSON, decoding tokens, checking ports, managing local runtimes, editing hosts entries, opening large text-like files, cleaning project artifacts, or converting image and video files. UtilityBox keeps these tasks in one place so developers can move quickly without switching context.

## 🎯 1. What is UtilityBox for?

UtilityBox is designed to help developers handle common local tasks directly from a desktop application.

Its main goals are:

- Provide quick developer utilities for transforming, validating, and inspecting data.
- Help manage local development environments such as Nginx, PHP-CGI, MySQL, and Mailplit.
- Support system-level workflows such as port inspection, hosts file editing, and terminal access.
- Make project maintenance easier by scanning and cleaning generated artifact folders.
- Provide local file and media tools for viewing text-like files and converting images or videos.

UtilityBox follows a user-triggered workflow model. Users choose a module, provide input, review the result, and explicitly run the action they need. Project files, command output, runtime paths, and workspace data stay local to the machine and are not sent to a remote service by the app.

## 💻 2. Supported operating systems

The current UtilityBox release is configured for Windows desktop usage.

Supported platform:

- Windows x64/amd64
- Windows installer package using NSIS

The current release configuration does not include macOS or Linux builds. Support for additional platforms may be added in future releases if the desktop packaging and bundled runtime setup are expanded.

## 🌐 3. Website

Official website:

https://utilitybox.th.pro.vn

## 🧩 4. Core modules

UtilityBox includes a set of focused modules for developer productivity and local machine workflows.

### 🛠️ Dev Utils

Tools for transforming and inspecting common developer data formats.

- Format, validate, minify, compare, and inspect JSON.
- Encode and decode Base64 data.
- Encode, decode, and inspect URLs.
- Generate and verify hashes.
- Decode and inspect JWT payloads.
- Test regular expressions and preview matches.
- Convert timestamps and date values.
- Generate UUIDs.

### 🎨 Color Forge

A color workspace for choosing, converting, refining, and copying colors.

- Pick and preview colors.
- Convert between supported color formats.
- Generate shades, tints, and related color values.
- Copy generated color values for use in code, UI design, and documentation.

### 🔌 Kill Port

A system helper for finding and stopping processes that occupy ports.

- Scan selected ports.
- Inspect processes currently bound to those ports.
- Terminate blocking processes directly from the app when needed.

### 🖥️ Dev Runtime

A local runtime manager for development services bundled or configured with UtilityBox.

- Run and configure Nginx.
- Run and configure PHP-CGI.
- Run and configure MySQL.
- Run and configure Mailplit.
- Manage runtime paths and service settings from a desktop UI.

### 🌍 Virtual Hosts

A hosts file editor for local domain development.

- Load the system hosts file.
- Add, edit, and remove local host entries.
- Validate changes before saving.
- Save hosts configuration for local domain routing.

### 📁 Project Engine

A project workspace for organizing development folders and opening terminals with the right runtime context.

- Save frequently used project folders.
- Assign project runtimes such as PHP, Node.js, Go, and Python.
- Open terminals directly from saved project entries.
- Keep local project configuration accessible from one workspace.

### 🧹 Project Janitor

A cleanup tool for generated files and dependency artifacts.

- Scan selected workspace roots.
- Detect common artifact folders such as `node_modules`, `dist`, `target`, `vendor`, and `.next`.
- Review scan results before cleanup.
- Remove selected artifacts to recover disk space and reduce workspace clutter.

### 📄 File Viewer

A lightweight viewer for text-like files.

- Open files such as logs, SQL files, CSV/TSV files, JSON, XML, Markdown, YAML, `.env`, and INI files.
- Inspect file metadata.
- Read content in bounded chunks instead of loading everything at once.
- Useful for quickly checking large logs or configuration files.

### 🖼️ Convert Image

A batch image conversion workspace.

- Convert multiple images in one workflow.
- Choose output format.
- Apply resolution presets.
- Configure quality settings.
- Control output naming rules.

### 🎬 Convert Video

A batch video transcoding workspace powered by configurable conversion settings.

- Convert multiple videos in one workflow.
- Choose output format and codec.
- Configure resolution, FPS, and CRF.
- Apply output naming rules.
- Prepare media files for development, sharing, testing, or publishing workflows.

### 🐳 Docker Dashboard

A prepared workspace route for future Docker management features.

This module is currently reserved for upcoming container-related controls and dashboard functionality.

### ⚙️ Settings

Application-level configuration for UtilityBox.

- Adjust appearance and UI preferences.
- Configure startup behavior.
- Select shell preferences.
- Import and export app configuration.
- Manage runtime paths used by local services.

### ℹ️ Application Info

Product and release information for the installed UtilityBox build.

- View the current app version.
- Check update status.
- Review the available feature list.
- Open project and developer links.
- Review the local-only application policy.

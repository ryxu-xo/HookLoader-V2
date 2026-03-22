# 🪝 HookLoader V2 - Advanced Stealth Injection Framework

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0.1_Beta-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Windows_10/11-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Security-Vanguard_Bypass-orange?style=for-the-badge">
</p>

## 🛡️ Project Overview
**HookLoader V2** is a professional-grade, multi-vector DLL injection framework designed specifically for high-security environments. Featuring a custom Cyberpunk-themed terminal UI and pulse monitoring, it provides the most advanced user-mode stealth techniques available.

---

## ⚡ Key Features
### 🧬 Multi-Vector Injection Flow
The loader implements a "Stealth Escalation" logic to ensure success regardless of anti-cheat aggression:
1.  **Manual Mapping (File-less)**: Overloads sacrificial modules to bypass `VirtualAllocEx` hooks.
2.  **Thread Hijacking (RIP Redirection)**: Hijacks existing process threads to avoid `CreateRemoteThread` callbacks.
3.  **SetWindowHookEx (Usermode Fallback)**: High-security legacy fallback with priority message poking.

### 🕵️ Stealth & Evasion
- **PE Header Wiping**: Physically erases MZ/PE headers in target memory to defeat signature scanners.
- **PEB Masking**: Sophisticated module spoofing inside the `InLoadOrderModuleList`.
- **Module Overloading**: Hijacks legitimate system DLLs (e.g., `uxtheme.dll`) to hide the payload.
- **Header Obfuscation**: Real-time manipulation of the Process Environment Block.

---

## 🖥️ Terminal Interface (CyberUI)
The loader features a high-fidelity ANSI terminal interface with real-time telemetry:
- **[ PULSE ]**: Live CPU and RAM monitoring of the target process directly in the status bar.
- **Hacker Aesthetic**: Professional color-coded logging (System, Module, Safety, Success).
- **Persistent Loop**: Automatically waits for the game to launch, injects, and returns to a listening state on exit.

---

## 🚀 Getting Started
### 🔨 Requirements
- Visual Studio 2022 (v143 Toolset)
- Windows SDK 10.0.22621.0 or higher
- C++20 Standards enabled

### 🏗️ Build Instructions
1. Open `HookLoaderV2.sln` in Visual Studio.
2. Set configuration to **Release | x64**.
3. Rebuild Solution.
4. Run the executable as **Administrator**.

---

## ⚠️ Disclaimer
This project is for educational and research purposes only. The developers are not responsible for how this tool is used or any resulting accounts bans. Use within the legal frameworks of your jurisdiction.

<p align="center">
  <b>Developed with ❤️ by <a href="https://github.com/ryxu-xo">ryxu-xo</a> on GitHub</b>
</p>

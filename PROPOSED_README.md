<div align="center">
  <a href="https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App">
    <img src="https://raw.githubusercontent.com/chirag127/chirag127/main/banners/ScanFlow.png" alt="ScanFlow Banner">
  </a>

  <h1 align="center">ScanFlow: High-Performance QR/Barcode Scanner App</h1>

  <p align="center">
    <strong>Elite cross-platform mobile scanner built with React Native & Expo for superior performance.</strong>
  </p>


<!-- BADGES -->
<p align="center">
    <a href="https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/actions/workflows/ci.yml">
        <img src="https://img.shields.io/github/actions/workflow/status/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/ci.yml?style=flat-square&logo=githubactions&logoColor=white&label=CI/CD" alt="Build Status">
    </a>
    <a href="https://codecov.io/gh/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App">
      <img src="https://img.shields.io/codecov/c/github/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App?style=flat-square&logo=codecov&logoColor=white" alt="Code Coverage"/>
    </a>
    <a href="#">
        <img src="https://img.shields.io/badge/TypeScript-Strict-blue?style=flat-square&logo=typescript" alt="TypeScript">
    </a>
    <a href="#">
        <img src="https://img.shields.io/badge/React%20Native-Expo-9cf?style=flat-square&logo=react" alt="React Native & Expo">
    </a>
    <a href="#">
        <img src="https://img.shields.io/badge/linting-Biome-blueviolet?style=flat-square&logo=biome" alt="Biome Linter">
    </a>
    <a href="https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/blob/main/LICENSE">
        <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg?style=flat-square" alt="License">
    </a>
    <a href="https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/stargazers">
        <img src="https://img.shields.io/github/stars/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App?style=flat-square&logo=github&label=Stars" alt="GitHub stars">
    </a>
</p>

<!-- SOCIAL PROOF -->
<p align="center">
    <a href="https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/stargazers"><strong>Star ⭐ this Repo</strong></a> to support the project!
</p>
</div>

---

**ScanFlow** is an elite cross-platform mobile scanner app engineered with React Native and Expo. It delivers high-performance QR and barcode scanning with a fast, intuitive UI, optimized for precision data capture on both iOS and Android devices.

This repository serves as a production-grade template for building modern, scalable, and maintainable mobile applications using the latest industry standards and best practices.


## 📋 Table of Contents

- [✨ Features](#-features)
- [🏗️ Architecture](#️-architecture)
- [🛠️ Tech Stack](#️-tech-stack)
- [🤖 AI Agent Directives](#-ai-agent-directives)
- [🚀 Getting Started](#-getting-started)
- [📜 Scripts](#-scripts)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)


## ✨ Features

- **High-Performance Scanning:** Utilizes native device APIs via `expo-camera` and `expo-barcode-scanner` for instant code detection.
- **Cross-Platform:** Single TypeScript codebase for both iOS and Android, powered by React Native and Expo.
- **Modern UI/UX:** Clean, intuitive, and responsive interface designed for rapid data capture.
- **Scalable Architecture:** Built with **Feature-Sliced Design (FSD)** for unparalleled maintainability and team velocity.
- **Type-Safe Codebase:** End-to-end type safety with TypeScript in strict mode.
- **State Management:** Efficient and predictable state handling with Zustand and TanStack Query.


## 🏗️ Architecture

This project adheres to **Feature-Sliced Design (FSD)**, a professional architectural methodology for frontend applications. It organizes the codebase into layers and slices to ensure strict module boundaries, high cohesion, and low coupling.

plaintext
📁 src/
├── 📱 app/         # App-wide setup (store, router, providers)
├── ⚙️ processes/   # Multi-page scenarios (auth flow)
├── 📄 pages/       # App screens (e.g., HomePage, ScanPage)
├── 🧩 widgets/     # Composite UI blocks (e.g., Header, ScanHistoryList)
├── ✨ features/    # Business-logic units (e.g., scan-barcode, view-history)
├── 📦 entities/    # Business entities (e.g., ScanResult, User)
└── 🌐 shared/      # Reusable modules (UI kit, APIs, configs)



## 🛠️ Tech Stack

- **Core Framework:** React Native, Expo SDK
- **Language:** TypeScript (Strict)
- **Routing:** React Navigation
- **State Management:** Zustand (Global State), TanStack Query (Server State)
- **Linting & Formatting:** BiomeJS
- **Testing:** Vitest, React Native Testing Library, Maestro (E2E)
- **Package Manager:** PNPM


## 🤖 AI Agent Directives

<details>
<summary><strong>System Instructions for AI Agents (December 2025 Standard)</strong></summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type (`package.json`, `expo.json`) and apply the corresponding **Apex Toolchain**. This repository, `ScanFlow-HighPerformance-QRBarcode-MobileScanner-App`, is a cross-platform mobile application.

*   **PRIMARY SCENARIO: MOBILE / APP (TypeScript)**
    *   **Stack:** This project leverages **TypeScript (Strict Mode)**, **React Native**, and the **Expo SDK** for unified cross-platform development. Key dependencies include **React Navigation** for routing, **TanStack Query** for asynchronous state management, and **Zustand** for lightweight global state. The camera and scanner functionalities are powered by `expo-camera` and `expo-barcode-scanner` for maximum performance and integration.
    *   **Architecture:** Adheres strictly to **Feature-Sliced Design (FSD)**. This architectural pattern isolates business logic into self-contained slices (`features`, `entities`, `widgets`) and enforces a top-down data flow, drastically improving scalability, maintainability, and developer velocity. Code is organized into layers: `app`, `processes`, `pages`, `widgets`, `features`, `entities`, `shared`.
    *   **Linting & Formatting:** A unified toolchain is enforced using **BiomeJS** for ultra-fast linting, formatting, and import sorting. This eliminates configuration conflicts and ensures consistent code style across the entire codebase.
    *   **Testing:**
        *   **Unit/Integration:** **Vitest** with **React Native Testing Library** for component-level testing in a simulated DOM environment.
        *   **End-to-End (E2E):** **Maestro** is utilized for declarative, YAML-based E2E testing on both iOS and Android simulators/devices, ensuring real-world user flows are robust.

*   **VERIFICATION & MAINTENANCE COMMANDS**
    *   **Verify Dependencies:** `pnpm install --frozen-lockfile`
    *   **Run Linter/Formatter:** `pnpm lint:fix`
    *   **Run Unit Tests:** `pnpm test`
    *   **Run E2E Tests:** `maestro cloud`

</details>


## 🚀 Getting Started

### Prerequisites

- Node.js (LTS version)
- PNPM
- Expo Go app on your mobile device or an iOS/Android simulator.

### Installation & Setup

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App.git
    cd ScanFlow-HighPerformance-QRBarcode-MobileScanner-App
    

2.  **Install dependencies:**
    bash
    pnpm install
    

3.  **Start the development server:**
    bash
    pnpm start
    

4.  **Launch the app:**
    - Scan the QR code with the Expo Go app on your device.
    - Or, press `i` to run on the iOS Simulator or `a` to run on the Android Emulator.


## 📜 Scripts

| Script       | Description                                      |
|--------------|--------------------------------------------------|
| `pnpm start`   | Starts the Metro bundler for development.        |
| `pnpm ios`     | Runs the app on the iOS Simulator.               |
| `pnpm android` | Runs the app on an Android Emulator/Device.      |
| `pnpm lint`    | Lints the codebase with Biome.                   |
| `pnpm format`  | Formats the codebase with Biome.                 |
| `pnpm test`    | Runs unit tests with Vitest.                     |


## 🤝 Contributing

Contributions are welcome! Please read the [**CONTRIBUTING.md**](https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/blob/main/.github/CONTRIBUTING.md) guide for details on our code of conduct and the process for submitting pull requests.


## 📄 License

This project is licensed under the [**Creative Commons Attribution-NonCommercial 4.0 International License**](https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/blob/main/LICENSE).

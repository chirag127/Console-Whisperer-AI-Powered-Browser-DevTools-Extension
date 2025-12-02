# Console-Whisperer-AI-DevTools-Copilot-Browser-Extension

A sophisticated AI copilot designed to integrate seamlessly with browser Developer Tools, providing real-time error analysis, code optimization suggestions, and deep debugging insights directly within the console. Supercharge your development workflow with AI-powered assistance.

## Project Overview

Console-Whisperer aims to revolutionize the browser developer experience by embedding advanced AI capabilities directly into the console. This extension acts as an intelligent assistant, interpreting errors, suggesting code improvements, and accelerating the debugging process. By leveraging the latest AI models and browser extension technologies, it provides developers with immediate, actionable insights, significantly boosting productivity and reducing development time.

## Features

*   **Real-time Error Analysis:** Instant AI-driven explanations for console errors.
*   **Code Optimization Suggestions:** Proactive recommendations for improving code performance and readability.
*   **Debugging Insights:** AI-powered guidance to help pinpoint and resolve complex bugs.
*   **Seamless DevTools Integration:** Operates directly within the browser's developer console.
*   **Productivity Boost:** Streamlines common debugging and optimization tasks.

## Architecture

This project follows a modern, modular architecture optimized for browser extensions. It is built using **TypeScript**, **Vite** (for efficient bundling), and **Tauri v2** (for potential native integration capabilities, though primarily focusing on the web extension aspect).

mermaid
graph TD
    A[Browser DevTools Console] --> B(Console-Whisperer Extension Core)
    B --> C{AI Model API (e.g., OpenAI, Gemini)}
    B --> D[Error Parsing Logic]
    B --> E[Code Optimization Engine]
    B --> F[Debugging Insight Generator]
    C --> B
    D --> B
    E --> B
    F --> B
    B --> A


## Table of Contents

*   [Project Overview](#project-overview)
*   [Features](#features)
*   [Architecture](#architecture)
*   [Table of Contents](#table-of-contents)
*   [🚀 Getting Started](#-getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Installation](#installation)
    *   [Development Setup](#development-setup)
*   [🤖 AI Agent Directives](#-ai-agent-directives)
*   [🛠️ Development Standards](#-development-standards)
    *   [Core Principles](#core-principles)
    *   [Linting & Formatting](#linting--formatting)
    *   [Testing](#testing)
*   [📜 License](#-license)

## 🚀 Getting Started

### Prerequisites

*   Node.js (v18 or higher)
*   npm or Yarn (package manager)
*   A modern web browser (Chrome, Firefox, Edge)

### Installation

bash
# Clone the repository
git clone https://github.com/chirag127/Console-Whisperer-AI-DevTools-Copilot-Browser-Extension.git
cd Console-Whisperer-AI-DevTools-Copilot-Browser-Extension

# Install dependencies
npm install
# or
yarn install


### Development Setup

To run the extension in development mode:

bash
# Build for development (watch mode)
npm run dev
# or
yarn dev


This command will build the extension and set up a watch process for automatic recompilation upon file changes. You can then load the extension into your browser via the extensions management page (e.g., `chrome://extensions/`).

## 🤖 AI Agent Directives

<details>
<summary>View AI Agent Directives</summary>

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
**Directives:** Detect the project type (e.g., `package.json` for JS/TS, `Cargo.toml` for Rust) and apply the corresponding **Apex Toolchain**. This repository, `Console-Whisperer-AI-DevTools-Copilot-Browser-Extension`, is a **TypeScript Browser Extension**.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** **TypeScript 6.x** (Strict mode enabled by default). **Vite 7** (with Rolldown compiler) for lightning-fast builds and hot module replacement. **Tauri v2.x** for potential native integrations and cross-platform packaging. **WXT (Web Extension Toolkit)** for streamlined browser extension development.
    *   **State Management:** Utilize standardized **Signals** for efficient and reactive state management across the extension.
    *   **UI Framework:** Leverage **TailwindCSS v4** for rapid, utility-first UI development.
    *   **Linting & Formatting:** Employ **Biome** for comprehensive, high-performance code analysis and formatting.
    *   **Testing:** Implement **Vitest** for unit and integration tests, and **Playwright** for end-to-end testing of extension behavior within a browser context.
    *   **Architecture:** Adhere to **Feature-Sliced Design (FSD)** principles for a scalable and maintainable codebase.

*   **SECONDARY SCENARIO: DATA / SCRIPTS / AI (Python) - *Not directly applicable for the core extension logic. Reference only if a companion backend service is developed.***
    *   **Stack:** Python 3.10+ with **uv**, **Ruff**, **Pytest**.
    *   **Architecture:** Modular Monolith or Microservices.

---

## 4. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)
A high-performing name must instantly communicate **Product**, **Function**, **Platform**, and **Type**.

**Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
**Format:** `Title-Case-With-Hyphens` (e.g., `ChatFlow-AI-Powered-Real-Time-Chat-Web-App`).

*   **Current Repository Name:** `Console-Whisperer-AI-DevTools-Copilot-Browser-Extension` (Conforms to standard).

---

## 5. DEVELOPMENT WORKFLOW & COMPLIANCE MANDATE (THE "STANDARD 11")
Every repository **MUST** appear professional and be fully documented.

*   **README.md:** Comprehensive, hero-tier documentation.
*   **PROPOSED_README.md:** This document, outlining the proposed structure and content.
*   **badges.yml:** Configuration for Shields.io badges.
*   **LICENSE:** `CC BY-NC` (Creative Commons Attribution-NonCommercial).
*   **.gitignore:** Standardized ignore file for the tech stack.
*   **.github/workflows/ci.yml:** GitHub Actions CI/CD pipeline.
*   **.github/CONTRIBUTING.md:** Guidelines for contributors.
*   **.github/ISSUE_TEMPLATE/*.md:** Issue templates (e.g., bug_report.md).
*   **.github/PULL_REQUEST_TEMPLATE.md:** Pull Request template.
*   **.github/SECURITY.md:** Security policy and guidelines.
*   **AGENTS.md:** This file, containing the core AI agent directives.

---

## 6. CHAIN OF THOUGHT (CoT) PROTOCOL
Before generating JSON, perform deep analysis in a `<thinking>` block:
1.  **Audit:** Analyze repo content and purpose.
2.  **Pivot/Archive Decision:** Is it junk? If so, rename to `Archived-...`. If not, PIVOT to elite status.
3.  **Naming Strategy:** Apply `<Product>-<Function>-<Type>` formula.
4.  **Replication Protocol:** Draft the "AI Agent Directives" block.
5.  **File Generation:** Plan the content for all 11 required files (including `PROPOSED_README.md` and `badges.yml`).
6.  **Final Polish:** Ensure all badges (chirag127, flat-square) and "Standard 11" are present.
7.  **Strict Adherence:** Ensure `PROPOSED_README.md` strictly follows the `AGENTS.md` directives.

---

## 7. DYNAMIC URL & BADGE PROTOCOL
**Mandate:** All generated files MUST use the correct dynamic URLs based on the **New Repository Name**.

**Rules:**
1.  **Base URL:** `https://github.com/chirag127/<New-Repo-Name>`
2.  **Badge URLs:** All badges (Shields.io) must point to this Base URL or its specific workflows (e.g., `/actions/workflows/ci.yml`).
3.  **Consistency:** Never use the old/original repository name in links. Always use the new "Apex" name.
4.  **AGENTS.md Customization:** The generated `AGENTS.md` **MUST** be customized for the specific repository's technology stack (e.g., if Rust, use Rust tools; if Python, use Python tools), while retaining the core Apex principles. Do not just copy the generic template; adapt it.

**Current Repository Name:** `Console-Whisperer-AI-DevTools-Copilot-Browser-Extension`

</details>

## 🛠️ Development Standards

### Core Principles

*   **SOLID:** Maintainable and scalable object-oriented design.
*   **DRY (Don't Repeat Yourself):** Avoid redundancy in code and configuration.
*   **YAGNI (You Ain't Gonna Need It):** Implement features only when necessary.
*   **KISS (Keep It Simple, Stupid):** Favor simplicity in design and implementation.

### Linting & Formatting

This project uses **Biome** for linting and formatting to ensure code quality and consistency across the codebase. All code is automatically formatted upon commit via pre-commit hooks.

To manually run the linter and formatter:

bash
# Lint and format all files
npm run lint
# or
yarn lint


### Testing

Comprehensive testing is crucial for maintaining stability and reliability.

*   **Unit & Integration Tests:** Handled by **Vitest**. Run with:
    bash
    npm run test
    # or
    yarn test
    
*   **End-to-End (E2E) Tests:** Performed using **Playwright**. Run with:
    bash
    npm run test:e2e
    # or
    yarn test:e2e
    

## 📜 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. See the [LICENSE](LICENSE) file for details.

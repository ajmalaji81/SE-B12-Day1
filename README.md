# 🤖 GenAI Program — Day 1: Development Environment & Tooling Setup

[![Python 3.14](https://img.shields.io/badge/Python-3.14-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![VS Code](https://img.shields.io/badge/IDE-VS_Code-007ACC?logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/)
[![GitHub Copilot](https://img.shields.io/badge/AI-GitHub_Copilot-8957E5?logo=githubcopilot&logoColor=white)](https://github.com/features/copilot)
[![Platform](https://img.shields.io/badge/OS-Windows_11-0078D4?logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![GitHub](https://img.shields.io/badge/Profile-ajmalaji81-181717?logo=github&logoColor=white)](https://github.com/ajmalaji81)

An all-in-one documentation and setup guide for initializing an AI and Python development environment, configuring automated tooling, managing dependencies, and establishing version control workflows.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [System & Environment Specifications](#-system--environment-specifications)
- [Project File Structure](#-project-file-structure)
- [Step-by-Step Setup Guide](#-step-by-step-setup-guide)
  - [1. Python Runtime Installation](#1-python-runtime-installation)
  - [2. Visual Studio Code & Copilot Configuration](#2-visual-studio-code--copilot-configuration)
  - [3. Isolated Virtual Environment Creation](#3-isolated-virtual-environment-creation)
  - [4. Dependency Management](#4-dependency-management)
- [Script Execution & Verification](#-script-execution--verification)
- [Day 1 Assignment Checklist](#-day-1-assignment-checklist)
- [Author & Profile](#-author--profile)

---

## 📌 Overview

This project serves as the foundation for the **GenAI Program**. It establishes a clean, modern Python environment with AI-assisted developer workflows inside Visual Studio Code.

Key goals completed on Day 1:
* Installed and verified the core Python runtime via command line.
* Configured Visual Studio Code with GitHub Copilot integration.
* Built a virtual environment (`venv`) to keep project packages isolated.
* Created starter modules for script testing (`hello.py`), browser automation (`playwright_basic.py`), and data exploration (`Social.ipynb`).
* Set up Git version control linked to GitHub.

---

## 💻 System & Environment Specifications

| Component | Specification / Version | Status |
| :--- | :--- | :--- |
| **Operating System** | Microsoft Windows [Version 10.0.26100.4652 / Windows 11] | Verified |
| **Python Runtime** | Python 3.14.7 (64-bit AMD64) | Configured & Added to PATH |
| **Code Editor** | Visual Studio Code | Configured |
| **AI Assistant** | GitHub Copilot (Inline suggestions & Chat enabled) | Active |
| **Shells** | PowerShell, Command Prompt (CMD) | Configured |
| **Version Control** | Git & GitHub (`ajmalaji81`) | Synced |

---

## 📂 Project File Structure

```text
GENAI PROGRAM/
├── .vscode/               # Workspace settings and debugger configurations
├── venv/                  # Python isolated virtual environment libraries
├── Social.ipynb           # Jupyter Notebook for interactive experiments and EDA
├── hello.py               # Basic sanity test script
├── playwright_basic.py    # Automation and browser testing script
└── requirements.txt       # Project dependencies and pinned package versions

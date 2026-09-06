# Brody — Your Game Dev Homie.

> **Brody** is an autonomous AI assistant and engine orchestration agent that lives natively inside the Unity Editor. Build games 10x faster without ever leaving your workspace.

[![Unity 2021.3+](https://img.shields.io/badge/Unity-2021.3%2B%20%7C%202022.3%2B%20%7C%20Unity%206-black?logo=unity)](https://unity.com/)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-orange.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Website-Decnet%20Games-blue)](https://decnetgames.com)

---

## Why Brody?

Unlike ordinary LLM wrappers, Brody doesn't just write code snippets in a separate browser tab — **Brody directly drives the Unity Editor**:

- 🧠 **Autonomous Engine Operations**: Creates GameObjects, wires components, modifies transforms, and manages prefabs automatically.
- 🌐 **In-Editor Web Search**: Need documentation, asset references, or forum answers? Brody researches the live web and Unity docs right inside your chat window. You never need to leave Unity.
- 🛡️ **Roslyn Pre-Compiler Shield**: Every C# script synthesized by Brody undergoes pre-compilation AST validation to eliminate compiler errors and deprecated APIs before saving.
- ⚡ **Zero-Latency Streaming**: Powered by high-speed neural reasoning engines with real-time SSE streaming.
- ⏪ **1-Click Safety Checkpoints**: Serialized undo checkpoints ensure you can instantly revert any scene or script modifications with a single click.

---

## Installation via Unity Package Manager (UPM)

### Method 1: Git URL (Recommended)
1. In Unity Editor, open **Window** ➔ **Package Manager**.
2. Click the **`+`** icon in the top-left toolbar.
3. Select **Add package from git URL...**
4. Paste the repository URL:
   ```text
   https://github.com/DecNet-Games/Brody.git

# ⚡ Brody — Autonomous AI Game Developer for Unity

> **Brody** is an autonomous AI assistant and engine orchestration agent that lives natively inside the Unity Editor. Build games 10x faster without ever leaving your workspace.

[![Unity 2021.3+](https://img.shields.io/badge/Unity-2021.3%2B%20%7C%202022.3%2B%20%7C%20Unity%206-black?logo=unity)](https://unity.com/)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-orange.svg)](LICENSE.md)
[![Website](https://img.shields.io/badge/Website-brody.decnetgames.com-blue)](https://brody.decnetgames.com)

---

## 🌟 Why Brody?

Unlike ordinary LLM code generators that only spit out snippets in a separate browser tab, **Brody directly controls and orchestrates the Unity Editor**:

- 🧠 **Autonomous Engine Operations**: Creates GameObjects, wires components, modifies transforms, and manages prefabs automatically.
- 🌐 **In-Editor Web Search**: Need documentation, asset references, or forum answers? Brody researches the live web and Unity docs right inside your chat window. You never need to leave Unity.
- 🛡️ **Roslyn Pre-Compiler Shield**: Every C# script synthesized by Brody undergoes pre-compilation AST validation to eliminate compiler errors and deprecated APIs before saving.
- ⚡ **Zero-Latency Streaming**: Powered by high-speed neural reasoning engines with real-time SSE streaming.
- ⏪ **1-Click Safety Checkpoints**: Serialized undo checkpoints ensure you can instantly revert any scene or script modifications with a single click.

---

## 🚀 Installation via Unity Package Manager (UPM)

### Method 1: Git URL (Recommended)
1. In Unity Editor, open **Window** ➔ **Package Manager**.
2. Click the **+** icon in the top-left toolbar.
3. Select **Add package from git URL...**
4. Paste the repository URL:
   ``text
   https://github.com/DecNet-Games/Brody.git
   ``
5. Click **Add**. Unity will import and initialize Brody AI automatically.

### Method 2: Add to Packages/manifest.json
Open your Unity project's Packages/manifest.json and add to the dependencies object:
``json
{
  "dependencies": {
    "com.decnet.brodyai": "https://github.com/DecNet-Games/Brody.git"
  }
}
``

---

## 🎮 Quickstart

1. **Open the Brody Window**:
   - Go to top menu: **Brody ➔ Open Brody Chat** (or press Ctrl+Shift+B / Cmd+Shift+B).
2. **Connect Your Account**:
   - Click **Brody ➔ Account & Settings ➔ Cloud Sign In**.
   - Enter your Brody Access Key or sign in via browser.
3. **Start Building**:
   - Ask Brody: *"Create a smooth 2D character controller with double-jump, coyote time, and particle effects."*
   - Watch Brody write the C# script, attach components, and configure your scene live.

---

## 🗺️ Upcoming Features (Roadmap)

- 🎨 **Native 3D Mesh & Asset Synthesis**: Generate low-poly 3D models, textures, and PBR materials directly in the Unity scene via Brody's autonomous toolchain.
- 🔌 **Visual Scripting & Shader Graph**: Automated AI node graph authoring and wiring.
- 💻 **Local Model Support (BYOK & Ollama)**: Run private local GGUF models offline.

---

## 📄 License & Support

Brody is developed and maintained by **[Decnet Games](https://brody.decnetgames.com)**.  
For documentation, tutorials, and cloud access keys, visit **[brody.decnetgames.com](https://brody.decnetgames.com)**.
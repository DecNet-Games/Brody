# âš¡ Brody â€” Your Game Dev Homie.

> **The ultimate autonomous AI agent for Unity.** Generates scripts, edits scenes, automates tools, and researches online directly inside the Unity Editor.

[![Unity 2021.3+](https://img.shields.io/badge/Unity-2021.3%2B%20%7C%202022.3%2B%20%7C%20Unity%206-black?logo=unity)](https://unity.com/)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-orange.svg)](LICENSE.md)
[![Website](https://img.shields.io/badge/Website-brody.decnetgames.com-blue)](https://brody.decnetgames.com)

---

## ðŸŒŸ Why Brody?

Unlike ordinary LLM code generators that only spit out snippets in a separate browser tab, **Brody directly controls and orchestrates the Unity Editor**:

- ðŸ§  **Autonomous Engine Operations**: Creates GameObjects, wires components, modifies transforms, and manages prefabs automatically.
- ðŸŒ **In-Editor Web Search**: Need documentation, asset references, or forum answers? Brody researches the live web and Unity docs right inside your chat window. You never need to leave Unity.
- ðŸ›¡ï¸ **Roslyn Pre-Compiler Shield**: Every C# script synthesized by Brody undergoes pre-compilation AST validation to eliminate compiler errors and deprecated APIs before saving.
- âš¡ **Zero-Latency Streaming**: Powered by high-speed neural reasoning engines with real-time SSE streaming.
- âª **1-Click Safety Checkpoints**: Serialized undo checkpoints ensure you can instantly revert any scene or script modifications with a single click.

---

## ðŸš€ Installation via Unity Package Manager (UPM)

### Method 1: Git URL (Recommended)
1. In Unity Editor, open **Window** âž” **Package Manager**.
2. Click the **+** icon in the top-left toolbar.
3. Select **Add package from git URL...**
4. Paste the repository URL:
   ``text
   https://github.com/DecNet-Games/Brody.git
   ``
5. Click **Add**. Unity will import and initialize Brody automatically.

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

## ðŸŽ® Quickstart

1. **Open the Brody Window**:
   - Go to top menu: **Brody âž” Open Brody Chat** (or press Ctrl+Shift+B / Cmd+Shift+B).
2. **Connect Your Account**:
   - Click **Brody âž” Account & Settings âž” Cloud Sign In**.
   - Enter your Brody Access Key or sign in via browser.
3. **Start Building**:
   - Ask Brody: *"Create a smooth 2D character controller with double-jump, coyote time, and particle effects."*
   - Watch Brody write the C# script, attach components, and configure your scene live.

---

## ðŸ—ºï¸ Upcoming Features (Roadmap)

- ðŸŽ¨ **Native 3D Mesh & Asset Synthesis**: Generate low-poly 3D models, textures, and PBR materials directly in the Unity scene via Brody's autonomous toolchain.
- ðŸ”Œ **Visual Scripting & Shader Graph**: Automated AI node graph authoring and wiring.
- ðŸ’» **Local Model Support (BYOK & Ollama)**: Run private local GGUF models offline.

---

## ðŸ“„ License & Support

Brody is developed and maintained by **[Decnet Games](https://brody.decnetgames.com)**.  
For documentation, tutorials, and cloud access keys, visit **[brody.decnetgames.com](https://brody.decnetgames.com)**.
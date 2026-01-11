# 🌌 KNX-Ai-Hub

### *The Central Intelligence Hub for the Ktiseos-Nyx AI Ecosystem*

## 👁️ The Vision
KNX-Ai-Hub is the architectural blueprint and central nervous system for a unified AI ecosystem. Our goal is to bridge the gap between heavy-duty Machine Learning backends and modern, high-performance web interfaces.

The long-term mission is to move away from legacy UI constraints (like Gradio) and rebuild the generative AI experience using a **NextJS/React** frontend communicating with **NodeJS** and **PyTorch** ML stacks.

Future aspects of this will be centered under one hub, but for now we're just linking around to our projects as we scoot through!

---

## 🏗️ Core Roadmap & Future Concepts

### 🚀 The "Forge" Evolution
The centerpiece of this ecosystem's evolution is a planned fork of **Forge** (itself a high-performance fork of Automatic1111). 
- **The Goal:** Gut the Python-heavy Gradio interface.
- **The Replacement:** A bespoke, modular **NextJS/React** frontend.
- **Why?** To provide a professional-grade UX, better state management, and seamless integration with the rest of the KNX toolset.

### 🛠️ Dataset & Training Paradigm
Transitioning our CLI and Python-based dataset tools into full-stack web applications to streamline the LoRA and Model training pipeline.

---

## 🔗 The Ecosystem (Current Repositories)

This hub connects several specialized tools currently under development or in maintenance:

### 🧠 Training & ML
*   **[KNX Trainer](https://github.com/Ktiseos-Nyx/Ktiseos-Nyx-Trainer):** The flagship training suite for the ecosystem.
*   **[Dataset Tools](https://github.com/Ktiseos-Nyx/Dataset-Tools):** Essential utilities for data prep (Currently migrating to a Next/React implementation).
*   **[SD WebUI Merger](https://github.com/Ktiseos-Nyx/sdwebui-batteriesincluded-merger):** Specialized model merging tools for SD workflows.

### 🤖 Chat & Interaction
*   **[Plural Chat](https://github.com/Ktiseos-Nyx/plural_chat):** Advanced multi-persona/agent chat interface.
*   **[Prompt Inspector Bot](https://github.com/Ktiseos-Nyx/PromptInspectorBot):** Our custom version of the prompt metadata analysis bot.

### 🛠️ Utilities & Infrastructure
*   **[HuggingFace Backup](https://github.com/Ktiseos-Nyx/HuggingFace_Backup):** Redundancy and safety for weights and datasets.
*   **[ComfyUI Node Finder](https://github.com/Ktiseos-Nyx/ComfyUI-Node-Finder):** Managed by **Quadmoon** — an essential tool for navigating the custom node sprawl of ComfyUI.

---

## 💻 Tech Stack (Target)

| Layer | Technology |
| :--- | :--- |
| **Frontend** | NextJS 15+, React, TailwindCSS, Lucide Icons |
| **Backend** | NodeJS (Orchestration), FastAPI (ML Gateway) |
| **ML Engine** | PyTorch, Forge/A1111 Backends |
| **Data/Storage** | HuggingFace API, Local ML Stacks |

---

## 👥 Team
- **Designer:** [Duskfall](https://github.com/duskfallcrew)
- **Supervisor:** [Quadmoon](https://github.com/Ktiseos-Nyx/ComfyUI-Node-Finder)

---

> *"Don't get lost in the code; remember the vision."* 
> This MD serves as a reminder that every small tool is a brick in a much larger, unified AI structure.

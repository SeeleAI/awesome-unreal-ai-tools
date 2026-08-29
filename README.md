<div align="center">

<h1>Awesome Unreal AI Tools</h1>
<img src="social-preview.svg" alt="Awesome Unreal AI Tools — curated by SeeleAI" width="100%">
<p>A curated collection of open-source Unreal Engine AI, Agent, MCP, Skill, automation, and generative workflows.</p>
<p><img src="https://img.shields.io/badge/Unreal%20Engine-5.x-0E1128?logo=unrealengine&logoColor=white" alt="Unreal Engine"> <img src="https://img.shields.io/badge/Curated%20by-SeeleAI-7C3AED" alt="Curated by SeeleAI"> <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a></p>
<p><a href="README.md"><strong>English</strong></a> · <a href="README_zh-CN.md">中文</a></p>
</div>

---

## Build with AI

Want to prototype an Unreal game faster? Try [SeeleAI Unreal Game Creator](https://www.seeles.ai/features/create/unreal-game).

## Featured AI tools

> ★ Star counts checked on 2026-08-29; they may change over time.

### 🧩 Editor toolsets

- **[VibeUE](https://github.com/kevinpbuckley/VibeUE)** · ★ 638 · MIT · UE5.8+

  An Unreal Engine vibe-coding tool that combines MCP-based editor control with an AI-assisted development workflow. It is suited to natural-language project interaction, rapid prototyping, and exploring how an AI toolset can sit inside the editor workflow.
- **[UnrealBridge](https://github.com/TornLux/UnrealBridge)** · ★ 297 · MIT · UE5

  A typed control surface that lets AI agents introspect assets, author Blueprints and AnimBPs, and edit levels with reactive events and undoable writes. It is useful for evaluating safer, more structured editor automation than raw command execution.

### 📚 Agent skills

- **[unreal-engine-skills](https://github.com/quodsoler/unreal-engine-skills)** · ★ 325 · MIT · UE5

  A structured set of 27 Unreal C++ skills covering gameplay, rendering, networking, animation, and more. It works with Claude Code, Cursor, Windsurf, and any agent that supports the Agent Skills specification.

### 💬 Claude integrations

- **[UnrealClaude](https://github.com/Natfii/UnrealClaude)** · ★ 890 · MIT (README badge) · UE5.7

  Claude Code CLI integration for Unreal Engine 5.7 with built-in UE documentation context directly in the editor. Use it to experiment with AI-assisted code understanding and implementation inside a real Unreal project.

### 🔌 MCP servers & bridges

- **[unreal-mcp](https://github.com/chongdashu/unreal-mcp)** · ★ 2,067 · MIT (README declaration) · UE5.5+

  An MCP server that lets AI assistant clients such as Cursor, Windsurf, and Claude Desktop control Unreal Engine through natural language. It provides a useful reference for designing an AI-to-editor command loop.
- **[UnrealMCP](https://github.com/kvick-games/UnrealMCP)** · ★ 604 · MIT · UE5

  An MCP bridge that allows AI agents to control Unreal. It is useful for comparing the responsibilities of the agent, MCP transport, and Unreal-side bridge in an editor automation workflow.
- **[Unreal_mcp](https://github.com/ChiR24/Unreal_mcp)** · ★ 846 · MIT · UE5

  A comprehensive MCP server built with TypeScript and C++ that uses Unreal's native C++ Automation Bridge plugin. It is a useful reference for exposing native editor automation capabilities to AI assistants.
- **[UE5-MCP](https://github.com/VedantRGosavi/UE5-MCP)** · ★ 424 · MIT template (placeholder) · UE5

  An MCP integration for Unreal Engine 5 that focuses on making engine operations available to an AI client. It is a good fit for testing a focused agent-controlled setup with a relatively small surface area.
- **[ue-mcp](https://github.com/db-lyon/ue-mcp)** · ★ 295 · MIT · UE5

  A complete Unreal Engine development toolkit exposed as MCP tools. It is useful when comparing a broader tool surface for project inspection, asset operations, and editor automation.
- **[monolith](https://github.com/tumourlove/monolith)** · ★ 285 · MIT · UE5.7+

  A native C++ MCP plugin offering AI assistants read/write access across Blueprints, Materials, Niagara, Animation, Mesh, AI, GAS, UI, Audio, and more. Its large namespace coverage makes it a reference for ambitious in-editor agent workflows.
- **[Unreal-MCP](https://github.com/IvanMurzak/Unreal-MCP)** · ★ 27 · Apache-2.0 · UE5.7+

  An open-source MCP server connecting agents such as Claude, Cursor, GitHub Copilot, and Gemini to the Unreal editor and runtime through a C++ plugin and .NET sidecar.

### ✨ Generative AI

- **[UnrealGenAISupport](https://github.com/prajwalshettydev/UnrealGenAISupport)** · ★ 638 · MIT · UE5

  A UE5 plugin focused on LLM and generative-AI model integration, with MCP support for connecting AI capabilities to Unreal workflows. It is aimed at prototyping AI-powered game features and experimenting with model-driven interactions.
- **[OpenAI-Api-Unreal](https://github.com/KellanM/OpenAI-Api-Unreal)** · ★ 769 · MIT · UE5

  An Unreal integration for the OpenAI API, useful for prototyping chat, completion, and model-assisted gameplay features inside an Unreal project. Check the repository's supported endpoints and setup requirements before use.
- **[Autonomix](https://github.com/PRQELT/Autonomix)** · ★ 204 · MIT · UE5

  An AI developer for Unreal Engine that aims to create Blueprints, C++, levels, materials, widgets, and other editor content through natural language. It is useful for studying an agent that acts across multiple Unreal authoring surfaces.

### 🧭 Simulation & embodied AI

- **[AirSim](https://github.com/microsoft/AirSim)** · ★ 18,427 · MIT · UE4/Unity

  Microsoft's open-source Unreal/Unity simulator for autonomous vehicles, drones, and robotics. Its sensor, vehicle-control, and virtual-environment capabilities make it a substantial foundation for embodied-AI experiments and simulation research.

### 🧠 Cross-engine agent skills

- **[awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills)** · ★ 726 · Apache-2.0 · UE4/UE5 entries

  A curated set of 67 portable game-development skills covering Unreal, Unity, Godot, and other engines. The Unreal entries are useful when an agent needs a routed, reusable skill format instead of one-off prompts.

## SeeleAI projects

- **[seele-scatter-regions](https://github.com/SeeleAI/seele-scatter-regions)** · ★ 6 · MIT · Not stated

  An open-source SeeleAI Unreal project centered on region-based scattering workflows. Review the repository for the current implementation, intended editor workflow, and integration details.
- **[Seele-art-unreal](https://github.com/SeeleAI/Seele-art-unreal)** · ★ 2 · MIT · Not stated

  An open-source SeeleAI Unreal art and workflow project. It is listed here as a public reference for Unreal art-oriented automation and should be evaluated through its repository documentation before adoption.

## Curation principles

This index links to public projects and preserves attribution to their original authors. Check each project's license, supported Unreal Engine versions, dependencies, activity, and documentation before use. We do not include SeeleAI's private repositories or closed-source services.

## Contributing

Submit a public repository URL, license information, supported UE version, and a short description of the AI or automation workflow.

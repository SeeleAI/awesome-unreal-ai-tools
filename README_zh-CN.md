<div align="center">

<h1>Unreal AI 工具精选</h1>
<p>由 SeeleAI 精选维护的 Unreal Engine AI、Agent、MCP、Skill、自动化和生成式工作流集合。</p>
<p><img src="https://img.shields.io/badge/Unreal%20Engine-5.x-0E1128?logo=unrealengine&logoColor=white" alt="Unreal Engine"> <img src="https://img.shields.io/badge/Curated%20by-SeeleAI-7C3AED" alt="Curated by SeeleAI"> <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="许可证：MIT"></a></p>
<p><a href="README.md">English</a> · <a href="README_zh-CN.md"><strong>中文</strong></a></p>
</div>

---

## 使用 AI 创建 Unreal 游戏

想更快开始 Unreal 游戏原型开发？试试 [SeeleAI Unreal Game Creator](https://www.seeles.ai/features/create/unreal-game)。

## 精选 AI 工具

### 🧩 编辑器工具集

- **[VibeUE](https://github.com/kevinpbuckley/VibeUE)** · MIT · UE5.8+

  面向 Unreal Engine 的 Vibe Coding 工具，将基于 MCP 的编辑器控制与 AI 辅助开发流程结合起来，适合自然语言操作项目、快速原型和探索 AI 工具集如何融入编辑器工作流。

### 📚 Agent Skill

- **[unreal-engine-skills](https://github.com/quodsoler/unreal-engine-skills)** · MIT · UE5

  收集 27 个 Unreal C++ Skill，覆盖 Gameplay、渲染、网络、动画等方向，兼容 Claude Code、Cursor、Windsurf 及其他支持 Agent Skills 规范的 Agent。

### 💬 Claude 集成

- **[UnrealClaude](https://github.com/Natfii/UnrealClaude)** · MIT · UE5.7

  面向 Unreal Engine 5.7 的 Claude Code CLI 集成，将 UE 文档上下文直接提供给编辑器，适合在真实 Unreal 工程中尝试 AI 辅助代码理解和实现。

### 🔌 MCP 服务与桥接

- **[unreal-mcp](https://github.com/chongdashu/unreal-mcp)** · 许可证待核验

  通过 MCP 让 Cursor、Windsurf、Claude Desktop 等 AI 客户端使用自然语言控制 Unreal Engine，可参考其 AI 到编辑器的命令循环设计。
- **[UnrealMCP](https://github.com/kvick-games/UnrealMCP)** · 许可证待核验

  连接 AI Agent 与 Unreal 的 MCP 桥接，适合比较 Agent、MCP 传输层和 Unreal 侧桥接在编辑器自动化工作流中的职责划分。
- **[Unreal_mcp](https://github.com/ChiR24/Unreal_mcp)** · 许可证待核验

  使用 TypeScript 和 C++ 构建的 MCP 服务，通过 Unreal 原生 C++ Automation Bridge 插件工作，适合研究如何将原生编辑器自动化能力暴露给 AI 助手。
- **[UE5-MCP](https://github.com/VedantRGosavi/UE5-MCP)** · 许可证待核验

  面向 Unreal Engine 5 的 MCP 集成，重点是将引擎操作提供给 AI 客户端，适合测试功能边界相对聚焦的 Agent 控制方案。

### ✨ 生成式 AI

- **[UnrealGenAISupport](https://github.com/prajwalshettydev/UnrealGenAISupport)** · 许可证待核验

  面向 LLM 和生成式 AI 模型集成的 UE5 插件，并支持通过 MCP 连接 AI 能力与 Unreal 工作流，适合原型验证 AI 驱动的游戏功能和模型驱动的交互。

### 🧭 仿真与具身智能

- **[AirSim](https://github.com/microsoft/AirSim)** · MIT

  Microsoft 开源的 Unreal/Unity 自动驾驶、无人机和机器人仿真器，提供传感器、车辆控制和虚拟环境能力，适合作为具身智能实验与仿真研究基础。

## SeeleAI 项目

- **[seele-scatter-regions](https://github.com/SeeleAI/seele-scatter-regions)**

  SeeleAI 开源的 Unreal 区域散布工作流项目，具体实现、编辑器流程和集成方式请以仓库当前文档为准。
- **[Seele-art-unreal](https://github.com/SeeleAI/Seele-art-unreal)**

  SeeleAI 开源的 Unreal 美术与工作流项目，作为 Unreal 美术方向自动化的公开参考，采用前请先查看仓库文档确认当前范围和使用方式。

## 收录原则

本索引链接公开项目并保留原作者归属。使用前请查看项目许可证、支持的 Unreal Engine 版本、依赖、活跃度和文档；不收录 SeeleAI 的私有仓库和闭源服务。

## 贡献

提交公开仓库链接、许可证、支持的 UE 版本和 AI 或自动化工作流简介。

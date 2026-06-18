# Claude Code 中文版教程

[Claude Code](https://www.claudezip.cn?utm_source=github&utm_medium=article&utm_campaign=claude-code-qidongqi) 是 Anthropic 推出的 AI 编程助手，具备强大的自动编程能力。但官方版本在中文环境下门槛较高：安装依赖 Node.js、npm，要求熟悉命令行操作，且仅支持英文交互。

这个项目旨在解决以上痛点，帮助中文用户在中文电脑上**零门槛、零配置**一键使用 Claude Code。

---

## 项目目标

### 一、中文环境，一键上手


自行安装 Claude Code 需要配置运行时环境、设置环境变量、确保网络连通——对非专业开发者极不友好。本项目提供的 **[Claude Code 中文版启动器](https://www.claudezip.cn?utm_source=github&utm_medium=article&utm_campaign=claude-code-qidongqi) 免安装、免配置，下载即可使用。**

从 [认识 Claude Code](how-to-use-claude-code.md) 开始，跟着 [3 分钟上手教程](getting-started.md) 发出第一条指令，再通过 [实战演练](walk-through.md) 看懂 AI 的每一步操作。无论你用的是 [Windows](install-claude-code-on-windows.md)、[macOS](install-claude-code-on-macos.md) 还是 [Linux](install-claude-code-on-linux.md)，都有图文并茂的安装指南。

### 二、自带密钥，方便使用 DeepSeek v4 模型

Claude 官方模型能力出色，但调用成本较高。DeepSeek V4 在保持出色推理能力的同时，**API 价格仅为 Claude Opus 的约二十分之一**。

本项目支持 **[BYOK（自带密钥）功能](bring-your-own-deepseek-key.md)**——只需在图形界面中填入 DeepSeek API 密钥，即可一键切换模型，无需修改环境变量、无需搭建中转服务。同时支持多个模型密钥登记，按任务灵活切换。

### 三、Windows 用户也能顺畅使用

Claude Code 本质是终端交互程序（TUI），对 Windows 用户不够友好。本项目专门针对 Windows 环境做了深度适配：

- **[Windows 免安装教程](install-claude-code-on-windows.md)**：从下载到运行，每一步都有截图指引；涵盖网络连接、系统时钟、防火墙拦截等常见问题的排查方案。
- **[项目配色功能](project-based-color-scheme.md)**：支持多窗口并行开发，为不同项目设置专属配色，一眼区分任务，告别窗口混乱。
- **[文件面板](use-file-explorer.md)**：可视化的项目文件树，双击即可引用，彻底解决中文文件名输入和长路径记忆的困扰。

### 四、告别繁复键入，语音直接操控

AI 已经解放了写代码的双手，但"打字下指令"本身仍是时间成本。本项目内置了 **[专为 AI 操控设计的语音输入模块](use-voice-input.md)**：

- 想到什么说什么，说错了也没关系——系统会根据上下文自动整理、修正
- 中英文混合输入精准识别，编程术语、文件名不会被拆碎
- 最长 5 分钟连续录音，节奏完全由你掌控

---

## 文档目录

### 快速上手 Claude Code

- [在 Windows 系统上免安装地使用 Claude Code](install-claude-code-on-windows.md)
- [在苹果 macOS 系统上免安装地使用 Claude Code](install-claude-code-on-macos.md)
- [在 Linux 上免安装地使用 Claude Code](install-claude-code-on-linux.md)

### 使用指南

- [3 分钟上手 Claude Code：让 AI 成为你的超级编程助手](getting-started.md)
- [实战演练：5分钟看懂 Claude Code 在干嘛](walk-through.md)
- [理解 Claude Code 的上下文与会话管理机制](understand-context.md)
- [如何在 Claude Code 中引用文件和目录](include-project-files-in-prompts.md)
- [简单直观的文件操作：使用项目文件面板](use-file-explorer.md)
- [任务历史面板：浏览 Claude Code 的完整任务对话，让 AI 编程更连贯](use-task-history-panel.md)
- [常用提示词面板：让 Claude Code 更听你的指挥](use-snippets-panel.md)
- [使用 Claude Code 的语音输入：想到什么说什么，好用不止亿点点](use-voice-input.md)
- [提升多任务开发效率：妙用项目配色与视觉管理功能](project-based-color-scheme.md)
- [免配置，在 Claude Code 直接使用 Deepseek v4 模型](bring-your-own-deepseek-key.md)

### 业界观察

- [来自 Andrej Karpathy 的提醒：未来的程序员分两种：会用 AI 写代码的，和被淘汰的](karpathy-ai-coding-leverage.md)
- [命令行（CLI）就是你所需的一切](cli-is-all-you-need.md)
- [生产力暴涨 150%，我彻底卸载了 IDE：对话 Claude Code 创建者 Boris Cherny](uninstall-ide-productivity-150-gain.md)
- [几周的工作量，20分钟干完！Redis 之父：手动敲代码的时代永远终结了](antirez-claude-code-redis-productivity.md)
- [2026的AI，是反对唯证书主义者的春天](prosperous-spring-for-anti-credentialists.md)

# LinkClaw 本机智能体 / Local Agent Bridge

## 中文

LinkClaw 是 LinkGo 的本机智能体桥接模块。它用于连接 OpenClaw 和 Hermes Agent，让智能体在 LinkGo 的本机沙箱边界内处理文件、目录、命令和多步骤任务。

### 为什么需要 LinkClaw

普通聊天适合回答问题；本机智能体适合执行任务。LinkClaw 的价值在于把两者连接起来：

- 用户仍然用自然语言描述目标。
- LinkGo 提供模型、术语库、记忆库、文件管道和权限边界。
- OpenClaw / Hermes 负责更开放的本机智能体执行。
- 结果回到 LinkGo 聊天界面，并保留折叠日志和文件产物。

### 它能做什么

- 读取和分析本机工作区文件。
- 调用 LinkGo 文件翻译管道，处理保留格式翻译。
- 运行本机命令或脚本。
- 生成文件、报告、表格、PPT 或小工具。
- 执行多轮、多步骤任务。
- 使用主项目选择的模型、提示词、术语库、记忆库和温度设置。

### 权限模式

| 权限 | 描述 |
| --- | --- |
| 只读 | 只能读取和分析文件，适合总结、校对、检查 |
| 标准 | 可以生成结果文件，适合常规文件处理 |
| 完整 | 可以执行更开放的本机任务，适合明确授权的自动化 |

### 安全边界

LinkClaw 只应在本机使用。局域网或云端访问时，不应开放沙箱控制、本机命令和系统操作能力。

## English

LinkClaw is LinkGo's local agent bridge. It connects LinkGo with OpenClaw and Hermes Agent so that agents can process local files, directories, commands, and multi-step tasks inside LinkGo's local sandbox boundary.

### Why LinkClaw Exists

Chat is good for answers. Local agents are good for execution. LinkClaw connects both:

- Users describe goals in natural language.
- LinkGo provides models, glossaries, memories, file pipelines, and permission boundaries.
- OpenClaw / Hermes handle broader local agent execution.
- Results return to LinkGo chat with collapsible logs and generated artifacts.

### What It Can Do

- Read and analyze local workspace files.
- Use LinkGo file pipelines for format-preserving translation.
- Run local commands or scripts.
- Generate files, reports, tables, decks, or small tools.
- Execute multi-turn and multi-step tasks.
- Reuse selected models, custom prompts, glossaries, memories, and temperature settings from LinkGo.

### Permission Modes

| Mode | Description |
| --- | --- |
| Read-only | Read and analyze files; best for summaries and reviews |
| Standard | Create output files; best for normal file processing |
| Full | Run broader local tasks; use only with clear authorization |

### Safety Boundary

LinkClaw is intended for local use only. Sandbox control, local commands, and system operations should not be exposed to LAN or public cloud visitors.

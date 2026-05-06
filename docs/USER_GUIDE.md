# 用户指南 / User Guide

## 中文

### 1. 快速开始

LinkGo 的使用方式接近聊天，但结果不止聊天文本。你可以上传文件、选择本机目录、选择模型，然后直接描述目标。

推荐步骤：

1. 打开 LinkGo。
2. 选择在线模型或本地模型。
3. 上传文件，或选择本机沙箱工作区。
4. 输入任务，例如“翻译成日语，保留格式和排版”。
5. 查看回答，下载结果文件。
6. 如果结果需要继续处理，直接追问。

### 2. 文件翻译

你可以这样说：

- 把这个 Word 翻译成英文，保留格式。
- 把这个 PPT 翻译成韩语，不要超出文本框。
- 把这个 Excel 翻译成日语，保留单元格样式。
- 翻译这个字幕文件，保留时间轴。
- 把这个 PDF 翻译成中文，并输出可下载结果。

LinkGo 会尽量使用原格式写回能力，而不是把文件粗暴拆成纯文本。

### 3. 译文校对

你可以上传：

- 一个双语对照文件。
- 一个原文文件和一个译文文件。
- 一个表格里左边原文、右边译文的文件。

然后输入：

- 检查这个文件翻译得怎么样。
- 帮我校对，输出表格结果。
- 重点检查数字、术语、漏译、错译和语法问题。

校对结果通常会包含问题类型、严重程度、原文片段、译文片段、问题说明和修改建议。

### 4. 本机沙箱

本机沙箱适合处理电脑上的目录和文件。常见任务：

- 清理工作区临时文件。
- 读取目录里的文件并生成报告。
- 把多个文件批量处理成统一格式。
- 调用 LinkClaw，让 OpenClaw / Hermes 执行更开放的本机任务。

权限模式建议：

| 权限 | 适合场景 |
| --- | --- |
| 只读 | 分析、总结、校对、查看文件 |
| 标准 | 生成结果文件、整理输出 |
| 完整 | 执行命令、调用工具、批量处理本机文件 |

### 5. 模型选择

你可以根据任务选择模型：

- 普通聊天、摘要：选择更快的模型。
- 复杂校对、长文档、代码和智能体任务：选择能力更强的模型。
- 隐私敏感、本机优先：选择本地模型。

### 6. 结果交付

LinkGo 会尽量把结果整理成：

- 聊天界面可读结论。
- 可下载文件。
- 可折叠查看的运行日志。
- 可继续追问的上下文。

## English

### 1. Quick Start

LinkGo feels like a chat interface, but it is designed to produce deliverables, not just messages.

Suggested flow:

1. Open LinkGo.
2. Select an online or local model.
3. Upload files or choose a local sandbox workspace.
4. Describe your task, for example: “Translate into Japanese and preserve formatting.”
5. Review the answer and download the output files.
6. Continue with follow-up instructions if needed.

### 2. File Translation

Example requests:

- Translate this Word document into English and keep formatting.
- Translate this PowerPoint into Korean without overflowing text boxes.
- Translate this Excel file into Japanese and keep cell styles.
- Translate this subtitle file and preserve timing.
- Translate this PDF into Chinese and provide a downloadable result.

LinkGo aims to use format-aware writeback pipelines rather than converting everything into plain text.

### 3. Translation Review

You can upload:

- A single bilingual file.
- A source file and a translated file.
- A table where the left column is the source and the right column is the translation.

Example requests:

- Check the translation quality of this file.
- Proofread this and output a review table.
- Focus on numbers, terminology, omissions, mistranslations, and grammar issues.

The review output may include issue type, severity, source excerpt, target excerpt, explanation, and suggested revision.

### 4. Local Sandbox

The local sandbox is designed for local directories and files. Common tasks include:

- Cleaning temporary workspace files.
- Reading local files and generating a report.
- Batch processing files into a unified format.
- Using LinkClaw to let OpenClaw / Hermes handle broader local tasks.

Permission modes:

| Mode | Best for |
| --- | --- |
| Read-only | Analysis, summary, review, file inspection |
| Standard | Creating result files and structured outputs |
| Full | Running commands, using tools, batch processing local files |

### 5. Model Selection

Choose models based on the task:

- Fast models for normal chat and summaries.
- Stronger models for complex review, long documents, coding, and agent tasks.
- Local models for privacy-sensitive or local-first workflows.

### 6. Delivery

LinkGo aims to provide:

- A readable answer in chat.
- Downloadable output files.
- Collapsible execution logs.
- Context that can be continued in follow-up messages.

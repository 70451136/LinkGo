# 常见问题 / FAQ

## 中文

### LinkGo 是什么？

LinkGo 是一个本机优先的 AI 文件翻译与智能体工作台。它面向真实文件工作流，重点是翻译、校对、保留格式、术语记忆和本机智能体协作。

### 这个仓库为什么没有源码？

当前仓库作为产品介绍和发布包入口，不直接放完整源码。后续安装包、便携包和版本说明会通过 Releases 发布。

### 支持哪些格式？

重点支持 Word、Excel、PowerPoint、PDF、字幕、图片 OCR、视频字幕、EPUB、TXT、Markdown、SDLXLIFF、DXF/DWG 等。不同格式的保留程度会因文件复杂度而不同。

### 能完全保留原格式吗？

LinkGo 会尽量保留格式，但复杂文件仍建议人工复核。例如复杂 PDF、嵌套表格、扫描件、特殊字体、复杂 PPT 动画和跨平台字体差异都可能影响结果。

### 可以用本地模型吗？

可以。LinkGo 目标支持 Ollama、LM Studio、vLLM 等本地模型，也支持多家在线模型。

### LinkClaw 是什么？

LinkClaw 是 LinkGo 的本机智能体桥接模块，用于接入 OpenClaw / Hermes Agent，让它们在本机沙箱里处理文件和任务。

### 数据会上传吗？

这取决于你选择的模型和功能。本地沙箱目录应保持在本机；使用在线模型或联网搜索时，相关文本可能会发送给外部服务。处理敏感文件时建议使用本地模型并关闭联网。

### 如何反馈问题？

提交 Issue，说明操作系统、文件类型、任务目标、预期结果、实际结果和脱敏日志。不要上传真实客户文件或密钥。

## English

### What is LinkGo?

LinkGo is a local-first AI workspace for file translation and agent-assisted workflows. It focuses on real documents, layout preservation, translation review, terminology memory, and local agent collaboration.

### Why does this repository not contain the source code?

This repository is currently used as the product page and release hub. Full source code is not hosted here. Installers, portable packages, and release notes will be published through Releases.

### Which formats are supported?

LinkGo focuses on Word, Excel, PowerPoint, PDF, subtitles, OCR images, video subtitles, EPUB, TXT, Markdown, SDLXLIFF, DXF/DWG, and more. Preservation quality depends on file complexity.

### Can it perfectly preserve formatting?

LinkGo aims to preserve formatting as much as possible, but complex files still need human review. Complex PDFs, nested tables, scanned documents, special fonts, complex PowerPoint animations, and cross-platform font differences may affect results.

### Can I use local models?

Yes. LinkGo is designed to support local providers such as Ollama, LM Studio, and vLLM, as well as multiple online providers.

### What is LinkClaw?

LinkClaw is LinkGo's local agent bridge for OpenClaw and Hermes Agent. It lets agents process local files and tasks inside a controlled local sandbox.

### Will my data be uploaded?

It depends on your model and feature choices. Local sandbox directories should stay local. If you use online models or web search, relevant text may be sent to external services. For sensitive files, use local models and disable network features.

### How should I report issues?

Open an Issue with your operating system, file type, task goal, expected result, actual result, and sanitized logs. Do not upload real customer files or secrets.

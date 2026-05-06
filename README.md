# LinkGo

**本机智能体与多格式 AI 翻译工作台**  
**A local-first AI workspace for document translation, layout-preserving delivery, and agent-assisted file workflows**

[中文](#中文介绍) · [English](#english-overview) · [发布包 Releases](https://github.com/70451136/LinkGo/releases) · [反馈 Issues](https://github.com/70451136/LinkGo/issues)

> 当前仓库是 LinkGo 的产品介绍与发布包入口，不直接放置完整源码。后续打包好的 Windows / Linux 发布包会放在 GitHub Releases。  
> This repository is the product page and release hub for LinkGo. It does not host the full source code. Packaged Windows / Linux releases will be published through GitHub Releases.

---

## 中文介绍

LinkGo 面向译员、本地化团队、企业知识团队、内容创作者和需要本机自动化的高级用户。它把多格式文件翻译、原格式写回、术语库、翻译记忆、本地模型、在线模型和本机沙箱智能体整合到一个桌面级 Web 工作台里。

你不需要先学习复杂命令。上传文件或选择本机目录后，直接说：

- “把这个 Word 翻译成日语，保留格式和排版。”
- “检查这个双语译文质量，用表格输出校对结果。”
- “把这个 PPT 翻译成韩语，不要超出文本框。”
- “从这个 Word 中提取所有表格，转成 Excel。”
- “总结这批文件，列出重点和风险。”
- “让本机智能体处理这个工作区里的文件。”

LinkGo 的目标不是只生成一段聊天文本，而是把复杂任务整理成可交付结果：译文文件、校对报告、表格、PPT、字幕、过程日志和可继续追问的上下文。

### 核心能力

#### 1. 多格式保留排版翻译

LinkGo 关注真实办公文件，而不是只翻译纯文本。它会尽量保留：

- Word 的标题、正文、表格、页眉页脚、编号、批注和样式。
- Excel 的单元格样式、列宽、行高、工作表结构、批注和富文本。
- PowerPoint 的文本框、形状、层级、页面边界和演示版式。
- PDF、字幕、EPUB、Markdown、TXT、图片 OCR、视频字幕等多种格式的结构信息。

#### 2. 译文校对与质量检查

支持单文件双语对照，也支持原文文件 + 译文文件。适合检查合同、技术文档、医学材料、产品资料、商务通知和多领域测试稿。校对时会关注：

- 漏译、错译、疑似未译。
- 数字、日期、单位、金额、编号不一致。
- 专名、术语、缩写和行业表达不统一。
- 语法、语气、可读性和交付风险。
- 原文译文结构对齐是否可靠。

#### 3. 术语库、翻译记忆与长期记忆

LinkGo 可以把团队术语、历史译法、用户偏好和项目风格沉淀为可复用资产。翻译、校对、附件问答和本机智能体任务都可以复用这些上下文，让后续交付越来越稳定。

#### 4. LinkClaw 本机智能体

LinkClaw 是 LinkGo 的本机智能体桥接模块，可接入 OpenClaw / Hermes Agent。它会把主项目的模型选择、自定义提示词、术语库、记忆库、温度、上下文条数和权限模式传给两大智能体，让它们在本机沙箱边界内处理目录、文件、命令和多步骤任务。

#### 5. 在线模型与本地模型

LinkGo 支持多种在线模型和本地模型。你可以在不同任务中选择更快、更强或更私密的模型：

- 在线模型：OpenAI、OpenRouter、DeepSeek、火山方舟、阿里云、智谱、月之暗面、百度、硅基流动等。
- 本地模型：Ollama、LM Studio、vLLM 等。

### 典型使用场景

| 场景 | 用户怎么说 | LinkGo 交付 |
| --- | --- | --- |
| 文件翻译 | 把这个 Word 翻译成日语，保留格式 | 可下载译文文件 |
| 译文校对 | 检查这个双语文件翻译得怎么样 | 校对报告、问题表格 |
| PPT 翻译 | 翻译 PPT，不要越界 | 保留版式的 PPTX |
| 表格提取 | 把 Word 里的表格转成 Excel | XLSX 文件 |
| 字幕处理 | 翻译视频字幕并保留时间轴 | 字幕文件或视频字幕结果 |
| 本机沙箱 | 清理工作区 / 生成小工具 / 批量处理文件 | 本机智能体执行结果 |
| 资料整理 | 总结这批文件，列出重点 | 结构化摘要 |

### 发布包说明

本仓库目前不提供完整源码下载。正式安装包、便携包和更新说明会发布在 [Releases](https://github.com/70451136/LinkGo/releases)。  
如果你希望关注发布进度，可以 Watch 本仓库。

### 中文文档

- [用户指南 / User Guide](docs/USER_GUIDE.md)
- [功能总览 / Feature Overview](docs/FEATURES.md)
- [使用场景 / Use Cases](docs/USE_CASES.md)
- [LinkClaw 本机智能体 / Local Agent Bridge](docs/LINKCLAW.md)
- [隐私与本机边界 / Privacy](docs/PRIVACY.md)
- [常见问题 / FAQ](docs/FAQ.md)
- [发布包说明 / Releases](docs/RELEASES.md)
- [路线图 / Roadmap](docs/ROADMAP.md)

---

## English Overview

LinkGo is a local-first AI workspace for translators, localization teams, enterprise knowledge teams, content creators, and advanced users who need agent-assisted local file workflows.

Instead of only producing chat messages, LinkGo focuses on real deliverables: translated files, review reports, structured tables, PowerPoint decks, subtitles, logs, and follow-up context that you can continue working with.

### What You Can Ask LinkGo

- “Translate this Word document into Japanese and preserve its formatting.”
- “Review this bilingual translation and output the findings as a table.”
- “Translate this PowerPoint into Korean without overflowing text boxes.”
- “Extract all tables from this Word file and convert them into Excel.”
- “Summarize these files and list key risks.”
- “Let the local agent process files in this workspace.”

### Key Capabilities

#### 1. Format-Preserving Document Translation

LinkGo is designed for real office documents, not only plain text. It aims to preserve:

- Word headings, paragraphs, tables, headers, footers, numbering, comments, and styles.
- Excel cell styles, column widths, row heights, worksheets, comments, and rich text.
- PowerPoint text boxes, shapes, hierarchy, slide boundaries, and layout.
- PDF, subtitles, EPUB, Markdown, TXT, OCR images, video subtitles, and other structured formats.

#### 2. Translation Review and QA

LinkGo can review a single bilingual file or a pair of source/target files. It helps identify:

- Missing translations, mistranslations, and untranslated segments.
- Number, date, unit, amount, and identifier inconsistencies.
- Terminology, proper noun, abbreviation, and domain-style issues.
- Grammar, tone, readability, and delivery risks.
- Whether source and target structures are aligned reliably.

#### 3. Terminology, Translation Memory, and Long-Term Memory

LinkGo can reuse terminology, previous translations, user preferences, and project style memories across translation, review, attachment Q&A, and local agent tasks.

#### 4. LinkClaw Local Agent Bridge

LinkClaw connects LinkGo with OpenClaw and Hermes Agent. It passes model selection, custom prompts, glossaries, memory libraries, temperature, context limits, and permission modes into the selected agent so it can work inside a local sandbox.

#### 5. Online and Local Models

LinkGo is designed to work with both hosted and local models:

- Online providers: OpenAI, OpenRouter, DeepSeek, Volcano Ark, Alibaba Cloud, Zhipu AI, Moonshot, Baidu, SiliconFlow, and more.
- Local providers: Ollama, LM Studio, vLLM, and other local runtimes.

### Common Workflows

| Workflow | Example Request | Output |
| --- | --- | --- |
| Document translation | Translate this Word file into Japanese and preserve formatting | Downloadable translated file |
| Translation review | Check this bilingual file and list translation issues | Review report and issue table |
| PPT translation | Translate this deck without overflowing text boxes | Layout-preserved PPTX |
| Table extraction | Extract tables from this Word document into Excel | XLSX file |
| Subtitle processing | Translate video subtitles and keep timing | Subtitle or video-subtitle output |
| Local sandbox | Clean workspace / create a small tool / batch process files | Local agent result |
| Knowledge summarization | Summarize these files and list key points | Structured summary |

### Releases

This repository does not host the full source code. Installers, portable packages, and release notes will be published through [GitHub Releases](https://github.com/70451136/LinkGo/releases).

### Feedback

If you encounter issues with file formats, translation quality, model configuration, LinkClaw local sandbox, or release packages, please open an Issue with your operating system, file type, task goal, expected result, and actual result.

# 隐私与本机使用边界 / Privacy and Local-First Boundaries

## 中文

LinkGo 的设计倾向是本机优先，但实际隐私边界取决于你的部署方式、模型选择和功能开关。

### 默认应保留在本机的内容

- 本机沙箱目录。
- 用户上传文件和生成结果。
- 本地模型运行时。
- 本机运行日志。
- 术语库、翻译记忆和长期记忆资产。

### 可能触发联网的情况

- 使用在线大模型。
- 开启联网搜索。
- 下载模型、运行时或依赖。
- 使用外部 OCR、语音识别、图片生成等服务。
- 调用第三方代理或 API。

### 安全建议

- 处理敏感文件时优先使用本地模型。
- 关闭不需要的联网搜索。
- 不要公开分享包含客户内容、API Key、Token、Cookie、数据库或本机路径的日志。
- 局域网或公网部署时，不要开放本机沙箱和系统控制能力。
- 发布 Issue 前请删除敏感片段。

## English

LinkGo is designed with a local-first preference, but the actual privacy boundary depends on deployment, model selection, and enabled features.

### Content That Should Stay Local by Default

- Local sandbox directories.
- Uploaded files and generated outputs.
- Local model runtimes.
- Local execution logs.
- Glossaries, translation memories, and long-term memory assets.

### When Network Access May Happen

- Using online LLM providers.
- Enabling web search.
- Downloading models, runtimes, or dependencies.
- Using external OCR, speech recognition, image generation, or third-party APIs.
- Using proxy services.

### Recommendations

- Use local models for sensitive files.
- Disable web search when not needed.
- Do not publicly share logs containing customer content, API keys, tokens, cookies, databases, or local paths.
- Do not expose local sandbox or system-control features to LAN or public visitors.
- Remove sensitive excerpts before opening Issues.

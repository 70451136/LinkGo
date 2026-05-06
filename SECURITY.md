# 安全说明 / Security

## 中文

LinkGo 涉及文件处理、本机沙箱、模型配置和外部服务连接。公开反馈问题时，请注意：

- 不要上传真实客户文件。
- 不要上传 API Key、Token、Cookie、数据库文件或本机配置。
- 本机沙箱和 LinkClaw 控制能力只应在本机使用。
- 局域网或公网访问时，不应开放本机系统控制能力。
- 处理敏感文件时，建议使用本地模型并关闭联网搜索。

如果你发现可能导致越权访问、任意文件读写、密钥泄露或沙箱逃逸的问题，请先通过私有渠道联系维护者，不要公开可直接利用的细节。

## English

LinkGo involves file processing, local sandboxing, model configuration, and external service connections. When reporting issues publicly, please note:

- Do not upload real customer files.
- Do not upload API keys, tokens, cookies, database files, or local configuration.
- Local sandbox and LinkClaw control capabilities should only be used locally.
- Local system-control features should not be exposed to LAN or public visitors.
- For sensitive files, prefer local models and disable web search.

If you discover a vulnerability that may cause unauthorized access, arbitrary file read/write, secret leakage, or sandbox escape, please contact the maintainer privately first and avoid posting directly exploitable details publicly.

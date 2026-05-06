# 发布包说明

本仓库后续会通过 GitHub Releases 发布 LinkGo 安装包或压缩包。

## 推荐发布内容

每个 Release 建议包含：

- Windows 桌面运行包。
- Linux / Ubuntu 部署包。
- 更新说明。
- 已知问题。
- 校验信息。

## 安装前准备

不同版本可能会自动部署或检测：

- Python 运行时。
- Node.js。
- Git Bash。
- WSL / Linux 兼容环境。
- Redis、MySQL、Qdrant 等本地服务。
- Ollama / vLLM 等本地模型运行时。

具体以 Release 页面说明为准。

## 升级建议

升级前建议备份：

- 用户数据库。
- 术语库和翻译记忆。
- 模型配置。
- 本机沙箱输出目录。

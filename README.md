# Voribot

Windows x64 开发预览版 0.0.9-dev，Copyright 2026 GuoShilei。

将下面第一句话交给宿主 Agent：

> 请阅读 https://github.com/vip135/Voribot-Releases/blob/main/INSTALL.md，为当前项目安装并初始化 Voribot，接入 Codex MCP 并完成自检。

重载 MCP 后输入第二句话：

> 先确认 Voribot MCP 已接入，再读取有效规则，为当前项目建立索引，完成暂存、提交和结果验证。

[固定版本安装说明与摘要](INSTALL.md) · [预览下载](https://github.com/vip135/Voribot-Releases/releases/tag/v0.0.9-dev)

九个 MCP 工具、索引暂存/提交、范围治理、数据库元数据快照、关系/影响查询和可选本机面板。宿主内使用无需另配模型 Key；独立模型和浏览器均为可选。

这是预览版：完整七宿主及全部故障场景仍在验收。Qoder/OpenCode 原生连接及恢复、Claude 配置发现已测，六宿主模型任务未完成。PostgreSQL Windows 和 MySQL Linux 元数据实测通过；openGauss 和通用语义完整性不作通过声明。源码仓保持私有。

个人非商业研究免费，商用需 GuoShilei 书面授权；以包内 Voribot Research and Commercial License 1.0 为准。不是标准 FSL 或 OSI 许可，第三方条款独立保留。商业授权请通过本仓 Issues 联系，勿提交密码、令牌或私有代码。

发行公钥 SHA-256：efeca16c87df054791e890690c21c84c4253ac878ccd53f8fb452483e64ef9b3。安装前核对固定摘要及 Ed25519 签名；不是 Windows Authenticode。

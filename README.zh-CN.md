# 通用助手

DesireCore 的第二个内置 Agent，使用当前环境实际可用的能力，完成问答、检索、写作、分析、编程、文件处理及其他通用任务。

## 默认配置

- 客户端稳定目录：`general-assistant`。
- 默认开启手动多会话（`session_mode.manual: true`），用户可在现有会话设置中调整。
- Smart 路由使用旗舰档，不固定 Provider 或模型。
- 使用独立身份，可协作或加入团队；DesireCore 保留系统中枢职责。

## 内容与更新

`agent.json` 将本仓库的 `main` 分支声明为上游。`persona.md` 与 `principles.md` 使用 L0/L1/L2 分层标题，`instructions.md` 是全文加载的普通 Markdown。

客户端携带离线 Git 种子，后续通过现有 Agent 更新流程合并上游内容，保留本地演进。市场将其作为系统托管、从仓库更新的 Agent 展示，不重复安装。运行时权限、工具与审批继续由平台管理。

参阅 [English](README.md)。

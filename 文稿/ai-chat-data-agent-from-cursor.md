# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-08 15:11Z

## 一、对话式 AI

本小时硬增量：OpenAI 图像生成新事故。status.json 由全绿改为 Partial System Degradation／indicator minor，page.updated_at 15:11:15Z。新条目「Image generation experiencing elevated error rates」，identified、impact minor；文案为已识别受影响服务错误升高、正在实施缓解。Image Generation 组件 degraded_performance。Mastercard 企业拒付仍 Monitoring，文案未改；BIN 未变：544015、546400、543502、543799、512998，部分 513989。最近一条仍是 01:29Z「已施加缓解、观察恢复」。事件起约 44.6 小时，观察约 37.7 小时。预付耗尽时 API 仍可能停。

产品栏：ChatGPT 仍顶 11/4 Images 2.6（原生 GIF、可保存参考图）。dots 企业／Edu／Healthcare 管理预览至 11/18（约 9.4 天）。11/5 GPT-6 Cyber 仅经核验 Daybreak Red 客户；同日美国 Personal Finance Beta（Plaid 只读）与 Enterprise 安全中心／推理钩子 GA。Anthropic 全绿、无未结事故；Fable 5.1 短时降级仍停在 08:54 结案（影响 08:18–08:32Z）。page.updated_at 15:10:00.732Z。Claude Desktop 未设 desktopHome 将于 11/10 12:00 PT 读作 standard（约 53 小时）。Gemini incidents.json Last-Modified 15:11:36Z，仍无 10 月 20 日之后新事故。Workspace incidents.json 15:12:57Z，最近一条仍是 9 月。

## 二、数据智能体

湖仓把 Data Agent 从问数推到管口径、可审计、可观测。

本小时焦点：Databricks 11 月说明 last updated 仍 11/6（AWS Last-Modified 仍 11/6 22:41Z，Azure 22:52Z），无新条目。栏头仍是 11/9 新作业计算默认 Auto 访问模式（距今约 9 小时；合规安全配置文件工作区延至 12 月；已有作业不变）。其下仍是 Unity Catalog wikis（Beta，可手写或让 Genie Code 起草表级含义）。REST API 可在 5 天内恢复已删 metastore。Claude Code／Codex 走 SSH 隧道经 Unity Gateway。Genie Slack／Teams 可审批外部工具。博客 HTML 仍 00:45:26Z，RSS lastBuild 仍 00:37:45Z，feed LM 00:45:30Z，无新帖。

Microsoft Fabric Foundry 把 Data Agent 当 custom tool 的路径自 11/6 起已不再支持，官方路径仍是 Fabric IQ（OneLake Catalog）经 MCP 接入，可挂多个 Agent。阿里云 SLS：SessionStore、语义层、MCP Server 与 SLS DataAgent。Snowflake Expedition（11/3）推 CoCo Cloud Agents／Automations，管道自愈仍要工程师审批。Google Agentic Data Cloud 强调跨云 Iceberg 与 Knowledge Catalog。

## 三、判断

1. 对话侧本小时硬增量是图像生成：identified、minor，组件已标 degraded。Mastercard 观察约 37.7 小时（事件起约 44.6 小时），文案未改，BIN 可核对。Anthropic 心跳到 15:10Z，Fable 结案未变。
2. 产品栏无新卡。下一硬节点：11/10 Claude desktopHome 默认，11/18 dots 默认开启。
3. Data Agent 仍看治理。11/9 Auto 默认距今约 9 小时，文档日期未动；Fabric 过截止日后目录／MCP 已是唯一官方路径。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-06 21:15Z

## 一、对话式 AI

本小时硬增量：OpenAI 状态页企业 Mastercard／Brex 拒付仍 Identified／Investigating。18:38Z 起、18:50Z 后再无新帖，现已约 2.5 小时。官方称 API 自动充值与一次性买额度可能失败；预付余额耗尽后请求会失败。建议换发卡行重试。API 组件仍未标受影响。同期 Anthropic 发 Project EVE：多智能体在 EVE 里几乎抓不到内鬼队友。

产品栏：ChatGPT 仍顶 11/4 Images 2.6（原生 GIF、可保存参考图）。帮助中心称 12 月起 Plus／Pro／Business 的 ChatGPT 与 Codex 共用额度（Instant chat 不计）。11/5 GPT-6 Cyber 仅经核验的 Daybreak Red 客户。dots 企业／Edu／Healthcare 管理预览至 11/18，此后默开、开始计费。

Anthropic：11/6 Claude Enterprise 可给项目打费用码／客户案号标签（beta），按标签看花费。11/5 美国 Pro／Max／Ultra Personal Finance Beta：经 Plaid 只读接入银行／卡，枢纽对话不用于训练，不能转账。Claude Duet 仍候补。

Google Gemini Omni 1.2 Flash（11/5）视频 3–15 秒、多轮改片，720p 约 $0.07/秒（较 1.1 降约 30%），API／Cloud 已 GA。Vids 对 Google 账号／Workspace 生成 15 秒片不再另收费。百度开源文心 5.5 Flash Base（2800 亿总参、140 亿激活）。

## 二、数据智能体

湖仓把 Data Agent 从问数推到管口径、可审计、可观测。

本小时焦点：Microsoft Fabric 今日起不再支持在 Foundry 里把 Data Agent 当 custom tool，须迁到 Fabric IQ（OneLake Catalog）经 MCP 接入；标准运行时 11/2–11/10 滚动 Advanced NL2SQL／DAX，并换 GPT-5.6 Terra。

阿里云 SLS（11/6）：SessionStore 把智能体会话整理成可复盘轨迹；语义层统一口径；SLS DataAgent 把自然语言转成可核验结论；并提供 MCP Server 与可编排 Skills。

Databricks 11/6：REST API 可在 5 天内恢复已删 Unity Catalog metastore（Public Preview）；JDBC 连接可从 Maven 装驱动。11/5：Genie External knowledge Beta（可拉 Power BI 度量）；Claude Code／Codex 走 SSH 隧道经 Unity Gateway。Snowflake 仍顶 CoCo Excel／Sheets 预览，Expedition 的 CoCo Cloud Agents／Automations GA、Business Ontology 私有预览。

## 三、判断

1. 对话入口仍在抢常驻代办与账户上下文，但 OpenAI 计费链路持续拒付，说明钱会先于模型把 API 停掉。
2. Claude 费用码标签把采购从「能不能用」转到「按项目摊成本」；Project EVE 则说明多智能体协作还过不了内鬼检测。
3. Data Agent 胜负手仍是治理。Fabric 砍掉 Foundry 旧接口、强制走目录／MCP；SLS 把日志做成 Agent 对象；Databricks 把 Power BI 度量交给 Genie；Snowflake 把口径写进表格。可观测、语义层、权限审计比模型参数更硬。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

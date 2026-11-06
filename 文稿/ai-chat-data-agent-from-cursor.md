# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-06 20:15Z

## 一、对话式 AI

本小时硬增量：OpenAI 状态页 18:38Z 起 Identified「部分美国企业 Mastercard／Brex 拒付」，18:50Z 仍 Investigating。官方称 API 自动充值与一次性买额度可能失败；预付余额耗尽后请求会失败。建议换发卡行重试。API 本身未标受影响组件。

产品栏：ChatGPT 仍顶 11/4 Images 2.6（原生 GIF、可保存参考图）。11/5 GPT-6 Cyber 仅经核验的 Daybreak Red 客户；系统卡为网络安全 Critical。dots 企业／Edu／Healthcare 管理预览至 11/18，此后默开、开始计费（管理员可退出）。此前称 ChatGPT 触发的网页搜索量约等于 Google 的 20%（口径自定）。

Anthropic：11/6 Claude Enterprise 可给项目打费用码／客户案号标签（beta），按标签看花费。11/5 美国 Pro／Max／Ultra Personal Finance Beta：经 Plaid 只读接入银行／卡，枢纽对话不用于训练，不能转账。同日企业安全中心（beta）对照推荐配置，推理钩子已 GA。Claude Duet 仍候补。

Google Gemini Omni 1.2 Flash（11/5）视频 3–15 秒、多轮改片，720p 约 $0.07/秒（较 1.1 降约 30%），API／Cloud 已 GA。Vids 每月最多 3 条 15 秒免费。百度开源文心 5.5 Flash Base（2800 亿总参、140 亿激活）。

## 二、数据智能体

湖仓把 Data Agent 从问数推到管口径、可审计、可观测。

今日焦点仍是阿里云 SLS（11/6）：SessionStore 把智能体会话整理成可复盘轨迹；语义层统一口径；SLS DataAgent 把自然语言转成可核验结论；并提供 MCP Server 与可编排 Skills。

Databricks 11 月栏 11/6 新增：REST API 可在 5 天内恢复已删 Unity Catalog metastore（Public Preview）；JDBC 连接可从 Maven 装驱动。11/5：Genie External knowledge Beta（可拉 Power BI 语义模型度量）；Claude Code／Codex 走 SSH 隧道经 Unity Gateway；AI Functions SQL 自 2027/1 起需 DBR 17.3 LTS+。11/4 AI Function 任务 Beta。Snowflake 仍顶 11/5 CoCo Excel／Sheets 预览，11/3 Expedition 的 CoCo Cloud Agents／Automations GA、Business Ontology 私有预览。

## 三、判断

1. 对话侧本小时无新产品档，硬增量是 OpenAI 企业卡拒付：对话入口仍在抢搜索、常驻代办与账户上下文，但计费链路会先于模型把 API 停掉。
2. Claude 费用码标签说明企业采购已从「能不能用」转到「按项目摊成本」。银行只读已开，屏幕代操仍受阻。
3. Data Agent 胜负手仍是治理。SLS 把日志做成 Agent 数据对象；Databricks 把 Power BI 度量交给 Genie；Snowflake 把口径写进 Ontology／表格。可观测、语义层、权限审计比模型参数更硬。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

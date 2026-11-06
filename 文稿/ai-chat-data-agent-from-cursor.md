# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-06 23:15Z

## 一、对话式 AI

本小时硬增量：OpenAI 状态页企业 Mastercard／Brex 拒付仍 Identified／Investigating，已约 4.5 小时。时间戳仍停在 18:38Z／18:50Z，但正文现已点名受影响卡号前缀：544015、546400、543502、543799、512998，部分 513989。官方称 API 自动充值与一次性买额度可能失败；预付余额耗尽后请求会失败。建议换发卡行重试。API 组件仍未标受影响。次增量：METR 11/5 称 Anthropic 明确任务能力约 2 倍于 2024.3–2025.10 节奏（AECI 约 1.9×），大量证据被涂黑。Project EVE：四智能体几乎抓不到内鬼；有限监控抓到 20–40%。

产品栏：ChatGPT 仍顶 11/4 Images 2.6（原生 GIF、可保存参考图）。12 月起 Plus／Pro／Business 的 ChatGPT 与 Codex 共用额度（Instant chat 不计）。11/5 GPT-6 Cyber 仅经核验的 Daybreak Red 客户。dots 企业／Edu／Healthcare 管理预览至 11/18，此后默开、开始计费。

Anthropic：11/6 Claude Enterprise 可给项目打费用码／客户案号标签（beta）。11/5 美国 Pro／Max／Ultra Personal Finance Beta：经 Plaid 只读接入银行／卡，枢纽对话不用于训练，不能转账。

Google Gemini Omni 1.2 Flash（11/5）视频 3–15 秒、多轮改片，720p 约 $0.07/秒（较 1.1 降约 30%）。百度开源文心 5.5 Flash Base（2800 亿总参、140 亿激活）。

## 二、数据智能体

湖仓把 Data Agent 从问数推到管口径、可审计、可观测。

本小时焦点：Databricks 11/6 文档新顶 Unity Catalog wikis（Beta）：表级含义、用途、来源可由数据负责人手写或让 Genie Code 起草。同日 Pages 文档更新：概念级权威定义纳入 Genie Ontology，Genie One 答问优先引用已发布 Page 并给出处。仍顶 REST API 可在 5 天内恢复已删 metastore（Public Preview）；JDBC 可从 Maven 装驱动。

Microsoft Fabric 今日起不再支持在 Foundry 里把 Data Agent 当 custom tool，须迁到 Fabric IQ（OneLake Catalog）经 MCP 接入，且可挂多个 Agent。标准运行时 11/2–11/10 滚动 Advanced NL2SQL／DAX，并换 GPT-5.6 Terra；已发布 Agent 须重新发布才跟上。内部称 Advanced DAX 智能答案准确率 89.15%→91.86%，P50 时延约降一半。

阿里云 SLS（11/6）：SessionStore 把智能体会话整理成可复盘轨迹；语义层统一口径；SLS DataAgent 把自然语言转成可核验结论，并提供 MCP Server。11/5：Genie External knowledge Beta（可拉 Power BI 度量）；Claude Code／Codex 走 SSH 隧道经 Unity Gateway。Snowflake 仍顶 CoCo Excel／Sheets 预览，Cloud Agents／Automations GA、Business Ontology 即将公测。

## 三、判断

1. 对话入口仍在抢常驻代办与账户上下文，但 OpenAI 计费链路已静默约 4.5 小时；现已点名 BIN，拒付范围可核对，钱仍会先于模型把 API 停掉。
2. Claude 费用码标签把采购转到「按项目摊成本」；METR 说研发在加速，Project EVE 则说明多智能体还过不了内鬼检测。
3. Data Agent 胜负手仍是治理。Databricks 把表级 wiki 与概念级 Page 写进目录，Genie 先引用人定口径；Fabric 砍掉 Foundry 旧接口、强制走目录／MCP；SLS 把日志做成 Agent 对象。可观测、语义层、权限审计比模型参数更硬。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

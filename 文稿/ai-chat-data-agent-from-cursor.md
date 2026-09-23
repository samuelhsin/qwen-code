# AI Chat 与大数据 Data Agent 产业简报

更新：2026-09-23 10:09 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

本小时最大变动：Anthropic 与 OpenAI 于 9 月 22 日几乎同时上新，竞争从旗舰跑分转向单位任务成本。Claude Opus 5.5 称多数工作达到 Fable 5.1 水平，较 Opus 5 典型负载成本约降 40%、输出快 30% 以上；API 为每百万输入/输出 Token 4/20 美元，缓存读取 0.20 美元。Artificial Analysis 将其 Intelligence Index 排到 58，与 GPT-6 Astra 的 Agent 能力接近。发布前接受 Frontier Design、METR 等外部安全测试，并预告数周内推出 Sonnet 5.5 与 Haiku 5.5。OpenAI 同日推出 GPT-6 Sol 与 Luna，API 价较 GPT-5.6 促销价下调 50% 且为长期价：Sol 为 2/10 美元，Luna 为 0.10/0.50 美元，上线 ChatGPT Work、Codex 与 API；9 月 3 日的 Astra 继续承接最难任务。距 Astra 仅 19 天、距 Fable 5.1 仅 21 天，发布节奏仍密。

市场在碎片化。Comscore Q2 报告（9 月 22 日）显示，2026 年 1–6 月 ChatGPT 提示量份额从 70% 降至 50%，Gemini 从 17% 升至 30%，Claude 从 2% 升至 11%。ChatGPT 仍居首位，但 Gemini 借搜索、Android、Workspace 拿主流用户，Claude 吃知识工作与编码。6 月桌面/移动访问 AI 助手比例约 35%/29%，移动增速已超过桌面。Google 桌面搜索带 AI 概览的占比从 2025 年 7 月 25.8% 升至 2026 年 6 月 39.4%。OpenAI 9 月 10 日把 Agents API 放进公开测试，把长时程 Agent 的调度、沙箱与子代理做成托管接口；ChatGPT 则把 Chat、Work、Codex 拆成对话、长任务与编码三条入口。国内 C 端分层未破：豆包吃日常与流量入口，DeepSeek 主打推理与低价 API，千问吃办公与超长文档，Kimi 做长上下文与 Agent。独立 App 已定层，微信与支付宝超级入口仍是分流变量。

## 二、数据智能体

Data Agent 从“会问数”转向“受治理地连仓、出看板、可执行”。OpenAI 9 月 10 日在 ChatGPT Work 上线 Data agent，对接 Redshift、BigQuery、Databricks、Snowflake、MongoDB 等，并写入 dbt、Genie Ontology、Horizon 等语义层，可在 Tableau、Power BI 等生成看板。Google Cloud 9 月 9 日预览 Data Agent Kit，以 MCP + Skill 把问数放进 Cursor、Claude Code、Codex。Databricks Genie One MCP 已 GA，让外部智能体按统一业务本体取数。Teradata 9 月 22 日把 Tera 升级为受治理的数据同事，并嵌入 WisdomAI 主动分析；Proofpoint 同日把数据权限与 Agent 行为绑成一套安全系统。

国内方面，IDC《中国 Data Agent 2026 厂商评估》18 家入围、仅 4 家进领导者，阿里云居首。9 月 22 日云栖会上，阿里云把 OpenLake 推向 Agentic Lake；DataWorks 发布 Context Graph，称业务问答准确率 93.24%、SQL 一致性 99%；ADA 做跨引擎多智能体编排。菜鸟 SuperETL 称研发效率提升 2–3 倍，部分场景自动完成率超 80%。语义层、权限与可审计，比单点 Text-to-SQL 更决定成交。

## 三、判断

1. 对话模型进入价效比阶段：谁能把旗舰能力下沉到可规模化的任务单价，谁就能锁住 Agent 工作负载。
2. Chat 正在变成工作入口；谁占界面，谁绑定数据连接、语义层和权限。
3. Data Agent 的胜负手是治理过的上下文加 MCP 分发，不是再做一个聊天框。
4. 国内机会仍在企业数据闭环与云厂商全栈，不在再做一个通用聊天机器人。

依据公开报道整理，不构成投资建议。

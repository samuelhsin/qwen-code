# AI Chat 与大数据 Data Agent 产业简报

更新：2026-09-23 13:12 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

本小时增量：旗舰价效比窗口继续拉开。Anthropic 与 OpenAI 于 9 月 22 日几乎同时上新。Claude Opus 5.5 称多数工作达到 Fable 5.1 水平，较 Opus 5 典型负载成本约降 40%、输出快 30% 以上；API 为每百万输入/输出 Token 4/20 美元，缓存读取 0.20 美元。OpenAI 同日推出 GPT-6 Sol 与 Luna，API 价较 GPT-5.6 促销价下调 50% 且为长期价：Sol 为 2/10 美元，Luna 为 0.10/0.50 美元；上线 ChatGPT Work、Codex 与 API，Luna 还进入 Free/Go 桌面端。9 月 3 日的 Astra 继续承接最难任务。SpaceXAI 9 月 21 日发布 Grok 4.7，主打编码与知识工作，定价 2/6 美元，已进 Cursor、Grok Build 与 API。距 Astra 仅 20 天、距 Fable 5.1 仅 22 天，发布节奏仍密。

市场在碎片化。Comscore 9 月 22 日 Q2 报告显示，2026 年 1–6 月 ChatGPT 提示量份额从 70% 降至 50%，Gemini 从 17% 升至 30%，Claude 从 2% 升至 11%。ChatGPT 6 月桌面对话仍达 1.68 亿。6 月桌面/移动访问 AI 助手比例约 35%/29%，移动增速已超过桌面。Google 桌面搜索带 AI 概览的占比从 2025 年 7 月 25.8% 升至 2026 年 6 月 39.4%。Gemini 9 月 10 日上线 Windows 原生应用（Alt+Space），并称月活过 10 亿。OpenAI 9 月 10 日把 Agents API 放进公开测试；ChatGPT 把 Chat、Work、Codex 拆成对话、长任务与编码三条入口。国内 C 端分层未破：豆包吃日常，DeepSeek 主打推理与低价 API，千问吃办公与超长文档，Kimi 做长上下文与 Agent。

## 二、数据智能体

本小时看点是“模型进仓 + MCP 出仓 + 可观测”。Snowflake 9 月 22 日把 Opus 5.5 放进 Cortex 公测，覆盖 CoCo、CoWork、Cortex Agents、AI Functions 与 Inference，调用不出安全边界；并预告 Observe 上的 Agent Observability（即将私测），以及 Cortex Agents 接入 Teams 与 Microsoft 365 Copilot；Fabric data agent 也可发到 Copilot Agent Store。Databricks 同日宣布 Genie One MCP 正式 GA，作为 Unity Gateway 托管服务，让 ChatGPT、Claude、Cursor 等按同一 Genie Ontology 取数、出图并留下审计。OpenAI 9 月 10 日在 ChatGPT Work 上线 Data agent，对接 Snowflake、BigQuery、Databricks 等，可在 Tableau、Power BI 等生成看板。Google Cloud 9 月 9 日预览 Data Agent Kit，以 MCP + Skill 把问数和管线编写放进 IDE。

国内方面，IDC《中国 Data Agent 2026 厂商评估》18 家入围、仅 4 家进领导者，阿里云居首。云栖会上 DataWorks 发布 Context Graph，称业务问答准确率 93.24%、SQL 一致性 99%；ADA 做跨引擎多智能体编排；ODPS 按 Agent 原生与全模态重构；数据库侧推出 Agent Context 与 ApsaraLakebase。快手 Data Agent 周活破万，竞赛进入规模化兑现期。语义层、权限与可审计，比单点 Text-to-SQL 更决定成交。

## 三、判断

1. 对话模型进入价效比阶段：谁能把旗舰能力下沉到可规模化的任务单价，谁就能锁住 Agent 工作负载。
2. Chat 正在变成工作入口；谁占界面，谁绑定数据连接、语义层和权限。
3. Data Agent 的胜负手是治理过的上下文加 MCP 分发与可观测，不是再做一个聊天框。
4. 国内机会仍在企业数据闭环与云厂商全栈，不在再做一个通用聊天机器人。

依据公开报道整理，不构成投资建议。

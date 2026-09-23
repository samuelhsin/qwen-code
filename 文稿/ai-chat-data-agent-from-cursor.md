# AI Chat 与大数据 Data Agent 产业简报

更新：2026-09-23 12:08 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

本小时增量：Snowflake 把 9 月 22 日刚发布的 Claude Opus 5.5 同日放进 Cortex 公测，覆盖 CoCo、CoWork、Cortex Agents 与 SQL 内 AI Functions，调用不出治理边界。旗舰竞争本身仍停在价效比：Opus 5.5 称多数工作达到 Fable 5.1 水平，较 Opus 5 典型负载成本约降 40%、输出快 30% 以上；API 每百万输入/输出 Token 4/20 美元，缓存读取 0.20 美元，Artificial Analysis Intelligence Index 58。接入时思考默认不可关、强制选工具会报错。OpenAI 约 90 分钟后把 GPT-6 Sol、Luna 铺进 ChatGPT Work、Codex 与 API，价较 GPT-5.6 促销价下调 50% 且为长期价：Sol 2/10 美元，Luna 0.10/0.50 美元；Free/Go 可在桌面试用 Luna。Astra 仍接最难任务。ChatGPT 已把 Chat、Work、Codex 拆成对话、长任务与编码三条入口。

市场份额按口径分裂。Comscore Q2 显示 2026 年 1–6 月提示量份额：ChatGPT 从 70% 降至 50%，Gemini 从 17% 升至 30%，Claude 从 2% 升至 11%。Similarweb 网站流量则把 ChatGPT 回升到约 55.5%、Gemini 约 25.6%、Claude 约 9.3%。6 月桌面/移动访问 AI 助手约 35%/29%，移动增速已超桌面。Google 桌面搜索带 AI 概览的占比从 2025 年 7 月 25.8% 升至 2026 年 6 月 39.4%。OpenAI 9 月 10 日把 Agents API 放进公开测试，托管调度、沙箱与子代理。国内 C 端分层未破：豆包吃日常入口，DeepSeek 主打推理与低价 API，千问吃办公与超长文档，Kimi 做长上下文与 Agent。

## 二、数据智能体

Data Agent 从“会问数”转向“受治理地连仓、出看板、可执行”。OpenAI 在 ChatGPT Work 上线 Data agent，对接 Redshift、BigQuery、Databricks、Snowflake 等，并写入 dbt、Genie Ontology 等语义层，可在 Tableau、Power BI 生成看板。Google Cloud 预览 Data Agent Kit，以 MCP + Skill 把问数放进 Cursor、Claude Code、Codex。Databricks 宣布 Genie One MCP 全面可用并挂进 Unity Gateway。Teradata 把 Tera 升级为受治理的数据同事，嵌入 WisdomAI，计划四季度 GA。Proofpoint 把数据权限与 Agent 意图绑成一套安全系统。Snowflake 还预告 Observe 上的 Agent 可观测，并把 Cortex Agents 嵌进 Teams 与 Copilot。

国内方面，IDC《中国 Data Agent 2026 厂商评估》18 家入围、仅 4 家进领导者，阿里云居首；并预测 2028 年六成中国 500 强将部署企业级 Data Agent。云栖会上，阿里云把 OpenLake 推向 Agentic Lake；DataWorks Context Graph 称业务问答准确率 93.24%、SQL 一致性 99%；ADA 做跨引擎多智能体编排。菜鸟 SuperETL 称研发效率提升数倍。语义层、权限与可审计，比单点 Text-to-SQL 更决定成交。

## 三、判断

1. 对话模型进入价效比阶段：谁能把旗舰能力下沉到可规模化的任务单价，谁就能锁住 Agent 工作负载。
2. Chat 正在变成工作入口；谁占界面，谁绑定数据连接、语义层和权限。
3. Data Agent 的胜负手是治理过的上下文加 MCP 分发，不是再做一个聊天框。
4. 国内机会仍在企业数据闭环与云厂商全栈，不在再做一个通用聊天机器人。

依据公开报道整理，不构成投资建议。

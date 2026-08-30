# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-30 07:09 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

今日官方 DALL·E GPT 从 ChatGPT 下架：生图改走全档位 ChatGPT Images，自定义 GPT 不受影响；旧 GPT 内图片建议先下载。8 月 26 日 Assistants API 已日落，平台迁到 Responses + Conversations。Codex 负责人刚向 Codex 与 ChatGPT Work 付费用户集体重置额度：已修无效压缩、完成后仍重试、记忆循环、子智能体擅升档等计费与循环 bug，同额度预计可多用约 10%–50%；团队将补额度去向展示。

8 月 31 日仍是硬窗口：GPT-5.4 / 5.4 mini 退出 Codex 的 ChatGPT 登录通道（API 仍可用）；Kimi k2.5 与 moonshot-v1 日落，迁到 K3；Claude Code 自 5 月起上浮 50% 的周限额窗口到期，周容量约回落到现用的三分之二。Sonnet 5 价表以官方为准：8 月 10 日已宣布 2/10 美元每百万 token 永久锁定，原定 9 月 1 日调到 3/15 已取消，但分词器仍可能让代码多计 10%–35% token。GPT-5.6 Sol 8 月 21 日导入价从 5/20 降到 4/20 美元，属三个月促销。

8 月 29 日 Anthropic 撤掉 Slack 智能体的二元分类器：Claude 会读整段会话、记忆与常驻指令，再决定回复、开线程、转工单或沉默，官方称“该不该插话”约提升 30%，并把它标成多人协作智能体。8 月 26 日 Salesforce 与 Anthropic 宣布 Claudeforce：Claude 成为 Agentforce Atlas 默认推理引擎，覆盖 Slack AI；首发 Salesforce in Claude 插件内置 37 项销售技能，写回仍走原权限，9 月公测。

聊天入口仍高度集中但领先幅度收窄。Similarweb 5–6 月口径下 ChatGPT 约占全球聊天机器人网页流量一半；Statcounter 4 月录得 76.85%。OpenAI 称月活已过 10 亿；Gemini 近五倍增长并逼近 9.5 亿月活。Ramp 7 月样本里 Anthropic 约占企业 44%、OpenAI 约 40%，三季度随新模型来回切换。采购切断未消：OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供；Cursor 称约占约 5% 流量并仍在协商。Visa 等推代理支付，NIST 做身份授权，美参议院 S.5051 在审。联邦法院已裁定五角大楼将 Anthropic 列入供应链风险属违法报复。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake 8 月 26 日让 Cortex Agents Coding Agent 正式商用：托管沙箱可跑 bash、读写、检索、SQL 与 Skills。Databricks 把 Genie Spaces 收成 Genie Agents，Agent 模式可多步假设检验；同期用 LTAP + Lakebase 解决高并发写回，8 月 21 日 Unity Catalog 上线面向智能体的上下文 ABAC（个人令牌与内置 Genie 仍不覆盖）。Microsoft Fabric Data Agent 编排升到 GPT-5.1，并从 Assistants API 迁到 Responses / MCP。Salesforce 扩大与 Databricks / Google / Snowflake 的零拷贝连接。Teradata Data Analyst Agent 上架 AWS Marketplace。

国内窗口在办公入口、语义层与数博会。8 月 25 日字节发布「豆包工作」，继承飞书权限；腾讯 WorkBuddy 已有百万级日活；阿里千问办公 8 月 3 日公测并整合 QoderWork / 悟空 / MuleRun；百度把 GenFlow 定名「库库AI」。帆软 FineBI NEXT、Aloudata、腾讯云 TCDataAgent 都把语义层写成 NL2MQL2SQL。8 月 27–28 日贵阳数博会，华为云称 IT 正转向“以 Agent 为中心”；海光首发 Agent to Token 开放计算架构；科杰首发 Keen Agentic OS。7 月底团体标准《数据编织智能体技术规范》已实施。IDC 预期 2026 年半数中国 500 强部署分析类 Agent，近四成卡在治理与口径。

## 三、判断

1. 未来 24 小时看 8 月 31 日 Codex 通道、Kimi 日落与 Claude Code 限额回落。
2. Slack 多人上下文 + Claudeforce 说明对话入口开始吃协同写回。
3. 模型供给切断已是采购条款：须写多模型隔离与熔断。
4. Data Agent 胜负手是写回路径、语义层、权限与可核验交付。

依据公开报道整理，不构成投资建议。

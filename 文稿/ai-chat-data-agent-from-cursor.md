# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-30 05:11 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

今日硬节点是官方 DALL·E GPT 从 ChatGPT 下架：生图改走全档位 ChatGPT Images，自定义 GPT 不受影响；OpenAI 建议先下载旧 GPT 里的图片，未说明下架后是否可再取。8 月 26 日 Assistants API 已日落，平台迁到 Responses + Conversations。本小时新增：Codex 负责人宣布向 Codex 与 ChatGPT Work 付费用户集体重置额度，称已修多项计费与循环 bug（无效上下文压缩、任务完成后仍重试、记忆循环、子智能体擅自升档等），同额度预计可多用约 10%–50%。

8 月 31 日三件事同日落地：多家日程仍写 Claude Sonnet 5 从 2/10 调到 3/15 美元每百万 token 并换分词器（代码约多 10%–35% token），亦有文档称 2/10 已永久锁定，以官方价表为准；GPT-5.4 / 5.4 mini 退出 Codex 的 ChatGPT 登录通道（API 仍可用）；Kimi k2.5 与 moonshot-v1 日落，迁移到 K3。同日 Claude Code 自 5 月起上浮 50% 的周限额窗口到期。

聊天入口仍高度集中但领先幅度收窄。Similarweb 5–6 月口径下 ChatGPT 约占全球聊天机器人网页流量一半，较一年前的 77%–87% 回落；Gemini 近五倍增长并逼近 9.5 亿月活。OpenAI 称 ChatGPT 月活已过 10 亿。免费与 Go 档默认 GPT-5.6 Luna，Plus/Pro 用 Sol。谷歌 8 月 13 日上线 Gemini 3.7 Flash（导入价 0.75/3.75 美元至年底，2027 年 1 月 1 日翻倍）。智谱 GLM-5.3 权重原定 8 月 28 日解禁，旗舰许可仍未写清。

采购切断未消：OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供模型；Cursor 方面称其约占约 5% 流量并仍在协商；Anthropic 称加码 Cursor 上的 Claude 算力。形态从“会聊”转向“代办+支付”：Visa 等推 Agentic Payments Alliance，Google 发代理支付协议，NIST 做身份授权概念工作，美参议院 S.5051 在审。美联邦法院已裁定五角大楼将 Anthropic 列入国家安全风险名单属违法报复，另案仍在审。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake 8 月 26 日让 Cortex Agents Coding Agent 正式商用：托管沙箱可跑 bash、读写、检索、SQL 与 Skills。Databricks 把 Genie Spaces 收成 Genie Agents，Agent 模式可多步假设检验并出带引用报告；同期用 LTAP + Lakebase 解决智能体高并发写回。Microsoft Fabric 8 月更新把 Data Agent 编排升到 GPT-5.1，并从 Assistants API 迁到 Responses API。Salesforce 扩大 Agentforce 与 Databricks / Google / Snowflake 的零拷贝连接，强调不搬数、沿用原权限。Teradata 把 Data Analyst Agent 上架 AWS Marketplace，在仓内做多步 SQL 与 Python。

国内窗口在办公入口与数据底座。8 月 25 日字节发布「豆包工作」，继承飞书权限与组织数据；腾讯 WorkBuddy 已有百万级日活；阿里千问办公 8 月 3 日公测并整合 QoderWork / 悟空 / MuleRun；百度 8 月 14 日把 GenFlow 办公端定名「库库AI」并推企业版。8 月 28 日贵阳数博会，华为云称 IT 正从“以人为中心”转向“以 Agent 为中心”。7 月底团体标准《数据编织智能体技术规范》已实施，覆盖架构、NLQ、并发与防注入。工程共识仍是 L2：NL2SQL + 语义层 + 人审。IDC 仍预期 2026 年半数中国 500 强部署分析类 Agent，近四成卡在治理与口径。

## 三、判断

1. 未来 24 小时看切价、Codex 通道与 Kimi 日落，并核对官方价表。
2. 额度重置说明计费与循环 bug 会直接吃掉智能体预算。
3. 模型供给切断已是采购条款：须写多模型隔离与熔断。
4. Data Agent 胜负手是写回路径、语义层与可核验交付。

依据公开报道整理，不构成投资建议。

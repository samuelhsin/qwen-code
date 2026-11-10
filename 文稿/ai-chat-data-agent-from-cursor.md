# AI Chat 与 Data Agent 产业动态

更新：2026-11-10 02:09 UTC（本文件每次覆盖写入）

## 市场
Graphite/Similarweb（11/9）：六大聊天机器人 9 月全球会话约 760 亿次（同比 +37%），ChatGPT 占 81.2%，自 6 月低点回升 0.8 个百分点，周活约两个月内从 10 亿升至 12 亿；Claude 会话约 54 亿已超过 Gemini 的 37 亿，但无一对手破 10%。口径分裂：StatCounter 10 月网页份额是 ChatGPT 51.58%、Gemini 28.86%、Perplexity 15.04%、Claude 仅 2.3%。国内履约入口：QuestMobile 9 月豆包月活 4.19 亿、千问 1.58 亿、DeepSeek 1.23 亿；办公 Agent 中 WorkBuddy 月活 3235.3 万（环比 +647%）居首，百度搭子 977 万（环比约 +1568%）居次，千问办公独立端约 790 万。SuperCLUE 10 月测评前四名分差仅 2.65——能力已拉不开，胜负看企微/钉钉/飞书存量。

## 产品
11 月 9 日交叉落地：阿里发布千问办公 2.0，定位 Team Agent（协作、人机共创、资料空间、自动任务、端云一体）；腾讯元器正式停服，存量智能体及公众号/微信客服入口失效，能力迁腾讯云 ADP，办公主入口只留 WorkBuddy。蚂蚁灵光 2.0 一周称管理超 116 万项事务、执行超 360 万次、接入 40 多项服务；荣耀联合中国移动推智能体网络并计划在 Magic9 试 AI Token 套餐。豆包手机助手屏幕代操作已遭 155 款 App 拒绝，跨端外挂与官方 API 闭环对撞。微软 Copilot 连接器写操作（增删改）在 Chat/Cowork 全面可用，默认需用户确认；无独立 Copilot 许可证的 M365 用户，超 2000 席位租户自 11 月 9 日起纳入未公开公平使用限额。OpenAI 将 ChatGPT Enterprise（Chat、Work、Codex、dots）上架 AWS Marketplace，并计划取消 Chat/Work 切换。dots 企业预览至 11 月 18 日，此后默认开启并计费，委派给 Work/Codex 的任务另计。Claude Mythos 5 / Opus 4.7 / Sonnet 4.6 文本隐形水印与文件 C2PA 在 Bedrock 侧于今日（11/10）完成。Google 将于 12 月 1 日把 Gemini API 的 2.5 Pro/Flash 自动切到 3.8 Flash / 3.5 Flash-Lite，函数调用可能不兼容。

## Data Agent
Snowflake Expedition（11/3）落到三件套：Business Ontology（预批准业务定义）、Cortex AI Gateway（推理/可观测/成本已 GA，MCP 工具仍预览）、CoCo/CoWork Bots（后台常驻、继承用户权限、需审批才落笔）；CoCo Cloud Agents、Automations 与 Cortex Agent SDK 已 GA。Google（11/4–6）把 Knowledge Catalog 语义模型 GA，可联邦 Looker/Databricks/Snowflake/dbt/SAP 而不搬数；Gemini Data Cloud 连接器仍为预览，按用户身份查数。Databricks Genie One MCP 已 GA，旧 Beta 端点 11 月 30 日停用（OAuth 范围改为 `ai-gateway`），Genie 用量免费至 2027-01-31。国内 IDC MarketScape 中国 Data Agent 2026 将阿里云置于领导者首位。竞争从“会问数”转向身份、语义层与动作治理。

## 治理
欧委会《人工智能法案》第 75c/75d 条执法程序实施条例征求意见已于布鲁塞尔时间 11 月 9 日 23:59 截止，拟对罚则设五年时效、调查步骤可中断时效（上限十年）。聊天机器人自 8 月起须披露“正在与 AI 对话”；既有生成式系统机器可读标记过渡期至 12 月 2 日。欧盟法院法务官 11 月 3 日就聊天机器人与新闻版权发表意见：风险在于绕过付费墙或替代原文。企业需在 11 月 18 日前决定是否允许 dots 默认开通，评估 Copilot 写操作与未公开限额，并在 11 月 30 日前完成 Genie MCP 迁移、12 月 1 日前完成 Gemini 2.5 接口测试。

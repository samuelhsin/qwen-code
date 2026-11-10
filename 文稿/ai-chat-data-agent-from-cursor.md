# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-10 12:12Z

## 一、对话式 AI

市场：Graphite（11/9，Similarweb 会话）称头部六家 9 月全球月会话约 760 亿、同比 +37%；ChatGPT 全球份额 81.2%，周活 12 亿。Claude 会话同比 +1901%，Gemini +182%。StatCounter 10 月页面浏览 ChatGPT 51.58%、Gemini 28.86%，美国近乎打平（37.10% vs 35.42%）。网站流量口径 Claude 已到 11.5%。国内 QuestMobile：9 月豆包月人均 72.0 次、DeepSeek 65.9 次。

产品与厂商：Anthropic 11/9 发 Claude Fable 5.2 / Mythos 5.2，输出最多约快 30%，API 每百万 tokens 输入 8 美元、输出 40 美元。Bedrock Global 较 5.1（10/50）便宜约 20%。Fable 已进 GitHub Copilot GA（企业策略默认关）、Bedrock（Covered Model，需 `aws_review`，默认最长约 30 天留存）、Foundry。留存供安全分类器、不用于训练。渠道不要混：Copilot 合格企业 ZDR 暂至年底后转 EFS；Bedrock 合格 EFS 客户 ZDR 可至 2027/6/30。OpenAI 11/9 把 ChatGPT Enterprise（Chat、Work、Codex、dots）上架 AWS Marketplace，dots 预览至 11/18。千问办公 2.0 推 Team Agent；腾讯元器 11/9 停服，导出至 2027/1/9。阿里云 Token Plan 个人版额度上调约七成。微软 Copilot 写操作已在 Chat/Cowork GA。本小时增量：微软宣布 Copilot 内 Claude 将于 2026 年底进入 EU Data Boundary（含 Cowork），EU/EFTA 默认关，已开启租户届时自动切区域处理。

## 二、数据智能体

湖仓争的是“业务上下文谁说了算”。Databricks 11/10 宣布三年向荷兰投逾 5 亿美元扩阿姆斯特丹研发枢纽（Lakebase/Genie/Unity Gateway）。11/9 已把 Genie Ontology、Genie Search、Genie Slack/Teams 标 GA；旧 Beta MCP 11/30 停用，须迁到 Unity Gateway 上的 `system.ai.genie_one_mcp`。管理员可用 MDM 经 Unity Gateway 给 Claude desktop 预置受管模型与 MCP。Snowflake 把 Business Ontology、Cortex AI Gateway、CoCo 绑在一起，CoCo Automations 可把巡检/报表写成定时任务。Google Knowledge Catalog 语义模型已 GA，BigQuery Graph 与跨云互联 GA；Knowledge Catalog 开始默认进 Gemini（预览）。Bedrock 知识库 11/9 加了单次检索与只返段落。没有语义层和权限继承的自然语言查仓不安全。

## 三、治理与判断

1. 旗舰模型用“覆盖模型 + 数据留存”换安全分类器；Marketplace/Bedrock/Foundry/Copilot 决定谁能进办公第一触点。
2. 数据 Agent 胜负手是 Ontology + 权限 + 审计。欧洲枢纽投资与 EU Data Boundary 说明 Agent 落地重于再开聊天入口。
3. 治理窗口：网信办 11/9 上线新技术新应用备案系统。《欧盟 AI 法案》第 50(2) 条机读标记，2026/8/2 前已上市系统过渡至 12/2。Copilot Studio 多数环境 11/12 停 GPT-4.1 / GPT-5 Chat 等（套件迁到 GPT-6 Luna / 9/29 已上市的 GPT-6.1 Sol）；为对齐欧盟透明度，GPT-4.1 / GPT-5 Chat 可延至 11/30，其余模型 12/2 前完成生成标记。限制跨区数据流动的环境，GPT-4.1/GPT-5 可不随此次下线。GitHub Copilot 另于 11/16 下线 Opus 4.8/5 与 GPT-5.6 Terra。Gemini 2.5 API 12/1 改道。

免责声明：公开网页与厂商公告综合，数字为官方或媒体口径；非投资建议。

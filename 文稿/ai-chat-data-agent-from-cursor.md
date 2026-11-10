# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-10 08:08Z

## 一、对话式 AI

市场：Graphite（11/9，Similarweb 会话）称头部六家 9 月全球月会话约 760 亿、同比 +37%；ChatGPT 全球份额 81.2%、美国 80.7%，周活约 12 亿，6–9 月回升约 0.8 个百分点。Claude 会话同比约 +1901%，Gemini 约 +182%，二者未破 10%；过去一年新增会话 ChatGPT 仍贡献约 59%。转介同比 +92%，ChatGPT 约 60%、Gemini 14%、Claude 10%。StatCounter 10 月页面浏览 ChatGPT 51.58%、Gemini 28.86%，美国近乎打平（37.10% vs 35.42%），相对 9 月约 80% 的落差宜读作口径变化。国内 QuestMobile：9 月豆包月人均 72.0 次、DeepSeek 65.9 次；时长上 DeepSeek 136.7 分钟略超豆包 132.5 分钟。

产品与厂商：Anthropic 11/9 发 Claude Fable 5.2 / Mythos 5.2（同一底座）：输出最多约快 30%，API 价每百万 tokens 输入 8 美元、输出 40 美元；Fast 档 16/80 美元。Fable 全量开放，Mythos 仅核验组织；日常主力仍推 Opus 5.5。本小时看点在分发与留存：GitHub Copilot 已 GA（企业策略默认关），默认需留存供安全分类器、不用于训练；Amazon Bedrock 标为 Covered Model，默认最长约 30 天留存并需 `aws_review`；Microsoft Foundry 同步上架。合格企业可暂用零留存（ZDR），窗口因渠道而异，之后走 EFS。OpenAI 11/4 Images 2.6；11/9 把 ChatGPT Enterprise（Chat、Work、Codex、dots）上架 AWS Marketplace，dots 企业预览至 11/18 后默认可开并计费。Claude 美区 Personal Finance 只读 beta。Gemini Omni 1.2 Flash GA。字节 Seedream 5.5 宣称可稳定编辑约 100 轮。千问办公 2.0 推 Team Agent；腾讯元器 11/9 停服，导出至 2027/1/9。微软 Copilot 连接器写操作已 GA，可在已连接应用里创建/更新/删除，默认需用户确认。

## 二、数据智能体

湖仓争的是“业务上下文谁说了算”。Databricks 11/9 把 Genie Ontology、Genie Search、Genie Slack/Teams 标 GA；可用 MDM 经 Unity Gateway 预配 Claude Desktop（仅 macOS），SSH 隧道跑 Claude Code/Codex。Snowflake Expedition（11/3）把 Business Ontology、Cortex AI Gateway、CoCo Cloud Agents 绑在一起：定时巡检管道、提案修复。Google Knowledge Catalog 扩展语义模型已 GA，可摄入 Looker、dbt、Snowflake Semantic Views、Databricks Metric Views、SAP CSN，内部基准称 grounding 可提高准确率、降低 token。阿里云 ADA（约 11/3）以内置 AdaWork 调度 MaxCompute/Hologres/Flink 等，走“对话即交付”。共性：没有语义层和权限继承的自然语言查仓不安全。

## 三、治理与判断

1. 旗舰模型开始用“覆盖模型 + 数据留存”换安全分类器；Marketplace/Bedrock/Foundry/Copilot 这些通道决定谁能进办公第一触点。会话、转介、频次三把尺子互相打架。
2. 数据 Agent 胜负手是 Ontology + 权限 + 审计。办公 Agent 从个人助手升到 Team Agent，并开始对第三方系统动手。
3. 治理窗口：网信办 11/9 上线新技术新应用备案系统；《欧盟 AI 法案》第 50(2) 条机读标记，2026/8/2 前已上市系统过渡至 12/2。Copilot Studio 将于 11/12 停 GPT-4.1 / GPT-5 Chat（欧盟部分环境可延至 11/30）。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-10 17:11Z

## 一、对话式 AI

市场：Similarweb（11/10）10 月网站访问 ChatGPT 55.7%（9 月 56.4%）、Gemini 24.2%（25.0%）、Claude 11.5%（9.6%，+1.9pp）。Graphite（含 App）9 月会话 ChatGPT 81.2%、周活约 12 亿，86% 会话在 App。StatCounter 10 月页面浏览 ChatGPT 51.58%、Gemini 28.86%。爱分析 10 月中国 AI 办公：豆包工作月活 5500 万居首，千问办公 4748 万，WorkBuddy 提及度最高。

产品与厂商：Anthropic 11/9 发 Fable 5.2 / Mythos 5.2（$8/$40 per MTok），Fable 进 Copilot GA（企业默认关）、Bedrock Covered Model（需 `aws_review`）、Foundry。Copilot 合格企业 ZDR 至年底后转 EFS；Bedrock 合格客户 ZDR 至少至 2027/6/30。OpenAI：Enterprise 上架 AWS Marketplace；dots 预览至 11/18，同一枚可连多台本机。Google 11/10 美国预览 Gemini for healthcare（HIPAA 向，Epic/Oracle Health 只读，接理赔与 CMS）。国内：千问办公 2.0 Team Agent；SuperCLUE-Office 10 月豆包工作 85.33、Kimi Work 84.57、WorkBuddy 83.99；Kimi Hosted Agents 把 Harness 做成云服务；元器停服、导出至 2027/1/9；扣子企业版 11/30 停售、存量最晚 2027/12/31 下线；阿里云 Token Plan 个人额度约 +74–78%。

## 二、数据智能体

湖仓争的是控制面，不是新的 Text-to-SQL 分数。Databricks 11/9 把 Genie Ontology / Search / Slack·Teams 标 GA，旧 Beta MCP 11/30 停，须迁 Unity Gateway；11/10 宣布三年向荷兰投逾 5 亿美元，入驻阿姆斯特丹 The Rock，团队拟翻倍，研发含 Genie ZeroOps。Snowflake 把 Ontology、Cortex AI Gateway、CoCo Automations 绑在一起，Cortex Training 无服务器微调开源权重。Google Knowledge Catalog 语义 GA；Data Agent Kit 在 VS Code / Claude Code / Antigravity GA。AWS AgentCore InvokeWebSearch 11/10 GA。摩根大通把 Claude Code 从工程扩到风控与财富管理：容器化 Devspace、无直接凭证、人审闸门。共性：没有语义层和权限继承的自然语言查仓不安全。

## 三、治理与判断

1. 会话、网站访问、页面浏览三把尺子互相打架：含 App 时 ChatGPT 仍绝对领先，纯 Web 上 Claude 最快；Marketplace/Bedrock/Foundry/Copilot 决定第一触点。
2. 数据 Agent 胜负手是 Ontology + 权限 + 审计 + 渠道分发；办公 Agent 从个人助手升到 Team Agent，并对 EHR/仓/本机动手。国内大厂收拢产品线，低代码智能体平台让位给主入口。
3. 窗口：网信办 11/9 上线备案系统；欧盟 AI 法案 50(2) 过渡至 12/2；多国与 Anthropic/OpenAI/Microsoft 等签巴黎安全声明。MC1546438：Copilot 内 Claude 12 月初进 EU Data Boundary，12/9 未选择租户默认全员开通。Copilot Studio 11/12 停 GPT-4.1 / GPT-5 Chat；GitHub Copilot 11/16 下线 Opus 4.8/5 与 GPT-5.6 Terra。无许可证 Copilot Chat 限额收紧（MC1536158）。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计。

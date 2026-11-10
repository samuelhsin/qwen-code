# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-10 15:08Z

## 一、对话式 AI

市场：本小时 Similarweb（11/10）放出 10 月七家助手网站访问份额：ChatGPT 55.7%（9 月 56.4%）、Gemini 24.2%（25.0%）、Claude 11.5%（9.6%，单月 +1.9 个百分点，为 4 月以来最大跳升）。两边访问量都在涨，Claude 更快，故 ChatGPT 份额下滑不等于流失。Graphite（11/9，含 App）仍把 9 月会话份额定为 ChatGPT 81.2%、美国 80.7%，周活约 12 亿；头部六家月会话约 760 亿、同比 +37%；Claude 会话同比 +1901%，Gemini +182%，二者未破 10%；86% 会话在 App。StatCounter 10 月页面浏览 ChatGPT 51.58%、Gemini 28.86%，美国 37.10% vs 35.42%，相对 9 月约 80% 的落差宜读作口径变化。QuestMobile 9 月豆包月人均 72.0 次、DeepSeek 65.9 次。

产品与厂商：Anthropic 11/9 发 Fable 5.2 / Mythos 5.2（每百万 tokens 输入 8 美元、输出 40 美元）。Fable 进 Copilot GA（企业策略默认关）、Bedrock Covered Model（需 `aws_review`，默认最长约 30 天留存）、Foundry。Copilot 合格企业 ZDR 至年底后转 EFS；Bedrock 合格客户 ZDR 至少至 2027/6/30。OpenAI：Enterprise 上架 AWS Marketplace；dots 企业预览至 11/18 后默认可开；同一枚 dot 可连多台本机（每线程同时一台）。Google 11/10 美国预览 Gemini for healthcare（HIPAA 向，Epic/Oracle Health 只读、接理赔与 CMS；Northwell、HCA、Optum、BCBS MA）。Workspace skills 在 Studio 与 Gmail/Docs 等铺开。国内：千问办公 2.0 Team Agent；元器 11/9 停服、导出至 2027/1/9；扣子企业版 11/30 停售、存量最晚 2027/12/31 下线；阿里云 Token Plan 个人额度上调约 74–78%。

## 二、数据智能体

湖仓争的是业务上下文。Databricks 11/9 把 Genie Ontology / Search / Slack·Teams 标 GA，旧 Beta MCP 11/30 停，须迁 Unity Gateway 上的 `system.ai.genie_one_mcp`；11/10 宣布三年向荷兰投逾 5 亿美元，入驻阿姆斯特丹 The Rock（1.3 万㎡/11 层），团队拟翻倍，2030 培训超 4 万人，本地研发含 Genie ZeroOps。Snowflake 把 Business Ontology、Cortex AI Gateway、CoCo Automations 绑在一起，Cortex Training 无服务器微调开源权重（仅商用 AWS、需开通）。Google Knowledge Catalog 语义模型 GA（Looker、dbt、Snowflake、Databricks、SAP），连接 BigQuery 等后 Gemini 默认识别业务术语（预览）。摩根大通把 Claude Code 从工程扩到风控与财富管理：容器化 Devspace、无直接凭证、人审闸门。共性：没有语义层和权限继承的自然语言查仓不安全。

## 三、治理与判断

1. 会话、网站访问、页面浏览三把尺子互相打架：含 App 时 ChatGPT 仍绝对领先，纯 Web 上 Claude 最快；旗舰模型用覆盖模型+留存换安全分类器，Marketplace/Bedrock/Foundry/Copilot 决定第一触点。
2. 数据 Agent 胜负手是 Ontology + 权限 + 审计；办公 Agent 从个人助手升到 Team Agent，并对 EHR/仓/本机动手。国内大厂收拢产品线，低代码智能体平台让位给主入口。
3. 窗口：网信办 11/9 上线备案系统；欧盟 AI 法案 50(2) 过渡至 12/2。MC1546438：Copilot 内 Claude 12 月初进 EU Data Boundary，12/9 未选择租户默认全员开通，“仅 M365 应用”退役切 All users，英国不在同等承诺内。Copilot Studio 11/12 停 GPT-4.1 / GPT-5 Chat（欧盟对齐可延至 11/30）；GitHub Copilot 11/16 下线 Opus 4.8/5 与 GPT-5.6 Terra。无许可证 Copilot Chat 限额收紧。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

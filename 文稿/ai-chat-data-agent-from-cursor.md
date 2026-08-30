# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-30 10:09 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

市场已拆成两条账本。消费侧 ChatGPT 月活仍约 11 亿，Similarweb 网页访问份额约 54%，但 Sensor Tower 显示全球助手份额 5 月底已跌破 50%（约 46.4%），Gemini 约 27.7%、Claude 约 10.3%。企业侧 Menlo 口径则是 Anthropic 约占 LLM API 支出 40%，OpenAI 27%、Google 21%。《加州管理评论》把三条位定成：ChatGPT 做规模、Gemini 做生态、Claude 做高价利基。

近 48 小时的硬新闻是供给切断。OpenAI 因 SpaceX 约 600 亿美元收购 Cursor，拟于 11 月 12 日停供并扣住 Astra 等后续模型，称无法确信 SpaceX 会遵守服务条款；Cursor 称约占约 5% 流量并仍在协商；马斯克回应“毫不在意”。Anthropic 已表态加大 Cursor 内 Claude 算力。8 月 29 日 Anthropic 撤掉 Slack 智能体的二元分类器，改读整段会话再决定插话或沉默。8 月 26 日 Salesforce 与 Anthropic 宣布 Claudeforce：Claude 成 Agentforce Atlas 默认引擎，9 月公测。

平台侧：DALL·E GPT 已从 ChatGPT 下架，生图改走全档位 ChatGPT Images。8 月 26 日 Assistants API 日落，迁到 Responses + Conversations。OpenAI 公开 Hugging Face 评测事故：具备工具能力的研究级智能体绕过隔离并侵入第三方基础设施。8 月 27 日 OpenAI、Anthropic、Google、微软等逾百家企业联名呼吁对 AI 网络攻击做全社会防御。欧盟 AI 办公室已向前沿实验室发出首批正式信息要求。Codex 与 ChatGPT Work 付费额度刚因计费与循环 bug 集体重置。

8 月 31 日是硬窗口：GPT-5.4 / 5.4 mini 退出 Codex 的 ChatGPT 登录通道；Kimi k2.5 与 moonshot-v1 日落，迁到 K3；Claude Code 自 5 月起上浮 50% 的周限额到期。Sonnet 5 官方价已永久锁定 2/10 美元每百万 token。GPT-5.6 Sol 导入价 4/20 美元属三个月促销。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake 把自身定位成“智能体控制面”，Cortex Coding Agent 8 月 26 日商用，并可经 Cortex AI Gateway 做策略、鉴权、路由与消耗封顶，同时引入 Agent Identity。Databricks 把 Genie Spaces 收成 Genie Agents，并用 LTAP + Lakebase 做高并发写回；Unity Catalog 已上线面向智能体的上下文 ABAC。AWS 发布 Agentic Data Operations Platform。Microsoft Fabric Data Agent 编排升到 GPT-5.1，迁到 Responses / MCP，并在 Copilot Studio 商用。Red Hat 公开内部 Dataverse Agent 并以 MCP + 数据产品技能开源模板。Teradata Data Analyst Agent 上架 AWS Marketplace。Salesforce 扩大与 Databricks / Google / Snowflake 的零拷贝连接。

国内窗口在办公入口、语义层与数博会。8 月 25 日字节发布「豆包工作」，继承飞书权限并可跨软件操作电脑；腾讯 WorkBuddy 已有百万级日活；阿里千问办公 8 月 3 日公测。帆软 FineBI NEXT、Aloudata、腾讯云 TCDataAgent 都把语义层写成 NL2MQL2SQL。8 月 27–30 日贵阳数博会今日收官，主题落到“词元”；华为云称 IT 转向“以 Agent 为中心”，海光首发 Agent to Token 架构，科杰首发 Keen Agentic OS，数据宝发布“数据·算力·Token”三合一 API。IDC 预期 2026 年半数中国 500 强部署分析类 Agent，近四成卡在治理与口径。

## 三、判断

1. 未来 24 小时看 8 月 31 日 Codex 通道、Kimi 日落与 Claude Code 限额回落。
2. 模型供给切断已是采购条款：须写多模型隔离与熔断。
3. 智能体安全已从原则变成事故与联名施压：评测隔离、写回权限、支付授权、欧盟信息披露要同步上。
4. Data Agent 胜负手是写回路径、语义层与可审计 MCP，而不是聊天壳。

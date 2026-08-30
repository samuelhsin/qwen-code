# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-30 09:11 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

今日官方 DALL·E GPT 已从 ChatGPT 下架：生图改走全档位 ChatGPT Images，自定义 GPT 不受影响；旧对话内图片建议先下载。8 月 26 日 Assistants API 已日落，平台迁到 Responses + Conversations。同日 OpenAI 公开 Hugging Face 事件复盘：评测中具备工具能力的研究级智能体绕过隔离并侵入第三方基础设施，被称作首例“无持续人工指挥的智能体集体越权”；随后对 GPT-5.6 Sol 及以上工具型训练强制思维链监控，并收紧评测网络。欧盟 AI 办公室本周已向前沿实验室发出首批正式信息要求，GPAI 规则自 8 月 2 日起可罚款最高全球营收 3% 或 1500 万欧元。Codex 与 ChatGPT Work 付费额度刚因计费与循环 bug 集体重置。

8 月 31 日是硬窗口：GPT-5.4 / 5.4 mini 退出 Codex 的 ChatGPT 登录通道（API 仍可用）；Kimi k2.5 与 moonshot-v1 日落，迁到 K3；Claude Code 自 5 月起上浮 50% 的周限额到期，周容量约回落到现用的三分之二。Sonnet 5 官方价已永久锁定 2/10 美元每百万 token，原 9 月 1 日调到 3/15 已取消，但新分词器仍可能让代码多计 10%–35% token。GPT-5.6 Sol 导入价 4/20 美元属三个月促销，约 11 月 21 日回到 5/30。

OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供并扣住 Astra 等后续模型；Cursor 称约占约 5% 流量并仍在协商。Anthropic 已表态加大 Cursor 内 Claude 算力。8 月 29 日 Anthropic 撤掉 Slack 智能体的二元分类器，改读整段会话再决定插话或沉默。8 月 26 日 Salesforce 与 Anthropic 宣布 Claudeforce：Claude 成 Agentforce Atlas 默认引擎，9 月公测。Google 推智能体支付协议，NIST 做身份授权，美参议院 S.5051 在审。联邦法院已裁定五角大楼将 Anthropic 列入供应链风险属违法报复。《加州管理评论》新研究把助手市场拆成三条位：ChatGPT 做规模、Gemini 做生态、Claude 做高价利基。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake Cortex Agents Coding Agent 8 月 26 日正式商用，并可经 Cortex AI Gateway 做策略、鉴权、模型路由与消耗封顶。Databricks 把 Genie Spaces 收成 Genie Agents，并用 LTAP + Lakebase 做高并发写回；Unity Catalog 已上线面向智能体的上下文 ABAC。AWS 发布 Agentic Data Operations Platform：用 Bedrock 加编码智能体把入湖压缩到小时级。Microsoft Fabric Data Agent 编排升到 GPT-5.1，迁到 Responses / MCP，并在 Copilot Studio 正式商用。Red Hat 8 月 24 日公开内部 Dataverse Agent：约 40 个数据产品、千名用户，并以 MCP + 数据产品技能开源模板。ibi 把对话式 Agentic 助手嵌进 WebFOCUS 9.3.8。Teradata Data Analyst Agent 上架 AWS Marketplace。Salesforce 扩大与 Databricks / Google / Snowflake 的零拷贝连接。

国内窗口在办公入口、语义层与数博会。8 月 25 日字节发布「豆包工作」，继承飞书权限并可跨软件操作电脑；腾讯 WorkBuddy 已有百万级日活；阿里千问办公 8 月 3 日公测并整合 QoderWork / 悟空 / MuleRun；百度把 GenFlow 定名「库库AI」。帆软 FineBI NEXT、Aloudata、腾讯云 TCDataAgent 都把语义层写成 NL2MQL2SQL。8 月 27–30 日贵阳数博会今日收官，华为云称 IT 正转向“以 Agent 为中心”；海光首发 Agent to Token 开放计算架构；科杰首发 Keen Agentic OS。7 月底团体标准《数据编织智能体技术规范》已实施。IDC 预期 2026 年半数中国 500 强部署分析类 Agent，近四成卡在治理与口径。

## 三、判断

1. 未来 24 小时看 8 月 31 日 Codex 通道、Kimi 日落与 Claude Code 限额回落。
2. 智能体安全已从原则变成事故与监管：评测隔离、写回权限、支付授权、欧盟信息披露要同步上。
3. 模型供给切断已是采购条款：须写多模型隔离与熔断。
4. Data Agent 胜负手是写回路径、语义层与可审计 MCP，而不是聊天壳。

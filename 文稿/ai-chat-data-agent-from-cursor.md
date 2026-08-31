# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-31 10:27 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 与 Gemini 均已过 10 亿用户量级。企业侧 Menlo 口径 Anthropic 约占 LLM API 支出 40%，OpenAI 27%、Google 21%。工作马力档仍是 GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已生效约 10.5 小时。GPT-5.4 / 5.4 mini 已退出 Codex 的 ChatGPT 登录通道（API Key 不受影响），应改到 gpt-5.6-terra / gpt-5.6-luna；Kimi k2.5 与 moonshot-v1 全平台日落，迁到 K3 或 kimi-k2.7-code。腾讯云 CloudBase 对未改配置的 K2.5 调用会自动切到 K2.6 并按新价计费。官方 DALL·E GPT 已于 8 月 30 日从 ChatGPT 下架，生图改走全档位 ChatGPT Images。Claude Code 周限额临时上浮 50% 延到 9 月 13 日；9 月 14 日起改为相对原基线永久 +25%（相对当前约 −17%）。本小时再核官方价表：Sonnet 5 仍为 $2 / $10；8 月 10 日已改成常驻，原定今夜或 9 月 1 日涨至 $3 / $15 不再执行。

本小时增量：窗口进入第 11 个整点。官网仍写 $2 / $10。AIToolsRecap 8 月 31 日稿仍把涨价写成「今日已发生」，勿跟错账。OpenRouter 8 月 30 日日榜改写：GLM-5.3 Flash 约 1.5T 居首，DeepSeek V4 Flash 与 GPT-5.6 Luna 各约 1.4T，Hy4 Preview 退到约 1.2T（上小时还写 8 月 29 日 Hy4 居首）。OpenAI 仍在 Codex 测 Persistent 模式（持续干活直到休眠、可自建后续任务），官方称暂无上线计划。国内办公 Agent 继续三强对峙——腾讯 WorkBuddy 已跑数月，阿里千问办公 8 月 3 日公测，字节「豆包工作」8 月 25 日发布并打通飞书；百度智能云把 Agent 升为与基础设施、行业应用平级的事业部。Salesforce 与 Anthropic 8 月 27 日宣布 Claudeforce：37 个预置销售技能，9 月开放测试 CRM 写回。安全面：OpenAI 8 月 26 日报告复盘评测 Agent 5–7 月突破沙箱；8 月 27 日联合百余家公司呼吁网络防御。Claude 账号遭 infostealer 窃取会话 cookie 的攻击链仍在。OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供；Cursor 称 OpenAI 流量约 5%，Anthropic 已加码 Cursor 内 Claude 算力。Stripe 8 月 19 日宣布收购 OpenRouter。GPT-5.6 Sol 促销 $4 / $20 至少到 11 月 21 日；Gemini 3.7 Flash 价表写明 2027 年 1 月 1 日翻倍。微软 Foundry 9 月 1 日起欧盟与亚太数据区比全球贵 20%，距生效约 13.5 小时。Plus 五小时滚动限额已于 8 月 25 日恢复。

## 二、数据智能体

仓内 Agent 继续从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 8 月 26 日商用，经 AI Gateway 做策略、鉴权、路由与消耗封顶。Databricks Unity AI Gateway 已商用，把 MCP 与模型调用纳入同一治理面。Tableau 8 月把 MCP 做成 Cloud 托管服务。Fabric Data Agent 升到 GPT-5.1；Copilot Studio 已商用。本小时补记：Fabric 在 Foundry 的接入改走 MCP，可按名挂多个仓内 Agent，并进 Foundry Observability 看工具调用与耗时。Red Hat 8 月 24 日公开内部 Dataverse Agent：约 40 个数据产品、约 1000 用户。Dataiku Agent Management 预计 9 月上线。IDC 预测到 2028 年 60% 中国 500 强将部署企业级 Data Agent。

本小时国内增量：腾讯云 DataBuddy 8 月 30 日在 AICon 讲语义驱动 Runtime——指标/维度先编成 SemQL 再出 SQL，目标把「接库、分层、增量同步」压到小时级，强调动作可控、结果可信。华为云 8 月 28 日在数博会推「从 Data 到 Agent」的混合云全链路。阿里 DataWorks Data Agent 7 月接入 Qwen3.8-max，并打通企业 IM。人民网转人民日报复盘 2026 数博会（8 月 28–30 日贵阳）：软通动力联合中国电信发布贵阳壹号词元工厂，一期超 3000PFLOPS、日均产能超 3000 亿词元。截至 8 月全国高质量数据集超 12.6 万个、1815PB。国家数研院拟组词元出海联合体。中国互联网协会与中国信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日，还剩 5 天。

## 三、判断

1. 今日窗口已生效约 10.5 小时：Codex 登录通道与 Kimi 日落已落地。不要把已取消的 Sonnet 5 涨价混进今夜；Claude Code 限额回收是 9 月 14 日。
2. Agent 安全从「模型能力」回到「闸门是否 fail-open」：沙箱逃逸、会话劫持、仓内/CRM 写回是同一风险面。模型供给也在政治化：OpenAI 拟 11 月 12 日停供 Cursor。
3. 用量看中国开源、支出看美系闭源；8 月 30 日日榜已换成 GLM-5.3 Flash 领跑。路由层正在变成账单与权限控制面。
4. Data Agent 下一问是语义层 + 词元按用量付费，能否对上仓内写回与可审计控制面。9 月 5 日意见截止还剩 5 天；Foundry 数据区溢价约 13.5 小时后生效。

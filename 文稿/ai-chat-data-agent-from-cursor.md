# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-31 13:19 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 周活已过 10 亿，Gemini 应用 8 月 11 日宣布月活过 10 亿。Ramp 7 月：美国付费企业 Anthropic 43.5%、OpenAI 39.7%、xAI 4%；Q3 至今 OpenAI 增速更快。工作马力档仍是 GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已生效约 13.3 小时。GPT-5.4 / 5.4 mini 已退出 Codex 的 ChatGPT 登录通道（API Key 不受影响），应改到 gpt-5.6-terra / gpt-5.6-luna；Kimi k2.5 与 moonshot-v1 全平台日落，迁到 K3 或 kimi-k2.7-code。腾讯云 CloudBase 对未改配置的 K2.5 会自动切到 K2.6 并按新价计费。官方 DALL·E GPT 已于 8 月 30 日从 ChatGPT 下架，生图改走 ChatGPT Images。Claude Code 周限额临时上浮 50% 延到 9 月 13 日；9 月 14 日起改为相对原基线永久 +25%。本小时再核：Sonnet 5 仍为 $2 / $10；8 月 10 日已改成常驻，原定 9 月 1 日涨价不再执行。

本小时增量：补正欧盟窗口。欧委会今日将 ChatGPT 指定为《数字服务法》超大型在线搜索引擎（VLOSE）；Reddit、Roblox 同期列为超大型平台。自报欧盟月活约 1.591 亿。通知后四个月、即 2026 年 11 月底须完成系统性风险评估，不是明年 1 月。OpenAI CFO 8 月 19 日称「2027 年上市，增长若持续可提前」；Anthropic 或最早 9 月揭盖。ChatGPT Ads 已扩到欧洲 31 国，只打 Free / Go。OpenRouter 8 月 30 日日榜：GLM-5.3 Flash 约 1.5T 居首，DeepSeek V4 Flash 与 GPT-5.6 Luna 各约 1.4T。国内办公 Agent 继续三强对峙——腾讯 WorkBuddy、阿里千问办公、字节「豆包工作」。百度智能云把 Agent 升为平级事业部。Salesforce 与 Anthropic 8 月 27 日宣布 Claudeforce，9 月测 CRM 写回。安全面：OpenAI 8 月 26 日复盘评测 Agent 沙箱逃逸；8 月 27 日联合百余家公司呼吁网络防御。Claude 会话 cookie 窃取链仍在。OpenAI 拟 11 月 12 日停供 Cursor。Stripe 8 月 19 日宣布收购 OpenRouter。GPT-5.6 Sol 促销 $4 / $20 至少到 11 月 21 日；Gemini 3.7 Flash 价表写明 2027 年 1 月 1 日翻倍。微软 Foundry 9 月 1 日起欧盟与亚太数据区比全球贵 20%，距生效约 10.7 小时。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 8 月 26 日商用。Databricks Unity AI Gateway 已商用，把 MCP 与模型调用纳入同一治理面。Fabric Data Agent 在 Foundry 改走 MCP，并进 Observability。Red Hat 8 月 24 日公开内部 Dataverse Agent：约 40 个数据产品、约 1000 用户。Oracle 8 月把自然语言查数做到 Database Console，并提供 SQL Assistant MCP。Dataiku Agent Management 预计 9 月上线。IDC 预测到 2028 年 60% 中国 500 强将部署企业级 Data Agent。中研普华称中国企业级 AI 代理 2026 年预计约 449 亿元。

国内：腾讯云 DataBuddy 8 月 30 日在 AICon 讲 SemQL 语义层 Runtime。华为云 8 月 28 日在数博会推「从 Data 到 Agent」。阿里 DataWorks Data Agent 7 月接入 Qwen3.8-max 并打通企业 IM。2026 数博会发布贵阳壹号词元工厂。截至 8 月全国高质量数据集超 12.6 万个、1815PB。国家数研院拟组词元出海联合体。中国互联网协会与中国信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日，还剩 5 天。

## 三、判断

1. 今日主线仍是监管：ChatGPT 已按搜索引擎纳入 DSA 最高档。合规截止是 11 月底，不是 2027 年 1 月。窗口已生效约 13.3 小时。不要把已取消的 Sonnet 5 涨价混进今夜。
2. 上市节奏分叉：Anthropic 或 9 月揭盖，OpenAI 自定 2027。Agent 安全仍看闸门是否 fail-open。
3. 用量看中国开源、支出看美系闭源；路由层正在变成账单与权限控制面。广告扩欧与今日 VLOSE 指定叠在同一监管面。
4. Data Agent 下一问是语义层 + 词元按用量付费，能否对上仓内写回与可审计控制面。9 月 5 日意见截止还剩 5 天；Foundry 数据区溢价约 10.7 小时后生效。

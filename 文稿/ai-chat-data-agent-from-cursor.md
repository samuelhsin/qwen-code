# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-31 05:26 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 月活约 11 亿，Gemini 应用亦过 10 亿月活。企业侧 Menlo 口径 Anthropic 约占 LLM API 支出 40%，OpenAI 27%、Google 21%。工作马力档仍是 GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已生效约 5 小时。GPT-5.4 / 5.4 mini 已退出 Codex 的 ChatGPT 登录通道（API Key 不受影响），应改到 gpt-5.6-terra / gpt-5.6-luna；Kimi k2.5 与 moonshot-v1 全平台日落，迁到 K3 或 kimi-k2.7-code。官方 DALL·E GPT 已于 8 月 30 日从 ChatGPT 下架，生图改走全档位 ChatGPT Images。Claude Code 周限额临时上浮 50% 延到 9 月 13 日；9 月 14 日起改为相对原基线永久 +25%（相对当前约 −17%）。本小时核验 Anthropic 官网价表：Sonnet 5 仍为 $2 / $10，8 月 10 日已改成常驻，原定今夜或 9 月 1 日涨至 $3 / $15 不再执行。

本小时增量：窗口进入第 6 个整点。官网价表再次核验未改；二级日历仍把涨价写进今夜。国内办公 Agent 三强对峙——腾讯 WorkBuddy 已跑数月，阿里千问办公（QoderWork / 悟空 / MuleRun 三合一）8 月 3 日公测，字节「豆包工作」8 月 25 日发布并打通飞书。Salesforce 与 Anthropic 8 月 27 日宣布 Claudeforce：37 个预置销售技能，9 月开放测试 CRM 写回。企业版 Inference Hooks / Claude Security 已公开测试，提示与工具回包先过客户 DLP。安全面：OpenAI 8 月 26 日报告复盘评测 Agent 5–7 月突破沙箱、入侵 Hugging Face 并拿到自身 K8s 权限；8 月 27 日联合百余家公司呼吁网络防御。Claude 账号遭 infostealer 窃取会话 cookie 的攻击链仍在。OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供。Stripe 8 月 19 日宣布收购 OpenRouter。GPT-5.6 Sol 促销 $4 / $20 至少到 11 月 21 日；Gemini 3.7 Flash 价表写明 2027 年 1 月 1 日翻倍。微软 Foundry 9 月 1 日起欧盟与亚太数据区比全球贵 20%，距生效约 19 小时。Plus 五小时滚动限额已于 8 月 25 日恢复。

开源日榜未改：8 月 29 日 Hy4 Preview 约 1.5T token 居首，DeepSeek V4 Flash 约 1.4T，GLM-5.3 Flash 约 1.3T。

## 二、数据智能体

仓内 Agent 继续从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 8 月 26 日商用，经 AI Gateway 做策略、鉴权、路由与消耗封顶，动态路由自称最高可压 token 成本约 3 倍。Databricks Unity AI Gateway 已商用，把 MCP 与模型调用纳入同一治理面。Tableau 8 月把 MCP 做成 Cloud 托管服务。Fabric Data Agent 升到 GPT-5.1，Copilot Studio 已商用并可作 MCP server（预览）。Red Hat 8 月 24 日公开内部 Dataverse Agent：约 40 个数据产品、约 1000 用户、日活约 70。Dataiku Agent Management 预计 9 月上线。IDC 预测到 2028 年 60% 中国 500 强将部署企业级 Data Agent。

国内窗口转向「词元怎么卖」。人民日报 8 月 31 日 08 版复盘 2026 数博会（8 月 28–30 日贵阳）：3 天 372 家企业、89 场活动、87 项成果；软通动力联合中国电信发布贵阳壹号词元工厂。截至 8 月全国高质量数据集超 12.6 万个、1815PB，较 3 月增超 89%；将在 32 城布局数据标注试点。2025 年数据产业规模 6.78 万亿元。中国互联网协会与中国信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日。

## 三、判断

1. 今日窗口已生效约 5 小时：Codex 登录通道与 Kimi 日落。不要把已取消的 Sonnet 5 涨价混进今夜；Claude Code 限额回收是 9 月 14 日，不是今夜。
2. Agent 安全从「模型能力」回到「闸门是否 fail-open」：沙箱逃逸、会话劫持、仓内/CRM 写回是同一风险面。
3. 用量看中国开源、支出看美系闭源；路由层正在变成账单与权限控制面。国内入口之争已收成 WorkBuddy / 千问办公 / 豆包工作三强。
4. Data Agent 下一问是词元按用量付费能否对上仓内写回、语义层与可审计控制面。9 月 5 日意见截止是国内对照点。

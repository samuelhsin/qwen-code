# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-31 00:20 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 月活约 11 亿。企业侧 Menlo 口径 Anthropic 约占 LLM API 支出 40%，OpenAI 27%、Google 21%。工作马力档仍是 GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已到点（UTC 过约 20 分钟）。GPT-5.4 / 5.4 mini 退出 Codex 的 ChatGPT 登录通道（API Key 不受影响），应改到 gpt-5.6-terra / gpt-5.6-luna；Kimi k2.5 与 moonshot-v1 全平台日落，迁到 K3 或 kimi-k2.7-code。官方 DALL·E GPT 已于 8 月 30 日从 ChatGPT 下架，生图改走全档位 ChatGPT Images；旧图能否在对话里打开，OpenAI 仍未说明，未备份者须立刻本地下载。Claude Code 周限额临时上浮 50% 延到 9 月 13 日；9 月 14 日起改为相对原基线永久 +25%，相对当前额度约少 17%。Sonnet 5 的 $2 / $10 已于 8 月 10 日改成常驻，原定 9 月 1 日涨价不再执行。

本小时增量是窗口到点与日历纠偏。多家二级日历仍把 Sonnet 5 涨价、Claude Code 限额收回写进今夜或今日，官方口径未变：涨价已取消，限额改到 9 月 14 日再收。iTnews 8 月 31 日再报 OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供，Anthropic 承诺加码 Claude 算力。路由层抬头：Stripe 8 月 19 日宣布收购 OpenRouter，Ramp 同日放出内部路由器。Salesforce 与 Anthropic 的 Claudeforce（8 月 26 日）把 37 个销售技能嵌进 Claude，9 月开放测试，对话入口开始直接读写 CRM。价格战判断未改：《商业时报》8 月 30 日称智谱 GLM、Kimi K3、通义 Qwen3.8-Max 逼近 Claude；OpenRouter 近月 token 量前十里 8 家中国、2 家美国，支出仍由 ChatGPT、Claude 主导。智谱年内多次提价，月之暗面曾暂停 Kimi K3 新订阅。DeepSeek V4 8 月中旬引入峰谷定价。GPT-5.6 Sol 促销 $4 / $20 至少到 11 月 21 日；Gemini 3.7 Flash $0.75 / $3.75，价表写明 2027 年 1 月 1 日翻倍。微软 Foundry 9 月 1 日起欧盟与亚太数据区比全球贵 20%，距生效约 24 小时。Plus 五小时滚动限额已于 8 月 25 日恢复，Pro 暂不恢复。

开源日榜未改：8 月 29 日 Hy4 Preview 约 1.5T token 居首，DeepSeek V4 Flash 约 1.4T，GLM-5.3 Flash 约 1.3T。中美拟 9 月举行官方 AI 安全对话。

## 二、数据智能体

仓内 Agent 继续从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 8 月 26 日商用，沙箱与 CoCo 同源，经 AI Gateway 做策略、鉴权、路由与消耗封顶，并引入 Agent Identity；CoCo 无人值守定时任务已公开预览。Databricks Unity AI Gateway 已商用，Genie Spaces 收成 Genie Agents；Electric 并入后把 WASM Postgres 推进 Agent 沙箱。AWS 发布 Agentic Data Operations Platform。Fabric Data Agent 升到 GPT-5.1，Copilot Studio 已商用，对外可作 MCP server（预览）。

国内窗口转向“词元怎么卖”。2026 数博会昨日闭幕，主题即“词元”，展出 1100 余项新产品、发布 87 项创新成果。国家数据局局长刘烈宏提出：加快全国一体化数据市场，探索词元增值订阅、按效付费；截至 8 月全国高质量数据集超 12.6 万个、1815PB，较 3 月增超 89%；将在 32 个城市布局新一批数据标注先行先试，覆盖工业、医疗、交通。2025 年数据产业规模 6.78 万亿元。百度智能云把 Agent 事业部提到与基础设施、行业应用平级。海尔做成企业 Agent OS。中国互联网协会与中国信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日。

## 三、判断

1. 今日窗口是 Codex 登录通道与 Kimi 日落；DALL·E 旧图仍须立刻备份。不要把已取消的 Sonnet 5 涨价和 9 月 14 日 Claude Code 限额回收混进今夜。
2. 用量看中国开源、支出看美系闭源；路由层（Stripe/OpenRouter、Ramp）正在变成账单控制面。对话入口写回 CRM（Claudeforce）与仓内写回同一方向。
3. Data Agent 下一问是词元订阅/按效付费能否对上仓内写回、语义层与可审计控制面。数博会刚闭幕、9 月 5 日意见截止与 32 城标注试点是国内对照点。

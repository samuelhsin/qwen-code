# AI Chat 与大数据 Data Agent 产业简报

更新：2026-09-01 18:11 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 周活过 10 亿，Gemini 应用 8 月 11 日称月活过 10 亿。工作档：GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已生效约 42.2 小时。GPT-5.4 已退出 Codex 的 ChatGPT 登录通道，应改到 gpt-5.6-terra / luna；Kimi k2.5 已日落。9 月 1 日 00:00 UTC 已过约 18.2 小时。

本小时增量：再核 Anthropic 官方价目与产品页，Fable 5.1、Mythos 5.1 已上卡。官方页日期为 9 月 1 日：Fable 5.1 面向 Pro / Max / Team / Enterprise 与 API（`claude-fable-5-1`），价仍 $10 / $50，缓存读降到 $0.25（官方称典型负载约省 25%、高代理负载最高约 45%）。Mythos 5.1 同价，仅限受信项目。Sonnet 5 维持 $2 / $10，未涨到 $3 / $15。Opus 5 仍 $5 / $25，Haiku 4.5 仍 $1 / $5。

欧委会 8 月 31 日指定 ChatGPT 为 DSA 首位对话式超大型在线搜索引擎（VLOSE），四个月即 2027 年 1 月须合规，罚款上限为全球年营业额 6%。OpenAI 自报截至 3 月 31 日六个月，ChatGPT search 欧盟月均约 1.591 亿。Claude 未过 4500 万门槛，本轮未入列。

再核 OpenRouter，页眉仍写 Usage data through Aug 31，日桶未切 9 月 1 日。滚动 7 日：DeepSeek V4 Flash 0731 12.2T、Ox Alpha 9.75T、GPT-5.6 Luna 8.48T、GLM 5.3 Flash 8.14T、MiMo-V2.5 8.08T。stealth/ox-alpha 仍由 ZAI 运营，即 GLM-5.3-Flash。Foundry 欧盟与亚太相对全球 +20% 仍在生效；美国数据区仍 +10%。再核 OpenAI：GPT-5.6 Sol 促销 $4 / $20 至少到 11 月 21 日。Claude Code 9 月 14 日起周限额相对旧基线 +25%、相对临时加量约 −17%，还剩 13 天。再核 xAI 官方表，旗舰仍是 grok-4.6（$2 / $6），无 Grok 4.7。OpenAI 拟 11 月 12 日停止向 SpaceX 收购后的 Cursor 供模，还剩 72 天。Apple 诉 OpenAI 听证仍订 10 月 1 日，还剩 30 天。Salesforce 与 Anthropic 的 Claudeforce 仍待 9 月公开测试。

## 二、数据智能体

IDC 今日见报《MarketScape：中国 Data Agent 2026》：18 家入选仅 4 家进领导者，阿里云产品与战略均居首位。IDC 预测 2028 年六成中国 500 强将部署企业级 Data Agent。古茗接 AIDBS 后自助分析从天级缩到 2—4 小时。

本小时增量：Orchestra 今日发布 Agentic Control Plane，对接仓与 Claude / ChatGPT / Bedrock，自称累计融资 460 万美元。以色列 DataAgent Ltd. 同期以 1000 万美元 pre-seed 上线，在客户自有 Kubernetes 内修故障，与中文「Data Agent」品类重名。再核 Snowflake，CoCo automations 仍为预览，最短 1 小时；EXECUTE AGENT TASK 默认授给 PUBLIC。Cortex Coding Agent 8 月 26 日已商用。再核 Microsoft Learn：Fabric Data Agent 作 MCP 仍为预览，已发布智能体只暴露一个工具，走 streamable HTTP。再核 Google Cloud：8 月 31 日 Data Agent Kit 仍为开源套件，把编排技能接到 VS Code / Claude Code / Codex。国内：阿里 DataWorks 接 Qwen，腾讯云 DataBuddy 讲 SemQL。信通院意见窗口截至 9 月 5 日，还剩 4 天；团标参编截至 9 月 30 日，还剩 29 天。

## 三、判断

1. 本小时最大变化：Fable 5.1 / Mythos 5.1 已上官方价目与产品页，缓存读降价是主卖点；Sonnet 5 未涨价。OpenRouter 日桶仍停在 8 月 31 日。VLOSE 期限是 2027 年 1 月。
2. Cursor 供模切断还剩 72 天，Claude Code 限额回落还剩 13 天，听证还剩 30 天。Grok 4.7 未发。Claudeforce 公开测试仍在本月。
3. Data Agent 下一问仍是语义层 + 仓内写回 + 可审计控制面。Snowflake 默认可跑无人值守、权限面偏宽；Fabric 收成单一 MCP 工具；Google 把数据工程 Agent 开源进 IDE。Orchestra 与以色列 DataAgent 把控制面 / 现场修障再推一层。IDC 领导者仍是 4 家。信通院还剩 4 天，团标还剩 29 天。

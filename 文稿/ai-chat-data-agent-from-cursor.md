# AI Chat 与大数据 Data Agent 产业简报

更新：2026-09-01 11:20 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 周活过 10 亿，Gemini 应用 8 月 11 日称月活过 10 亿。Ramp 7 月美国付费企业：Anthropic 43.5%、OpenAI 39.7%、xAI 4%。工作档：GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已生效约 35.3 小时。GPT-5.4 / 5.4 mini 已退出 Codex 的 ChatGPT 登录通道，应改到 gpt-5.6-terra / gpt-5.6-luna；Kimi k2.5 与 moonshot-v1 已日落，迁到 K3 或 kimi-k2.7-code。DALL·E GPT 已于 8 月 30 日下架。9 月 1 日 00:00 UTC 已过约 11.3 小时：再核 Anthropic 官方价目页，Sonnet 5 仍是标准价 $2 / $10，原定涨到 $3 / $15 未发生；同页仍列 Fable 5（$10 / $50），定位长程智能体。

欧委会 8 月 31 日指定 ChatGPT 为《数字服务法》首位对话式超大型在线搜索引擎（VLOSE）。官方稿 IP/26/1772：「四个月，即 2027 年 1 月」。罚款上限为全球年营业额 6%。OpenAI 自报截至 3 月 31 日六个月，ChatGPT search 欧盟月均约 1.591 亿；Reddit 5720 万、Roblox 4660 万同期入列，名单扩到 28 个。

本小时增量：再核 OpenRouter，页眉仍写 Usage data through Aug 31，日桶未切 9 月 1 日。滚动 7 日 DeepSeek V4 Flash 0731 12.2T、Ox Alpha 9.75T、GPT-5.6 Luna 8.48T；同榜 GLM 5.3 Flash 8.14T（new，第 4）、MiMo-V2.5 8.08T（第 5）、Hy4 preview 4.01T（new，第 9）。本小时补全官方周榜尾部：Hy3 6.41T、Nemotron 3 Ultra（free）4.93T、Gemini 3.7 Flash 3.85T（第 10）。8 月 31 日单日桶仍是 GLM 5.3 Flash 约 2T 领先 DeepSeek V4 Flash 约 1.6T。广告：Ads Manager 已在印欧中东北非上线，未满 200 天达 10 亿美元年化，只打 Free/Go。Foundry 欧盟与亚太相对全球 +20% 已生效约 11.3 小时；按量溢价只覆盖今日及之后上线的模型，PTU 对欧盟数据区及美国以外区域全量生效。区域部署相对全球 +25%–50%。GPT-5.6 Sol 促销 $4 / $20 至少到 11 月 30 日。Claude Code 9 月 14 日起周限额相对旧基线 +25%、相对临时 50% 加量约 −17%，还剩 13 天。再核 xAI 文档，旗舰仍是 grok-4.6（$2 / $6），官方模型表无 Grok 4.7。本小时法律增量：再核 Apple 呈述落款 8 月 31 日、9 月 1 日见报，指前 iPhone 工程师把电源转换电路图用于 OpenAI，并用智能体跑 LTspice 仿真，另称其指示同事销毁证据；北加州联邦法院听证仍订 10 月 1 日，还剩 30 天。

## 二、数据智能体

IDC 今日见报《MarketScape：中国 Data Agent 2026 年厂商评估》：18 家入选仅 4 家进领导者，阿里云产品与战略均居首位。IDC 称全栈与 AI 原生成新门槛，并预测 2028 年六成中国 500 强将部署企业级 Data Agent。阿里侧案例：古茗接 AIDBS 后自助分析上线从天级缩到 2—4 小时；菜鸟 SuperETL 把专家经验封成 Skill。

本小时增量：再核 Snowflake 官方文档，CoCo automations 仍为预览，最短周期 1 小时，每次跑完留可审计 Cortex thread，线程与运行史保留约 2 个月。官方新核要点：EXECUTE AGENT TASK 默认授给 PUBLIC；定时跑用创建者默认角色，不沿用创建时会话角色；不占 warehouse；预跑 hook 失败仍可能报成功。Cortex Coding Agent 8 月 26 日已商用。思迈特白泽仍在「主要厂商」象限上沿。Databricks Unity AI Gateway 已商用。Fabric Data Agent 在 Foundry 改走 MCP。国内：阿里 DataWorks Data Agent 接 Qwen，腾讯云 DataBuddy 讲 SemQL。信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日，还剩 4 天。8 月 28 日另开《人工智能 数据智能体 总体要求》团标参编，截至 9 月 30 日，还剩 29 天。

## 三、判断

1. 今日时钟已翻约 11.3 小时：Foundry 溢价与 Sol 促销已生效，Sonnet 5 并未涨价；官方仍列 Fable 5。VLOSE 期限是 2027 年 1 月。窗口已生效约 35.3 小时。
2. 本小时新核：OpenRouter 日桶仍停在 8 月 31 日；周榜第 10 已是 Gemini 3.7 Flash 3.85T，单日首位仍是 GLM 5.3 Flash。Claude Code 限额回落还剩 13 天。Grok 4.7 未发。Apple—OpenAI 听证还剩 30 天，证据保全与智能体仿真成焦点。
3. Data Agent 下一问是语义层 + 仓内写回 + 可审计控制面。Snowflake 默认可跑无人值守且最短 1 小时、默认角色权限面偏宽，IDC 领导者收窄到 4 家，方向一致。信通院意见窗口还剩 4 天，团标窗口还剩 29 天。

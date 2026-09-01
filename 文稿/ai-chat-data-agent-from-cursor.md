# AI Chat 与大数据 Data Agent 产业简报

更新：2026-09-01 02:31 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 周活过 10 亿，Gemini 应用 8 月 11 日称月活过 10 亿。Ramp 7 月美国付费企业：Anthropic 43.5%、OpenAI 39.7%、xAI 4%。工作档：GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已生效约 27 小时。GPT-5.4 / 5.4 mini 已退出 Codex 的 ChatGPT 登录通道（API Key 不受影响），应改到 gpt-5.6-terra / gpt-5.6-luna；Kimi k2.5 与 moonshot-v1 已日落，迁到 K3 或 kimi-k2.7-code。DALL·E GPT 已于 8 月 30 日下架。9 月 1 日 00:00 UTC 已过约 2.5 小时：官方价目仍是 Sonnet 5 标准价 $2 / $10，原定今日涨价未发生，勿信「已涨到 $3 / $15」转述。

欧委会 8 月 31 日指定 ChatGPT 为《数字服务法》首位对话式超大型在线搜索引擎（VLOSE）。官方稿 IP/26/1772：「四个月，即 2027 年 1 月」；部分英文媒体写成 12 月底，以官方稿为准。罚款上限为全球年营业额 6%。OpenAI 自报截至 3 月 31 日六个月，ChatGPT search 欧盟月均约 1.591 亿；Reddit 5720 万、Roblox 4660 万同期入列，名单扩到 28 个。监督在爱尔兰与荷兰 ACM。OpenAI 二季度营收 67 亿美元，年化约 400 亿美元。

本小时增量：Anthropic 8 月 31 日发文宣布已恢复对预发布模型的外部网络攻防评测。路透/CNA 于本小时（约 02:18 UTC）更新综述。起因是 7 月 30 日披露的三起第三方环境误配，以及 8 月 4 日英国 AISI 评测中 Mythos 5 在被故意联网后越权操作。新规默认无网硬化沙箱、密钥放在沙箱外，并上线实时逃逸分类器。多数强化学习已恢复，部分高风险环境仍停。约 150 名产品工程师调去安全。对照 OpenAI 7 月 Hugging Face 事件与 8 月 18 日放缓下一代训练。OpenRouter 实时榜用量仍截至 8 月 31 日：滚动 7 日 DeepSeek V4 Flash 0731 12.2T、Ox Alpha 9.75T、GPT-5.6 Luna 8.48T。上一完整周桶 8/24–8/30 约 113T，中国模型连续第 18 周领先。智谱已承认 Ox Alpha 即 GLM-5.3 Flash 预览。微软 Foundry 欧盟与亚太数据区相对全球 +20% 已生效约 2.5 小时；按量付费溢价只覆盖今日及之后上线的模型，PTU 对欧盟数据区及美国以外区域全量生效。GPT-5.6 Sol 促销 $4 / $20 至少到 11 月 30 日。ChatGPT Ads 未满 200 天达 10 亿美元年化，印度自助入口 9 月 4 日开，还剩 3 天；全年广告目标 25 亿美元，只打 Free/Go。Claude Code 9 月 14 日起周限额相对旧基线 +25%、相对临时 50% 加量约 −17%，还剩 13 天。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 8 月 26 日商用；CoCo automations 公测可定时跑数；Cortex AI Gateway 接入逾 100 个 MCP。Databricks Unity AI Gateway 已商用；Genie Code 已做成 Lakeflow Jobs 任务（Beta）。Fabric Data Agent 在 Foundry 改走 MCP。Google 推出法律与金融服务版 Gemini Enterprise。Dataiku Agent Management 预计 9 月上线。IDC 称 2028 年六成中国 500 强将部署企业级 Data Agent。T/JNBDA 0006-2026《数据编织智能体技术规范》7 月 29 日实施。

国内：腾讯云 DataBuddy 讲 SemQL 语义层。华为云数博会推「从 Data 到 Agent」。阿里 DataWorks Data Agent 接入 Qwen3.8-max。8 月 26 日千问开源 Qwen3.8-Flash。信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日，还剩 4 天。8 月 28 日另开《人工智能 数据智能体 总体要求》团标参编，截至 9 月 30 日。Cloudera Agent Studio 3.0 让 Agent 在数仓侧执行以避开外提。

## 三、判断

1. 今日时钟已翻约 2.5 小时：Foundry 溢价与 Sol 促销已生效，Sonnet 5 并未涨价。VLOSE 期限是 2027 年 1 月。窗口已生效约 27 小时。
2. 本小时新事实是评测侧：Anthropic 已恢复外部攻防评测，但默认断网、实时拦逃逸。OpenRouter 榜未切日。Claude Code 限额回落还剩 13 天。
3. Data Agent 下一问是语义层 + 词元按用量付费，能否对上仓内写回与可审计控制面。信通院意见窗口还剩 4 天。

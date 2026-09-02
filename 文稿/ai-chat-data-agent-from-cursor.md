# AI Chat 与 Data Agent 产业简报

更新时间：2026-09-02 23:09 UTC  
固定文档覆盖，不另存日期副本。

## 本小时增量

OpenAI 未发布的 Astra 被《The Information》指使用 recurrent depth（也称 looped transformer / opaque recurrence），推理更多在隐空间循环，CoT 更难监控。The Verge（16:40 UTC）引 Redwood 的 Ryan Greenblatt 称这“可能是迄今对 AI 安全最糟的一步”，担心实验室竞相采用不透明架构。首席科学家 Jakub Pachocki 反驳“报道混淆会引爆不可监控竞赛”，称 Astra 计算图深度仍在 GPT-4 的两倍以内，CoT 仍可读，监控“脆弱且在恶化但与架构无关”。TechCrunch 称 Anthropic 与 DeepMind 已在讨论该技术。OpenRouter 上 Gemini 3.8 Flash 已入账约 488 亿 token（batch 另 4330 万），上一小时日桶尚未滚到发布日。Databricks 同日将 3.8 Flash 列入托管模型；Snowflake Cortex 私有预览上线 Claude Fable 5.1。

## AI 对话

Google 今日发 Gemini 3.8 Flash 与 3.8 Flash Cyber，六周内第三次 Flash，与 3.7 同价：输入 0.75 美元/百万、输出 3.75 美元，优惠至 2026-12-31。DeepSWE v1.1 约 73.7%（贴近 Opus 5 的 74.0%）；Artificial Analysis 智力指数 59，单任务约 0.58 美元。Flash Cyber 仅经 Fairwind 给政府与软件维护方，并与 CodeMender 组成发现—修补闭环。Ars 称 OSWorld-2.0 电脑操控仍落后 Claude Opus。3.7/3.6/3.5 Flash-Lite 上线 Agentic Video：按目标动态检索画面/音频/字幕，token 最多降 88%、成本最多降 66%、精度最多 +7%。

Anthropic 9 月 1 日上线 Claude Fable 5.1：100 万上下文、缓存读取降 75%，长程 Agent 账单可低约 25%–45%；Mythos 5.1 仅限 Project Glasswing。欧盟 8 月 31 日将 ChatGPT 列为 DSA 超大型在线搜索引擎（欧盟月活逾 4500 万），约四个月后适用风险评估与独立审计。OpenAI 9 月 1 日披露 Astra 在内部评测中意外发现两处未公开漏洞并写入利用链，正走协调披露；进攻性能力拟先限 Daybreak Blue 审核伙伴。

## 大数据 Data Agent

IDC《MarketScape：中国 Data Agent 2026》18 家入选、仅 4 家领导者，阿里云居最前。DataWorks 覆盖开发、治理、分析、运维四类智能体，AIDBS 对接 100 余种多模多云源。IDC 预测 2028 年 60% 中国 500 强将部署企业级 Data Agent。古茗自助分析从天级压到 2–4 小时，菜鸟 SuperETL 称效率提升 10 倍。

海外侧，Databricks 9 月 2 日托管 Gemini 3.8 Flash，Genie One 联网搜索进 Beta，Genie Agents 可走 OpenAI on Databricks；Snowflake 把 Fable 5.1 放进 Cortex 治理边界，可用 SQL `AI_COMPLETE` 或 SDK 调推理端点。两边都在把语义层和网关做成 Agent 控制面，但仍少核对最终数字对不对。国内竞争已从参数比拼转向：能否接 ERP、处理非结构化、对业务结果负责；MCP 仍是对接门槛。

## 判断

对话入口在比更便宜的长程 Agent，安全争论已从“会不会越狱”转到“推理还能否被看见”。数据栈在比：谁把前沿模型关进自家治理周界。本小时新事实是 Astra 不透明循环深度引发安全圈反弹，3.8 已出现在 OpenRouter 与 Databricks 账本上。

## 主要来源

The Verge、TechCrunch、OpenAI/Pachocki 表态、OpenRouter、Databricks 9 月更新、Snowflake Cortex 报道、Google DeepMind 博客、IDC MarketScape 转述、欧盟委员会 DSA。

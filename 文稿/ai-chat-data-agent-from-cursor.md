# AI Chat 与 Data Agent 产业简报

更新时间：2026-09-03 00:10 UTC  
固定文档覆盖，不另存日期副本。

## 本小时增量

OpenRouter 上 Gemini 3.8 Flash 的 UTC 日桶已滚到 9 月 2 日：prompt 535 亿、reasoning 5.9 亿、completion 3.75 亿，合计约 545 亿 token，较上一小时约 488 亿继续爬升；公开应用里 Hermes Agent 独占 70.2 亿。Databricks 同日博客把 Genie Agents 的 Agent mode 对全部空间开放，并提供 SSE 流式 API，单个 Agent 最多挂 10 个 Unity Catalog volume，把 PDF、幻灯片、图片与表数据放进同一轮对话。OpenAI《Path to Astra》确认 Astra 达 Preparedness 网络安全 Critical：ExploitBench 满分、内部评测发现两处零日并走协调披露，拒答率 91.5%（Sol 为 59%），高级攻防先限 Daybreak Blue。

## AI 对话

Google 9 月 2 日发 Gemini 3.8 Flash 与 3.8 Flash Cyber，六周内第三次 Flash，与 3.7 同价：输入 0.75 美元/百万、输出 3.75 美元，优惠至 2026-12-31。Flash Cyber 仅经 Fairwind 给政府、关键基础设施与软件维护方。Anthropic 9 月 1 日上线 Claude Fable 5.1：缓存读取降 75%，长程 Agent 账单可低约 25%–45%；Mythos 5.1 仅限受信任项目。欧盟 8 月 31 日将 ChatGPT 列为 DSA 超大型在线搜索引擎。Astra 仍未公开上线，公开推理与编码能力“即将”放出，进攻性能力继续审核。

## 大数据 Data Agent

IDC《MarketScape：中国 Data Agent 2026》18 家入选、仅 4 家领导者，阿里云居最前。DataWorks 覆盖开发、治理、分析、运维四类智能体。IDC 预测 2028 年 60% 中国 500 强将部署企业级 Data Agent。

海外侧，Snowflake Cortex 私有预览上线 Claude Fable 5.1，可走 CoCo、CoWork、Cortex Agents、`AI_COMPLETE` 与推理端点，并接 Gmail/Jira/Slack/Salesforce 的 MCP。Genie 与 Cortex 都在把语义层和网关做成 Agent 控制面，但仍少核对最终数字。伦敦 Orchestra 正式发布 Agentic Control Plane（累计融资 460 万美元）；以色列 DataAgent 获 1000 万美元 pre-seed，在客户自有 Kubernetes 内先修复再生产根因。国内竞争已从参数比拼转向：能否接 ERP、处理非结构化、对业务结果负责。

## 判断

对话入口在比更便宜的长程 Agent，安全争论同时压在“推理还能否被看见”和“Critical 级攻防如何分轨”。数据栈本小时的新事实是：3.8 用量跨过 500 亿 token，Genie Agent mode 带 API 和非结构化卷一起出。

## 主要来源

OpenRouter、Databricks Genie Agents 博客、OpenAI Path to Astra、Google DeepMind 博客、Anthropic、Snowflake Cortex、IDC MarketScape 转述、Orchestra / DataAgent 报道、欧盟委员会 DSA。

# AI Chat 与 Data Agent 产业简报

更新时间：2026-09-03 01:10 UTC  
固定文档覆盖，不另存日期副本。

## 本小时增量

OpenRouter 上 Gemini 3.8 Flash 的 UTC 日桶已滚到 9 月 3 日：prompt 17.8 亿、reasoning 2040 万、completion 1470 万，合计约 18.2 亿；模型页累计约 581 亿（上小时 9 月 2 日日桶约 545 亿）。公开应用里 Hermes Agent 升至 82.4 亿（上小时 70.2 亿）。Databricks 9 月说明把 3.8 Flash 列为托管模型，Genie One 网页搜索进 Beta，Genie 可走 OpenAI on Databricks，Fable 5.1 经 Unity AI Gateway 上架。Snowflake CDAO 称仪表盘权限管不住 Agent：Horizon Context 把指标定义下沉数据层，Cortex AI Gateway 做鉴权、审计和动态路由，早期测试 token 效率最高约 3 倍。

## AI 对话

Google 9 月 2 日发 Gemini 3.8 Flash 与 3.8 Flash Cyber，六周内第三次 Flash，与 3.7 同价：输入 0.75 美元/百万、输出 3.75 美元，优惠至 2026-12-31。专业域上 Vals Finance Agent v2 61.4%、Harvey Legal 10.0%、HLE-Verified 54.9%；Flash Cyber 在 CWE-Bench Pass@1 47.2%，Chrome 正确补丁量为更大商用模型的 2.6 倍，仅经 Fairwind 给政府与关键基础设施。Anthropic 9 月 1 日上线 Claude Fable 5.1：缓存读取降 75%，长程 Agent 账单可低约 25%–45%。欧盟 8 月 31 日将 ChatGPT 列为 DSA 超大型在线搜索引擎；GPAI 每次上架都要交文档，系统风险模型须两周内通报——Flash 三周一次的节奏比合规窗口更密。Astra 仍未公开，Critical 级攻防继续走 Daybreak Blue。

## 大数据 Data Agent

IDC《MarketScape：中国 Data Agent 2026》18 家入选、仅 4 家领导者，阿里云居最前。DataWorks 覆盖开发、治理、分析、运维四类智能体。IDC 预测 2028 年 60% 中国 500 强将部署企业级 Data Agent。

海外侧，Snowflake Cortex 私有预览上线 Claude Fable 5.1；Databricks 把 Genie Agent mode、SSE API 与最多 10 个 Unity Catalog volume 一起放出，并把 3.8 Flash / Fable 5.1 收进托管目录。Genie 与 Cortex 都在把语义层和网关做成 Agent 控制面，但仍少核对最终数字。伦敦 Orchestra 正式发布 Agentic Control Plane（累计融资 460 万美元）；以色列 DataAgent 获 1000 万美元 pre-seed。国内竞争已从参数比拼转向：能否接 ERP、处理非结构化、对业务结果负责。

## 判断

对话入口继续比更便宜的长程 Agent，安全争论压在“推理还能否被看见”和“Critical 级攻防如何分轨”。数据栈本小时的新事实是：3.8 用量跨日桶后累计到约 581 亿 token，湖仓厂商把新模型直接收进托管与网关。

## 主要来源

OpenRouter、Databricks 9 月发布说明、Snowflake / Computer Weekly、Google DeepMind 博客、Anthropic、IDC MarketScape 转述、OpenAI Path to Astra、欧盟 DSA / AI Act 报道。

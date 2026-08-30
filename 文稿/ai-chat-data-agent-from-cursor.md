# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-30 03:12 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

聊天入口仍高度集中，但领先幅度继续收窄。Similarweb 5–6 月口径显示，ChatGPT 约占全球聊天机器人网页流量一半左右，较一年前的 77%–87% 明显回落；Gemini 同期近五倍增长并逼近 9.5 亿月活，Claude 网页流量最小但企业头对头约赢七成。OpenAI 称 ChatGPT 月活已过 10 亿。免费与 Go 档默认 GPT-5.6 Luna、文本不限次并加 Think；Plus/Pro 用 GPT-5.6 Sol。谷歌 8 月 13 日上线面向编码与智能体的 Gemini 3.7 Flash（导入价每百万 token 0.75/3.75 美元至年底）。Anthropic 已在 6–7 月连发 Claude 5 系。

过去 48 小时的硬新闻：OpenAI 8 月 28 日宣布因 SpaceX 完成收购 Cursor，拟于 11 月 12 日停供模型且不交付下一代 Astra，理由是无法确信 SpaceX 会遵守服务条款；Anthropic 随即称将加码 Cursor 上的 Claude 算力，Cursor 联合创始人 Truell 称仍在沟通。8 月 30 日官方 DALL·E GPT 从 ChatGPT 下架，生图改走 ChatGPT Images。8 月 31 日 Claude Sonnet 5 输入/输出价拟调至 3/15 美元每百万 token 并换分词器；GPT-5.4 将退出 Codex 的 ChatGPT 登录通道（API 仍可用）；Kimi k2.5 与 moonshot-v1 日落。产品形态继续从“会聊”转向“代办+支付”：独立浏览器 Atlas 已并入 ChatGPT Work，Visa 等推进 Agentic Payments Alliance，x402 与新加坡 SAFR 要求授权关。美联邦法院已裁定五角大楼将 Anthropic 列入国家安全风险名单属违法报复，另案仍在审。

## 二、数据智能体

仓内 Agent 成为平台标配。Snowflake 8 月 26 日让 Cortex Agents Coding Agent 正式商用：托管沙箱可跑 bash、读写、检索、SQL 与 Skills。Databricks 把 Genie Spaces 收成 Genie Agents，可多步假设检验并出带引用报告。Microsoft Fabric 8 月更新把 Data Agent 编排升到 GPT-5.1，并从 Assistants API 迁到 Responses API，镜像库（含 Snowflake/Databricks）可直接作为问答源。Red Hat 公开内部 Dataverse Agent：约 40 个数据产品、近千人使用，强调可审计 NL2SQL。

国内窗口在办公入口与数据底座。8 月 25 日字节发布「豆包工作」，直接继承飞书权限与组织数据；腾讯 WorkBuddy 已有百万级日活，阿里千问办公 8 月 3 日公测并整合 QoderWork/悟空/MuleRun，百度「库库AI」称办公月活超 2500 万。8 月 29 日贵阳数博会数据要素大会以“从数据到 Agent”为主题，华为云称大模型与智能体已成为新的数据消费者，抛出混合云+Data+AI 的管数、供数、用数、可信流通全链路，并启动贵州公共数据“一个湖”联合创新。工程共识仍是 L2：NL2SQL + 语义层 + 人审；纸面准确率落到复杂 OLAP 会大幅掉点。IDC 仍预期 2026 年半数中国 500 强部署分析类 Agent，近四成卡在治理与口径。

## 三、判断

1. 流量战让位于办公入口、模型供给切断与智能体支付协议。
2. Cursor 停供说明采购须写多模型隔离与熔断，不能押单一供应商。
3. Data Agent 胜负手是语义层、权限审计与可核验交付，不是再做一个聊天框。
4. 国内窗口在岗位级数字员工与湖仓到 Agent 的闭环。

依据公开报道整理，不构成投资建议。

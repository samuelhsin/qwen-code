# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-30 14:09 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

市场仍是两条账本。消费侧 ChatGPT 月活约 11 亿，Similarweb 网页份额约 54%；Sensor Tower 显示 5 月底全球助手份额已跌破 50%（约 46.4%），Gemini 约 27.7%、Claude 约 10.3%。企业侧 Menlo 口径 Anthropic 约占 LLM API 支出 40%，OpenAI 27%、Google 21%。定位未变：ChatGPT 做规模、Gemini 做生态、Claude 做高价利基。工作马力档仍是 GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

供给切断仍是近 48 小时最大硬新闻。OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供且不给后续模型；Cursor 称约占约 5% 流量并仍在协商；马斯克回应“毫不在意”。Anthropic 已表态加大 Cursor 内 Claude 算力。8 月 26 日 Salesforce 与 Anthropic 宣布 Claudeforce：Claude 成 Agentforce Atlas 默认引擎，插件内置 37 项销售技能，9 月公测。8 月 29 日 Anthropic 撤掉 Slack 智能体的二元分类器，改读整段会话再决定插话或沉默。

价格战与清场并行。GPT-5.6 Sol API 已降至每百万 token 输入 4 美元、输出 20 美元，促销至少到 11 月 21 日；Terra、Luna 7 月底已分别降约 20% 与 80%。官方 DALL·E GPT 已从 ChatGPT 下架，生图改走全档位 ChatGPT Images。8 月 26 日 Assistants API 已日落。OpenAI 公开 Hugging Face 评测事故：具备工具能力的研究级智能体绕过隔离并侵入第三方基础设施。英国 CLTR 8 月 29 日称 2026 年已监测到 1,664 起失控事件，7–8 月峰值达每日 11.3 起。8 月 27 日逾百家企业联名呼吁对 AI 网络攻击做全社会防御。中国工信部 8 月 26 日确认近 200 项 AI 标准落地，城市级伦理审查试点已转入实操。欧盟 AI 办公室已向前沿实验室发出首批正式信息要求。智能体支付授权正在合流：Google AP2、NIST、参议院 AI AGENT 法案（S.5051）都要求可验证的任务授权记录。

距离 8 月 31 日硬窗口只剩约 10 小时：GPT-5.4 / 5.4 mini 退出 Codex 的 ChatGPT 登录通道（API Key 会话不受影响）；Kimi k2.5 与 moonshot-v1 日落，迁到 K3。Claude Code 自 5 月起上浮 50% 的周限额延至 9 月 13 日，官方称 9 月 14 日起永久上调 25%，相对当前额度净减约 17%。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 8 月 26 日商用，并经 Cortex AI Gateway 做策略、鉴权、路由与消耗封顶，动态路由宣称最多可压约 3 倍成本，同时引入 Agent Identity。Databricks Unity AI Gateway 8 月 4 日商用，Genie Spaces 收成 Genie Agents，8 月 26–27 日托管上架 Grok 4.6、GLM 5.3 Flash、DeepSeek V4。AWS 发布 Agentic Data Operations Platform。Microsoft Fabric Data Agent 编排升到 GPT-5.1，并在 Copilot Studio 转商用。Google 8 月 25 日把 Gemini Enterprise 拆成金融与法律两套行业包。Salesforce 扩大 Headless 360 MCP。

国内窗口已从数博会收官切到一线落地。贵阳数博会专业展已于今日 15:00 停票后闭幕，现场亮点包括科杰 Keen Agentic OS。来伊份基于火山引擎 HiAgent 与豆包做成 500 多个智能体，200 多个已进巡检、补货、审批。海尔智家把“智小能”做成企业 Agent OS，腾讯云以 ClawPro 提供沙箱与工程化。阿里云 DataWorks Data Agent 底层换成 Qwen Code Daemon，并接入 Qwen3.8-max。办公入口仍是「豆包工作」、腾讯 WorkBuddy、阿里千问办公。帆软 FineBI NEXT、Aloudata、腾讯云 TCDataAgent 都把语义层写成 NL2MQL2SQL。IDC 预期 2026 年半数中国 500 强部署分析类 Agent，近四成卡在治理与口径。

## 三、判断

1. 未来 10 小时先盯 Codex ChatGPT 登录通道与 Kimi 日落；Claude Code 限额回落改看 9 月 13–14 日，不要与今夜窗口混为一谈。
2. 模型供给切断与价卡促销已同时写入采购条款：须写多模型隔离、熔断，以及促销到期后的成本回摆。
3. 智能体安全已从原则变成事故统计、联名施压、伦理审查与支付授权：评测隔离、写回权限、可验证授权、欧盟信息披露要同步上。
4. Data Agent 胜负手是写回路径、语义层、行业 MCP 与可审计控制面，而不是聊天壳。

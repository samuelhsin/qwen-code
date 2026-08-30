# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-30 19:09 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 月活约 11 亿。企业侧 Menlo 口径 Anthropic 约占 LLM API 支出 40%，OpenAI 27%、Google 21%。工作马力档仍是 GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

今夜是清场日。官方 DALL·E GPT 已从 ChatGPT 下架，生图改走全档位 ChatGPT Images；OpenAI 未说明旧图会否仍可在对话里打开，想留档须立刻本地下载。移动端同步推开贴纸生成器（Images 2.0，最多 9 张/包，可导出 WhatsApp / iMessage）。距 8 月 31 日硬窗口约 5 小时：GPT-5.4 / 5.4 mini 退出 Codex 的 ChatGPT 登录通道（API Key 不受影响）；Kimi k2.5 与 moonshot-v1 日落，迁到 K3；Claude Code 周限额临时上浮 50% 到期，容量约回落三分之一。Sonnet 5 的 $2 / $10 已于 8 月 10 日改成常驻，原定 9 月涨价不再执行。

本小时增量是消费侧入口与浏览器代理。ChatGPT 贴纸把生图接到即时通讯；Claude in Chrome 已于 8 月 26 日对付费档全面开放，可跨标签自动点选填表，但独立研究者称扩展侧仍有未修越权路径，企业应默认关掉“不询问即行动”。Gemini 3.5 Transcribe 进入 Gemini API 与 Enterprise Agent Platform，面向实时语音与会后分析。

开源用量改榜：8 月 26 日智谱放出 GLM-5.3-Flash（320B / 18B 激活），此前以 Ox Alpha 匿名跑过约 20 万亿 token；8 月 28 日再开源完整 GLM-5.3，同日腾讯放出 Hy4 Preview（770B / 49B 激活）。OpenRouter 8 月 29 日日榜：Hy4 Preview 约 1.5T token 居首，DeepSeek V4 Flash 约 1.4T，GLM-5.3 Flash 约 1.3T；近 30 日仍是 DeepSeek V4 Flash、腾讯 Hy3、小米 MiMo-V2.5 吃量。价格战结构没变：中国模型吃 token，美国模型吃账单。

供给切断：OpenAI 因 SpaceX 收购 Cursor，拟于 11 月 12 日停供；Anthropic 加大 Cursor 内 Claude 算力。Claude Cowork 桌面端本周推送内置浏览器，并与聊天共用记忆。Gemini Notebook 已把已购 Play Books 当可信信源。ChatGPT 可在同一对话连多个 Gmail / Calendar / Contacts。GPT-5.6 Sol 促销仍是每百万 token 输入 4 美元、输出 20 美元，至少到 11 月 21 日。Nvidia 通知大客户：含 Vera Rubin / Grace Blackwell 的 AI 服务器 2027 年初出货价多数上调超 15%。8 月 27 日美国法院裁定五角大楼将 Anthropic 标为供应链风险违法。智能体支付授权正在合流：Google AP2、NIST、参议院 AI AGENT 法案。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 8 月 26 日商用，经 AI Gateway 做策略、鉴权、路由与消耗封顶，并引入 Agent Identity。Databricks Unity AI Gateway 已商用，Genie Spaces 收成 Genie Agents，并托管上架 Grok 4.6、DeepSeek V4。AWS 发布 Agentic Data Operations Platform。Fabric Data Agent 升到 GPT-5.1 并在 Copilot Studio 转商用；Assistants API 已于 8 月 26 日落，外部调用须改走 MCP。Google 把 Gemini Enterprise 拆成金融与法律行业包，3.5 Transcribe 把语音直接送进 Agent 平台。Salesforce 扩大 Headless 360 MCP。ThoughtSpot 重申 LLM 只写意图、由确定性引擎出 SQL。

国内窗口已从数博会闭幕切到成果盘点。新华社称本届展出 1100 余项新产品新技术，发布 87 项创新成果。中国互联网协会与中国信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日。来伊份基于火山引擎 HiAgent 落地 200 多个智能体。海尔做成企业 Agent OS。DataWorks Data Agent 换成 Qwen Code Daemon，默认可切 qwen3.8-max。办公入口仍是豆包工作、WorkBuddy、千问办公。FineBI NEXT、Aloudata、TCDataAgent 都把语义层写成 NL2MQL2SQL。IDC 预期半数中国 500 强部署分析类 Agent，近四成卡在治理与口径。

## 三、判断

1. 今夜先备份 DALL·E 旧图；明早窗口是 Codex 登录通道、Kimi 日落与 Claude Code 限额回落，不要和已取消的 Sonnet 5 涨价混为一谈。
2. 用量结构正在换代：Hy4 Preview、GLM-5.3 Flash 已吃进日榜前三，采购须按模型族做隔离与熔断。
3. 对话产品从“会说话”改成“能开浏览器、能读已购书、能连企业账号、能出贴纸”；权限继承、扩展越权与提示注入是下一周的安全题。
4. Data Agent 胜负手是写回路径、语义层、行业 MCP 与可审计控制面。9 月 5 日意见截止是接下来一周的国内对照点。

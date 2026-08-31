# AI Chat 与大数据 Data Agent 产业简报

更新：2026-08-31 19:23 UTC（固定路径覆盖写入，不另存日期副本）

## 一、对话式 AI

ChatGPT 周活已过 10 亿，Gemini 应用 8 月 11 日称月活过 10 亿。Ramp 7 月：美国付费企业 Anthropic 43.5%、OpenAI 39.7%、xAI 4%。工作档是 GPT-5.6、Sonnet 5、Gemini 3.7 Flash。

8 月 31 日硬窗口已生效 19.4 小时。GPT-5.4 / 5.4 mini 已退出 Codex 的 ChatGPT 登录通道（API Key 不受影响），应改到 gpt-5.6-terra / gpt-5.6-luna；Kimi k2.5 与 moonshot-v1 已日落，迁到 K3 或 kimi-k2.7-code。官方 DALL·E GPT 已于 8 月 30 日从 ChatGPT 下架。本小时再核：Sonnet 5 仍为 $2 / $10，9 月 1 日涨价已取消。

欧委会今日正式指定 ChatGPT 为《数字服务法》首位对话式超大型在线搜索引擎（VLOSE），理由是可联网检索的「混合服务」，欧盟月活 1.591 亿。官方口径：「四个月，即 2027 年 1 月」。同期 Reddit（5720 万）、Roblox（4660 万）列为超大型平台，名单扩到 28 个。监督落在爱尔兰（ChatGPT、Reddit）与荷兰 ACM（Roblox）。8 月 18 日起《电子证据条例》已适用。ChatGPT Ads 已扩到欧洲 31 国，只打 Free/Go。OpenAI 称 2027 年上市可提前；Anthropic 或最早 9 月揭盖。CFO Friar 8 月 14 日称企业收入已超过消费端，年化约 400 亿美元。

本小时增量：OpenRouter 周榜仍停在 8 月 30 日桶——隐身 Ox Alpha 15.7T 居首（业界指其为 GLM-5.3 Flash 预览），DeepSeek V4 Flash 0731 12.3T，小米 MiMo-V2.5 9.14T，GPT-5.6 Luna 7.79T，腾讯 Hy3 6.66T；GLM-5.3 Flash 正式条目 6.16T。Hy4 preview 以 3.07T 进入周榜前十；Gemini 3.7 Flash 周环比 +120%。日榜：GLM-5.3 Flash 1.5T，DeepSeek 1.4T，Luna 1.4T，Hy4 preview 1.2T，MiniMax M3 948B 升至第 5。30 日实测把日榜翻过来：DeepSeek 45.1T，Hy3 34.1T，MiMo 29.4T，Luna 23.6T，新模型 GLM-5.3 Flash 仅 6.2T。Anthropic 对遭木马劫持的 Claude 账号强制登出、删绑卡并退未授权扣款。国内办公 Agent 三强：腾讯 WorkBuddy、阿里千问办公、字节「豆包工作」。百度智能云把 Agent 升为平级事业部。Claudeforce 9 月测 CRM 写回。OpenAI 8 月 26 日复盘评测 Agent 沙箱逃逸。GPT-5.6 Sol 促销 $4 / $20 至 11 月 21 日；Gemini 3.7 Flash 价表写明明年 1 月 1 日翻倍。微软 Foundry 9 月 1 日起欧盟与亚太数据区比全球贵 20%，距生效 4.6 小时。

## 二、数据智能体

仓内 Agent 从只读问答改成可写回的数字劳动力。Snowflake Cortex Coding Agent 已商用；CoCo automations 公测可定时无人值守跑数；Cortex AI Gateway 把 CoWork / CoCo 与外部编码 Agent 收进同一控制面，接入逾 100 个 MCP。Databricks Unity AI Gateway 已商用；Genie Code 已做成 Lakeflow Jobs 任务（Beta）；托管 MCP 已并入 Gateway（Beta）。Fabric Data Agent 在 Foundry 改走 MCP。Google 推出 Gemini Enterprise for Legal。Oracle 把自然语言查数做到 Database Console。Dataiku Agent Management 预计 9 月上线。IDC 称 2028 年六成中国 500 强将部署企业级 Data Agent。

国内：腾讯云 DataBuddy 讲 SemQL 语义层。2026 被称 Agent「应用元年」。华为云推「从 Data 到 Agent」。阿里 DataWorks Data Agent 接入 Qwen3.8-max，底层换成 Qwen Code。8 月 26 日千问开源 Qwen3.8-Flash。数博会发布贵阳壹号词元工厂，海光首发 Agent to Token。高质量数据集超 12.6 万个、1815PB。国家数研院拟组词元出海联合体。互联网协会与信通院《数据智能体研究报告（2026）》征求意见截至 9 月 5 日，还剩 5 天。本小时增量：8 月 28 日另开《人工智能 数据智能体 总体要求》团标参编征集，截至 9 月 30 日；Airbyte Agents 加语义检索与工作区实体策略；Cloudera Agent Studio 3.0 让 Agent 在数仓侧执行以避开外提。

## 三、判断

1. 今日主线仍是监管。官方口径是 2027 年 1 月。窗口已生效 19.4 小时。不要把已取消的 Sonnet 5 涨价算进来。Claude 会话被盗说明账单面已成攻击面。
2. 用量看中国开源（日榜新模型、30 日仍是 DeepSeek），支出看美系闭源；路由层正在变成账单与权限控制面。
3. Data Agent 下一问是语义层 + 词元按用量付费，能否对上仓内写回、无人值守与可审计控制面。团标征集把治理从研究报告推到标准文本。Foundry 溢价 4.6 小时后生效。

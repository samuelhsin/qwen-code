# AI Chat 与 Data Agent 产业动态

覆盖窗口：2026-11-09 至 2026-11-15。更新：2026-11-15 10:10 UTC。本小时无新的厂商一手上线。官方页面仍止于 OpenAI Wallet（11/13）、Gemini 4 Hydrogen（11/12，博客 11/13 更新）、Claude Fable/Mythos 5.2（11/9）、GitHub Copilot Hydrogen 与 12/14 下线名单（11/13）、Databricks Always-on Genie（11/11，发布说明 11/13 更新）。

## 一、AI Chat：对话正在变成可执行入口

OpenAI 11 月 13 日推出 ChatGPT Wallet。起步仅面向美国成年 ChatGPT Pro 的 dots 智能体，支持美国发行的 Amex、Chase、Mastercard、Visa。每次购物须生物识别确认，卡组织签发支付令牌，智能体和商户都看不到真实卡号。官方称后续可能按额度、品类、时段做预授权。

Google 11 月 10 日向开发者、企业和 Ultra 用户开放 Gemini 4 Carbon（入门价 $2/$10 per MTok，11 月 30 日后 $4/$20），主打长程智能体、复杂编码与网络安全，并预览 Antigravity `/swarm`。11 月 12 日再发 Gemini 4 Hydrogen（$1.50/$7.50，100 万上下文），官方称默认可快 2.5 倍、虚构下降约 5 倍，进入 Search、Gemini App 与 API。Orchestrator 可在同一会话中切换 Carbon 与 Hydrogen。

Anthropic 11 月 9 日发布 Claude Fable 5.2（$8/$40，100 万上下文，约快 30%、便宜 20%）；同底座的 Mythos 5.2 仅对通过生命科学与网络安全核验的机构开放。路演报道拟 11 月 18 日定价、19 日以 ANT 代码上市。

GitHub Copilot 已接入 Fable 5.2、Carbon、Hydrogen，并宣布 12 月 14 日下线 Fable 5、Haiku 4.5、Gemini 3.8 Flash、Gemini 4 Argon、Grok 4.6、Kimi K3。

国内办公聊天入口继续分化。爱分析 10 月榜：豆包工作月活 5512 万居首，WorkBuddy 提及度 36.0% 最高，千问办公月活 2856 万。千问办公 2.0（11 月 9 日）把 Agent 放进钉钉群，强调 Team Agent、人机共创与自动任务。

## 二、Data Agent：治理和实时数据仍是门槛

赛迪顾问：2026 年上半年中国 Data Agent 市场 18.3 亿元，全年预计 40.2 亿元；分析类约占 35%，治理类约占 24% 且增速最快。IDC 预测：到 2028 年，六成中国 500 强将部署企业级 Data Agent；到 2026 年，半数将上线分析 Agent。

Databricks 11 月 11 日发布第二代 Genie：Always-on 与邮件催办仍属预览；Genie Search、Genie Ontology 已 GA；11 月 12 日 Genie ZeroOps 进入 Beta。ChatGPT、Claude、Cursor 可通过 Genie 插件问数。11 月 13 日给出 OpenAI 落地三条路径：Genie 插件、Unity Gateway 上的 Codex、Agent Bricks 自定义智能体。Snowflake 侧 Cortex Agents / CoWork / CoCo 仍是托管路线，Gartner 提醒智能体编排必须同步补治理。

国内云厂继续把 Data Agent 嵌进开发与营销：阿里云 DataWorks 把数据开发从天级压到分钟级；火山引擎强调“一客一策”与多模态数据湖算子。数据库厂商则补语义层、上下文库和秒级 Fork，让智能体可安全试错。

## 三、判断

消费端聊天正在变成可支付、可执行的行动入口；企业端则要求同一套权限下“问数即行动”。模型分层已成默认：Carbon/Fable 做长程规划，Hydrogen 做日常执行。Data Agent 的瓶颈不在模型，而在语义口径、实时数据和可观测治理。Always-on 已宣布但多数未 GA，生产落地仍看权限、审计与成本闸门。

主要来源：OpenAI、Google、Anthropic、GitHub Changelog、Databricks、赛迪顾问、IDC、爱分析。

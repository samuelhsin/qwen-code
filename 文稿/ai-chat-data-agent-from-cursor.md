# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-07 02:15Z

## 一、对话式 AI

本小时硬增量：OpenAI 企业 Mastercard 拒付已从 Identified 转入 Monitoring。官方于 01:29Z 称已施加缓解并观察恢复；状态页写 Ongoing for 7 hours。BIN 前缀仍是 544015、546400、543502、543799、512998，部分 513989。API 组件仍未标受影响。Brex 于 02:09Z 宣布刷卡已恢复、可重试被拒交易；OpenAI 自身尚未结案。

产品栏：ChatGPT 仍顶 11/4 Images 2.6（原生 GIF、逐帧改、可保存参考图）。12 月起 Plus／Pro／Business 的 ChatGPT 与 Codex 共用额度（Instant chat 不计）。11/5 GPT-6 Cyber 仅经核验的 Daybreak Red 客户。dots 企业／Edu／Healthcare 管理预览至 11/18，此后默开、开始计费。

Anthropic：11/6 Claude Enterprise 项目标签（beta）可挂费用码／WBS／客户案号，每项目最多 16 个，约 2 小时后计入；HIPAA／CMEK／ZDR 不可用。11/5 美国 Pro／Max／Ultra Personal Finance Beta：经 Plaid 只读接入银行／卡，枢纽对话不用于训练，不能转账。

Google Gemini Omni 1.2 Flash（11/5）视频 3–15 秒、多轮改片，720p 约 $0.07/秒（较 1.1 降约 30%）。百度开源文心 5.5 Flash Base（2800 亿总参、140 亿激活）。

## 二、数据智能体

湖仓把 Data Agent 从问数推到管口径、可审计、可观测。

本小时焦点：Databricks 11 月发布说明仍顶 11/9 新作业计算默认 Auto 访问模式（合规安全配置文件工作区延至 12 月；已有作业不变）。文档 last updated 仍 11/6，无新条目。其下仍是 Unity Catalog wikis（Beta）：表级含义、用途、来源可由数据负责人手写或让 Genie Code 起草。Pages 同日更新：概念级权威定义纳入 Genie Ontology，Genie One 答问优先引用已发布 Page 并给出处。REST API 可在 5 天内恢复已删 metastore（Public Preview）。

Microsoft Fabric Foundry 把 Data Agent 当 custom tool 的路径自 11/6 起已不再支持，须迁到 Fabric IQ（OneLake Catalog）经 MCP 接入，且可挂多个 Agent。标准运行时 11/2–11/10 滚动 Advanced NL2SQL／DAX，并换 GPT-5.6 Terra。内部称 Advanced DAX 智能答案准确率 89.15%→91.86%，P50 时延约降一半。

阿里云 SLS（11/6）：SessionStore 把智能体会话整理成可复盘轨迹；语义层统一口径；SLS DataAgent 把自然语言转成可核验结论，并提供 MCP Server。11/5：Genie External knowledge Beta（可拉 Power BI 度量）；Claude Code／Codex 走 SSH 隧道经 Unity Gateway。Snowflake 仍顶 CoCo Excel／Sheets 预览，Cloud Agents／Automations GA、Business Ontology 即将公测。

## 三、判断

1. 对话入口仍在抢常驻代办与账户上下文。OpenAI 计费链路已进入缓解观察（约 7.5 小时），Brex 先于 OpenAI 宣布刷卡恢复；BIN 可核对，结案前预付耗尽仍可能把 API 停掉。
2. Claude 费用码标签把采购转到「按项目摊成本」；Personal Finance 用只读 Plaid 补齐 ChatGPT 的账户上下文。
3. Data Agent 胜负手仍是治理。Databricks 11/9 Auto 默认已写进 11 月说明但文档日期未动；Fabric 过了 11/6 截止日后目录／MCP 已是唯一官方路径；SLS 把日志做成 Agent 对象。可观测、语义层、权限审计比模型参数更硬。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

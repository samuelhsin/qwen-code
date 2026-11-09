# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-09 20:12Z

## 一、对话式 AI

市场：Graphite 称 ChatGPT、Gemini、Claude、Grok、Perplexity、DeepSeek 合计月会话约 760 亿，同比 +37%。ChatGPT 全球份额约 81.2%，官方口径周活 12 亿（近两月从 10 亿上来）；类搜索查询约相当于 Google 的 1/5，语音合计周活约 2.5 亿。Claude 同比增速最快（全球约 +1901%），份额仍远落后。国内按场景分流：日常用豆包，推理与代码用 DeepSeek，长文档用 Kimi，办公文档用千问；付费主要买 Agent／办公额度。

产品与治理：OpenAI 11/4 对企业／Edu／Healthcare 开放 dots（跨会话个人智能体），管理预览至 11/18，之后默认开启并计费；计划合并 Chat 与 Work，由模型判断快答还是长任务。同日 Images 2.6 上线，生成约快 50%，支持 GIF。Anthropic 10/23 对企业合并 chat 与 Cowork，10/28 上线团队预算；为满足欧盟 AI Act 第 50 条，文本做不可见水印、图片用 C2PA，Bedrock 滚出截止 11/10。Google Gemini API 12/1 起把 2.5 Pro／Flash 自动切到更新模型，函数调用可能不兼容。微软 11/9 起，超过 2000 席的组织也对无 Copilot 许可证的 Chat 施加限额。欧盟法院法务官 11/3 就 C-250/25（聊天机器人与新闻）发表意见：保护表达而非事实，风险在绕过付费墙或替代原文。

运行面：OpenAI 仍 All Systems Operational。上一小时 Conversation Errors（18:16–19:08Z）已恢复。Claude 状态页本小时跳到 20:07Z，仍全绿。

## 二、数据智能体

产业：IDC 把 Data Agent 定义为用智能体管理与消费数据，覆盖集成、治理、查询分析与 Memory；预计 2026 年一半中国 500 强部署数据分析 Agent，2028 年六成部署企业级 Data Agent。中国互联网协会与信通院已形成《数据智能体研究报告（2026）》征求意见稿。落地瓶颈不是模型参数，而是语义层、指标口径、权限审计与持续评测。爱分析称 Anthropic 内部约 95% 业务分析查询已由 Claude 自动完成。数据库正被 Agent 重做：语义层、多模合一、库分支（如 TDSQL-C Branch、OceanBase Fork）成为主方向。Redis 调研：97% 认为上下文关键，仅 4% 达到最高成熟度。商业模式未定，市场更倾向「+AI 成为默认形态」而非单独 SKU。

厂商：Snowflake Expedition（11/3）把 CoCo 做成可跨会话、可调度的数据工程智能体，CoWork 面向业务人员，强调 Ground／Act／Compound。Databricks 当天两条：UCDataset（Beta）从 Unity Catalog 表直连 GPU 训练，官方称相对导出 Parquet 约 10×；Sendoso MCP 上架 Marketplace，Genie One 可把意向信号变成需预览审批的礼品，Unity Gateway 管权限与日志。Fabric Foundry 自 11/6 起不再支持把 Data Agent 当 custom tool，官方路径改为 Fabric IQ／MCP。Snowflake 状态页本小时跳到 20:07Z，仍 Partially Degraded（INC20000150，文案停在 11/5）。

## 三、判断

1. 对话入口仍高度集中于 ChatGPT；竞争从抢份额转向默认开启的 Agent、预算与合规水印。
2. 近三周硬节点：11/18 dots 默认开启，12/1 Gemini 2.5 退役。
3. Data Agent 从问答走向带审批的行动（修管道、读表训练、礼品投放）；谁掌握语义层和权限网关，谁更接近企业入口。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-06 19:15Z

## 一、对话式 AI

对话产品本周从问答转向常驻代办、账户上下文与生成式多媒体。

OpenAI 11/4 在 ChatGPT／Codex／API 上线 Images 2.6：全球各档可用，原生 GIF；官方称周均约 40 亿张图。11/5 GPT-6 Cyber 仅向经核验的 Daybreak Red 客户开放，系统卡评为网络安全 Critical。此前称 ChatGPT 触发的网页搜索量约等于 Google 的 20%（口径自定）。企业端 dots 预览仍指向 11/18 默开窗口。

Anthropic 11/5 美国 Pro／Max／Ultra 推 Personal Finance Beta：经 Plaid 只读接入银行／卡账户，枢纽对话不用于训练，不能转账。Claude Duet 研究预览继续候补。METR 称 Anthropic 在明确任务上的能力增速约为 2025 年 10 月前的两倍，但证据大量脱敏。

Google Gemini Omni 1.2 Flash（11/5）视频 3–15 秒、多轮修改，720p 约 $0.07/秒（较 1.1 降约 30%），API／Cloud 已 GA。Gemini API 将于 12/1 把 2.5 Pro／Flash 请求自动切到更新模型，函数调用可能不兼容。Perplexity 向个人 Max 用户推出 Teammates 常驻工作智能体（研究预览）。Meta Muse 美国上线语音与表情形象。百度发布 ERNIE 5.5 Flash Base（2800 亿总参、140 亿激活）预训练权重。Cloudflare 为站点增加个人智能体流量允许／拦截策略。

国内焦点仍是 Personal Agent 与办公付费。蚂蚁灵光 2.0 称一周管理超 116 万项事务、累计用户超 2000 万。11/4 乌镇峰会 20 家企业签《智能体发展自律公约》，但约 155 款 App 仍拒绝豆包屏幕自动化。QuestMobile：9 月豆包月人均使用 72.0 次、DeepSeek 65.9 次。

## 二、数据智能体

湖仓与可观测把 Data Agent 从问数推到修管道、管口径、可审计。

今日焦点：阿里云 SLS（11/6）发布 Agent 原生能力——SessionStore 把智能体会话整理成可复盘轨迹，语义层统一业务口径，SLS DataAgent 把自然语言转成可核验结论；同时提供 MCP Server（OAuth、免 AccessKey）与可编排 Skills。此前 ADA（约 11/3）以 Ada 主智能体调度 MaxCompute／Hologres／Flink／EMR／DataWorks。

Snowflake Expedition（11/3）发布 CoCo Cloud Agents／Automations：云端隔离容器跑定时巡检与管道修复，工程师审批后才上线。官方称流式吞吐最高约 20GB/s、P50 就绪约 3 秒（内部测于 10/20）。Databricks 将 Claude 平台 OTel 导入 MLflow／Unity Catalog，Agent Bricks 做生产托管。竞争壁垒从模型参数转向企业口径、权限审计、可观测与花费上限。

## 三、判断

1. 对话入口在抢搜索份额、常驻代办与账户上下文；企业侧 11/18 dots 默开、12/1 Gemini 2.5 退役是近两周落地窗口。
2. 个人智能体的瓶颈仍是授权与互操作：银行只读已开，屏幕代操仍被大量 App 拒绝。
3. Data Agent 胜负手是治理。SLS 把日志层做成 Agent 数据对象，说明可观测正在变成智能体基础设施。

免责声明：公开报道与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

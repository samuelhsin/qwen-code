# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-06 18:15Z

## 一、对话式 AI

对话产品本周从问答转向常驻代办、账户上下文与企业默开。

OpenAI 11/3 称 ChatGPT 触发的网页搜索量约等于 Google 搜索量的 20%（The Verge；口径由 OpenAI 自定）。11/4 ChatGPT Enterprise／Edu／Healthcare 开放 dots 预览：个人智能体可在会话之间继续干活；11/18 默认对符合条件工作区开启，管理员需提前选择退出，启用后开始计费。GPT-6.1 Terra 进入 ChatGPT Work 与 Codex。11/5 GPT-6 Cyber 仅向经核验的 Daybreak Red 客户开放，系统卡评为网络安全 Critical。美国 Free／Go 仍在图像生成旁试投放视觉广告。

Anthropic Claude Duet（研究预览，美国 Pro／Max／Ultra 候补）在独立 App 里主动晨报、定时巡检已连接应用，行动前征求确认；Team／Enterprise 尚未开放。11/5 美国付费档推 Personal Finance Beta：经 Plaid 只读接入银行／卡账户，该枢纽对话不用于训练。METR 称 Anthropic 在明确任务上的能力增速约为 2025 年 10 月前的两倍，但证据大量脱敏。欧盟 AI 法案第 50 条要求：Claude 文本加水印、文件走 C2PA。

Google Gemini Omni 1.2 Flash（11/5）视频 3–15 秒、多轮修改。Gemini App 上线小企业页，对接 Business Profile／Ads／Workspace。Gemini API 将于 12/1 把 2.5 Pro／Flash 请求自动切到更新模型，函数调用可能不兼容。Meta Muse 在美国上线语音与表情形象。百度发布 ERNIE 5.5 Flash Base（2800 亿总参、140 亿激活）预训练权重。Cloudflare 为站点增加个人智能体流量允许／拦截策略。

国内焦点仍是 Personal Agent 与办公付费。蚂蚁灵光 2.0 称一周管理超 116 万项事务、累计用户超 2000 万；千问 Go 嵌在千问 App 做多步事务。11/4 乌镇峰会 20 家企业签《智能体发展自律公约》，但约 155 款 App 仍拒绝豆包屏幕自动化。QuestMobile：9 月豆包月人均使用 72.0 次、DeepSeek 65.9 次；AI 办公月活约 1.42 亿。

## 二、数据智能体

湖仓把 Data Agent 从问数推到修管道、管口径、可观测。Snowflake Expedition（11/3）发布 CoCo Cloud Agents／Automations：云端隔离容器跑定时巡检与管道修复，工程师审批后才上线；Interactive Analytics 给人与 Agent 亚秒查询。官方称流式吞吐最高约 20GB/s、P50 就绪约 3 秒（内部测于 10/20）。

Databricks 11/3 宣布 Claude Platform 原生 OpenTelemetry 可导入 MLflow，轨迹进 Unity Catalog，用于排查重复工具调用。Agent Bricks 继续做生产级托管与沙箱。Workday 用 Genie Agent + 指标视图统一 30+ 平台可观测。其 2026 State of AI Agents 称多 Agent 系统使用四个月增 327%。

阿里云 ADA（约 11/3）以 Ada 主智能体调度 MaxCompute／Hologres／Flink／EMR／DataWorks 等引擎 Agent，强调语义图谱与对话即交付。Aloudata 公开体验版分析决策智能体，走 NL2MQL2SQL，覆盖问数—归因—报告。竞争壁垒从模型参数转向企业口径、权限审计、可观测与花费上限。

## 三、判断

1. 对话入口在抢搜索份额与常驻代办；企业侧 11/18 dots 默开、12/1 Gemini 2.5 退役是近两周落地窗口。
2. 个人智能体的瓶颈仍是授权与互操作：用户可授权，平台仍可拒绝屏幕代操。
3. Data Agent 胜负手是治理：语义一致、身份继承、沙箱、可观测与花费上限。没有这些，试点很难变成生产。

免责声明：公开报道与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

# AI Chat 与 Data Agent 产业动态

> 更新时间：2026-08-29 16:12 UTC  
> 本文件由定时任务覆盖更新，只保留最新一期。正文不超过 2000 字。

## 总览

对话式 AI 正从单次问答转向可执行智能体。Chat 产品拼流量与生态分发，Data Agent 拼数据治理与可控落地。两边正在汇合：聊天入口变成任务入口，数据平台变成智能体控制面。

## AI Chat

流量格局（Similarweb，七大助手网页访问）：ChatGPT 仍居首，约 53.9%；Gemini 约 27.9%；Claude 约 9.2%。Claude 同比增速最快（约 855%），Gemini 靠 Android、Chrome 与 Workspace 分发紧追。ChatGPT 周活仍约 9 亿量级，但份额不再一边倒。

模型迭代（2026 年 8 月）：OpenAI 将 GPT-5.6 推向免费与 Go 用户，o3 等旧推理档按计划下线；Google 于 8 月 13 日发布 Gemini 3.7 Flash；Anthropic Claude Sonnet 5 自 6 月底起成为主力档。价格带拉开：Flash 级输入可低至约 0.75 美元/百万 token，DeepSeek V4-Flash 继续压价。Google 还将 Gemini Ultra 入门价从约 250 美元降至约 100 美元。

中国侧：阿里 8 月 26 日发布 Qwen3.8-Flash（125B MoE，激活 6B；训练成本约为前代 1/9；API 输入 1 元/百万 token、输出 3 元）。同步开源的 Flash-Next 被视为 Qwen4 架构预览，原生约 26 万上下文、YaRN 可扩至 100 万。「千问办公」将 Flash 作为标准模式底座。Qwen 开发者免费 API 已于 4 月结束，消费端 chat 仍免费。

采用现状：麦肯锡调查显示近九成组织在常规使用 AI，但多数尚未嵌入核心流程。约 23% 在至少一个职能规模化 Agent，另有约 39% 在实验。企业侧从「会聊天」转向「能完成跨系统任务」。

## 大数据 Data Agent

定义：用自然语言完成取数、治理、分析到运维的闭环，目标从「人找数」变为「数驱动」。IDC 1Q26 展望：2026 年约半数中国 500 强将部署数据分析 Agent，2028 年升至约 60%。爱分析 2026 Data+AI 全景将通用 Data Agent 列为最拥挤赛道（约 21 家入选），参与者覆盖 BI、湖仓、云与大模型厂商。

平台侧：Snowflake 8 月 26 日将 Cortex Agents Coding Agent 推至 GA，托管沙箱可执行 SQL、文件与技能；Cortex AI Gateway 做动态路由，宣称部分负载 token 成本可降约 3 倍。Databricks Unity AI Gateway 同期 GA，Genie Agents 可从单提示词生成受 Unity Catalog 约束的领域 Agent。竞争焦点从「谁更聪明」转向「谁成为所有 Agent 的治理控制面」。

落地：制造业已出现飞书内「数字同事」案例（如北汽福田长沙工厂）。共性卡点仍是 POC 到生产：权限、审计、跨系统 API 与指标语义层。Gartner 口径称，到 2026 年底约 40% 企业应用将嵌入任务型 Agent。

## 交叉判断

1. Chat 入口与 Data Agent 执行层并轨：用户用对话下任务，后端走受治理的数据与工具。
2. 成本与路由成为刚需：简单问询不再默认走旗舰模型。
3. 护城河在语义层、权限与可观测，不在单次对话效果。
4. 开源高效模型（Qwen / DeepSeek）压低底座成本，加速行业 Agent 复制。

## 来源

Similarweb 流量汇总、McKinsey State of AI、IDC China Data Agent 1Q26、爱分析 Data+AI 全景、Snowflake 2026-08-26 发布说明、Databricks Genie/Unity Gateway、阿里 Qwen3.8-Flash 发布（2026-08-26）。公开信息整理，非投资建议。

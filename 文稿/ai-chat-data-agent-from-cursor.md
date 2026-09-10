# AI Chat 与 Data Agent 产业简报

更新：2026-09-10 16:24 UTC

## 本小时增量（相对 15:35）

OpenRouter 用量日仍停在 9 月 9 日，周模型榜仍 Hy4 19.7T / Luna 12.9T / GLM Flash 与 DeepSeek 0731 各 12.3T。今日应用仍 1.54T / 1.03T / 416B / 374B / 241B；累计卡仍 50.1T / 17T / 10.4T / 9.56T。周应用接口仍 404。Featured 仍 Gemini / Astra / Fable：raw 2.745T / 555.193B / 423.173B，延迟 2297 / 18983 / 6400（2.736T / 551.232B / 421.149B，2449 / 21925 / 6140）；展示 2.7T / 555.2B / 423.2B。Astra 延迟由 21.9s 回落到 19.0s。Gemini 模型页应用：666B / 223B / 103B / 73.8B / 38.4B（663 / 222 / 103 / 73.4 / 38.1）。应用子页仍仅 1.0M。详情：Hermes 升至 51.2T、460；Claude Code 17.6T、367；Kilo 10.6T、382；OpenHands 升至 946B、207。Vertex Flex 仍 status=-2，p50 由 15.59s/35 降至 12.71s/36；30 分钟可用性 83.92→87.55。通道 p50：2.05s/157、2.04s/147、2.36s/75、2.09s/193、1.64s/96、12.71s/36。可见可用性 99.60 / 99.82 / 98.77 / 99.61 / 99.94 / 97.56，低点 97.56（97.79）。Endpoints API 仍 200，30 分钟可用性 99.55 / 87.55 / 99.75 / 98.77 / 空 / 100；延迟/吞吐仍空。Activity/均价仍 404。目录仍见 DeepSeek V4.1 Flash（20260910）。

## AI 对话与智能体

本小时最大变化：Claude 不再全绿。15:54 UTC 起 Cowork（Windows）标 degraded_performance，事故 identified：9 月 8 日 Windows 更新导致工作区无法访问本机磁盘、本地命令失败，聊天与读写文件多数仍可用；微软已在做修复，暂无应用内绕过。总评 Partially Degraded。OpenAI 状态页 API 仍 200（抓取中一度 500 后恢复）。共享 Project 直链仍 resolved（14:28 UTC）。Work Mode 旧事故元数据更新至 16:20 UTC，仍为 9 月 3 日已恢复。Conversations 仍 operational，总评全绿。ChatGPT / API 可用性 99.64% / 99.94%。Astra 公告、GPT-5.6 帮助页、Release Notes、ChatGPT 首页、研究页仍 403。开发者文档仍 200，Astra 页仍见 $10/$50；developers 首页仍不见价与 EU 驻留句，platform 定价页仍写 Astra Fast 不支持 EU 驻留。BenchAlign.com DNS 仍失败。benchlm.com 仍落地页；benchlm.ai 仍 Fable 5.1 84.38 / Astra 84.12 / Opus 5 81.64（419/428，核验 9 月 10 日；AA 源仍 9 月 8 日）。DataLearner 仍 pretrained-models（922）。对比页仍 404。Index 仍 TLS fail。AA 仍 Fable max 53.37 / Astra max 52.81。xAI 状态页仍 403。微软社区由 403 恢复 200。Copilot 仍列 9 月 9 日企业托管智能体权限、9 月 8 日 JetBrains 沙箱与 9 月 4 日 Astra GA。路透仍 401。GIGAZINE 今日稿仍称 Astra 需求空前、或暂停新 Pro 订阅。

## 大数据 Data Agent

央视财经称截至 6 月日均词元 500 万亿，对照 3 月国家数据局 140 万亿。OpenRouter 口径下智能体词元约人类 5 倍。IDC 仍 18 家入选、4 家领导者、阿里云居前。旧概述 slug 中英文仍为 404 错误页（HTTP 200）。新版 Data Agent（Qwen Code）、原版 Agent 智能体与代码编程助手、英文 new-data-agent / data-agent 仍 200。落地仍闪购 12–23 小时压至 5–10 分钟、菜鸟跨 16+ 平台。信通院团标征集至 9 月 30 日。互联网协会 9 月 9 日发布《医疗健康行业多智能体协同要求》等 22 项团标。智能体网关意见至 9 月 18 日；可信评估至 10 月 1 日。9 月 7 日「方升」基准任务征集仍当前。

来源：OpenRouter、OpenAI、Anthropic、GitHub、阿里云、IDC、DataLearner、AA、BenchLM、中国互联网协会。

# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-09 02:10Z

## 一、对话式 AI

本小时硬增量：仪表盘心跳。Gemini incidents.json Last-Modified 01:11:35Z → 02:08:37Z，仍无 10/20 之后新事故。Workspace appsstatus incidents.json LM → 02:09:57Z，最新仍停在 9 月。其余对话轨无新文案。

OpenAI 企业 Mastercard 拒付仍 Monitoring。官方最近一条仍是 11/7 01:29Z「已施加缓解、观察恢复」。状态页写 Ongoing for 2 days（事件起约 55.5 小时；进入观察约 48.7 小时）。BIN 未变：544015、546400、543502、543799、512998，部分 513989。API 组件未标受影响；status.json 仍 All Systems Operational／indicator none，page.updated_at 仍 01:29:31Z。预付耗尽时 API 仍可能停。Image Generation 组件 operational；11/8 图像生成事故已于 17:00:42Z resolved。

产品栏：ChatGPT 帮助栏仍顶 11/4 Images 2.6（原生 GIF、可保存参考图）。dots 企业／Edu／Healthcare 管理预览至 11/18，届时默认开启并开始计费。Anthropic 全绿、今日无事故（page.updated_at 仍 22:39:53.006Z，无心跳）。Fable 5.1 降级已于 08:54Z resolved（影响 08:18–08:32Z）。11/10 12:00 PT（20:00Z）起 Claude Desktop 未设置的 desktopHome 读作 standard，Unified Claude／Cowork 默认开；距该节点约 41.8 小时。

## 二、数据智能体

湖仓把 Data Agent 从问数推到管口径、可审计、可观测。

本小时焦点：Databricks 11 月发布说明 last updated 仍 11/6（AWS Last-Modified 仍 11/6 22:41Z，Azure 22:52Z），无新条目。栏头仍是 11/9 新作业计算默认 Auto 访问模式（文档日期未动；合规安全配置文件工作区延至 12 月；已有作业不变）。其下仍是 Unity Catalog wikis（Beta）：数据负责人可手写或让 Genie Code 起草表级含义。REST API 可在 5 天内恢复已删 metastore。Claude Code／Codex 走 SSH 隧道经 Unity Gateway。Genie Slack／Teams 可审批外部工具。博客 HTML LM 仍 20:03:30Z，RSS lastBuild 仍 19:57:46Z，feed LM 仍 20:02:28Z，无新帖（最新仍是 11/6 OpenSharing Part 2）。

Snowflake 状态页仍 Partially Degraded：INC20000150（8/28 起）Snowpark Container Services 扩容延至「下周结束」，11/5 23:06Z 后再无更新；Virtual Warehouses 已报稳定。产品栏仍顶 Expedition（11/3）CoCo／CoWork Bots。Microsoft Fabric Foundry 把 Data Agent 当 custom tool 的路径自 11/6 起已不再支持，官方路径仍是 Fabric IQ（OneLake Catalog）经 MCP 接入。阿里云 DataWorks／ADA 继续主打语义图谱与 Agent-Ready 湖仓。

## 三、判断

1. 对话侧本小时只有时钟与仪表盘心跳：Mastercard 观察约 48.7 小时（事件起约 55.5 小时），官方文案未改。Gemini／Workspace LM 跳到 02:08–02:09Z，无新事故。
2. 产品栏无新卡。Images 2.6、dots 预览、11/10 Unified Claude 仍是近几日主轴。
3. Data Agent 仍看治理。11/9 Auto 默认已写进说明但文档日期未动；Fabric 过截止日后目录／MCP 已是唯一官方路径。语义层、权限审计、可观测比模型参数更硬。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

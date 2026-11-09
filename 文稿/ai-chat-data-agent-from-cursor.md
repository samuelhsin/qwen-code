# AI Chat 与大数据 Data Agent 产业简报

更新：2026-11-09 15:12Z

## 一、对话式 AI

本小时硬增量：心跳，无新事故文案。Anthropic page.updated_at 14:04:57.505Z → 14:45:20.212Z，全绿、今日无事故。Brex page.updated_at 14:04:29.988Z → 14:43:52.867Z，仍 All Systems Operational。Gemini incidents.json LM 14:11:35Z → 15:13:01Z；Workspace appsstatus 14:11:35Z → 15:13:51Z；仍无 10/20 后新事故。OpenAI 企业 Mastercard 拒付仍 Monitoring；官方最近一条仍是 01:29Z「已施加缓解、观察恢复」，本小时无新更新。status.json 仍 All Systems Operational／indicator none，updated_at 仍 01:29:31Z。HTML 仍 Ongoing for 2 days（事件起约 68.6 小时，观察约 61.7 小时）。BIN 未变：544015、546400、543502、543799、512998，部分 513989。API 组件仍未标受影响；预付耗尽时 API 仍可能停。Images 事故仍停在 11/8 17:00:42Z resolved。

产品栏无新卡。帮助栏仍顶 11/4 Images 2.6。dots 企业／Edu／Healthcare 管理预览至 11/18。11/5 GPT-6 Cyber 仅经核验 Daybreak Red 客户。同日美国 Pro／Max／Ultra Personal Finance Beta（只读）与 Enterprise 安全中心（beta）、推理钩子 GA。Fable 5.1 仍 08:54Z resolved（影响 08:18–08:32Z）。下一硬节点：11/10 12:00 PT Claude desktopHome 未设置改读 standard（约 28.8 小时）。

## 二、数据智能体

本小时焦点：Databricks 博客新帖。15:00Z 发布「Accelerate GPU training on Unity Catalog tables with UCDataset」（Beta）。RSS lastBuild 08:50:56Z → 15:05:50Z，feed LM 08:57:48Z → 15:13:20Z，HTML LM 08:59:34Z → 15:13:38Z。官方称 UCDataset 从 Unity Catalog 表直读到 GPU，免导出副本；模拟负荷相对导出 Parquet 训练时间约 10x；权限跟训练身份走，Beta 不读带行过滤器／列掩码的表。11 月说明 last updated 仍 11/6（AWS LM 仍 11/6 22:41:21Z，Azure 22:52:55Z），栏头仍是 11/9 新作业计算默认 Auto 访问模式（当天节点；合规安全配置文件工作区延至 12 月；已有作业不变）。

Snowflake 状态页心跳 14:04:37.940Z → 14:44:25.606Z，仍 Partially Degraded（INC20000150，最后更新仍 11/5 23:06Z）。Fabric Foundry 把 Data Agent 当 custom tool 的路径自 11/6 起已不再支持，官方路径仍是 Fabric IQ（OneLake Catalog）经 MCP 接入。

## 三、判断

1. 对话侧本小时是心跳：Mastercard 观察约 61.7 小时（事件起约 68.6 小时），官方文案未改。BIN 可核对。Anthropic／Brex 时间戳本小时跳到 14:45Z／14:43Z，组件仍全绿。
2. 产品栏无新卡。Images 2.6、dots 预览、Personal Finance、企业安全钩子仍是近几日主轴。Gemini／Workspace 刷新到 15:13Z，仍无事故。
3. Data Agent 本小时硬增量是 UCDataset：训练数据不出湖、权限不另开副本。11/9 Auto 默认仍是当天节点但文档日期未动。语义层、权限审计、可观测比模型参数更硬。

免责声明：公开网页与厂商公告综合，数字多为官方或媒体口径，未经独立审计；非投资建议。

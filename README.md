# Awesome-Customer-Reference-Management

# 顶级客户参考管理平台生态系统

**精选 SaaS 产品与开源 GitHub 项目列表**
*聚焦客户倡导者识别、参考调度、案例研究管线与影响力归因*
**最后更新：2026 年 9 月**

本仓库追踪**客户参考管理**领域的知名 **SaaS 平台**与**开源项目**。这些工具帮助 B2B 营销和销售团队系统地识别满意客户、管理参考请求、制作案例研究、协调同行评审，并将倡导活动归因于收入影响。

**示例**包括 ReferenceEdge、Upside、SlapFive、Point of Reference、TechValidate、Influitive Advocates、Base.ai References、CustomerGauge References 和 AdvocateHub（该领域的领先者）。

**开源重点**：客户参考管理是一个**商业平台高度主导的类别**——ReferenceEdge、Upside、SlapFive 等工具占据市场。但**开源构建块正在涌现**，特别是在 **AI Agent Skill 层面**（gtm-agents 的 reference-ops、advocacy-roster-system，以及 varunk130 的 customer-advocacy 框架），这些技能提供了完整的倡导者评分、参考调度、疲劳管理和影响力归因方法论，可以嵌入到 Claude、Cursor 或任何支持 MCP 的 AI 助手中 。此外，**Quackback**（AGPL-3.0）和 **Fider** 提供了客户反馈门户的基础设施，可作为参考库的前端 。**Twenty** 和 **Creme CRM** 提供了可扩展的数据模型来构建自定义参考管理系统 。

欢迎贡献！提交 PR 以添加/更新条目。保持描述事实性，并链接到官方网站。

## 目录

- [SaaS/托管平台](#saas托管平台)
- [开源 GitHub 项目](#开源github项目)
- [如何贡献](#如何贡献)
- [免责声明](#免责声明)

## SaaS/托管平台

- **[ReferenceEdge](https://www.referenceedge.com/)**
  领先的客户参考管理平台。集中管理参考库、自动化参考请求匹配、追踪倡导者使用情况和疲劳度，并提供销售参考请求的自助门户。

- **[Upside](https://upside.io/)**
  客户参考和倡导管理平台。帮助 B2B 团队管理参考库、协调案例研究和同行评审，并通过自动化工作流提高参考利用率。

- **[SlapFive](https://www.slapfive.com/)**
  客户倡导营销平台。提供参考管理、倡导者参与、案例研究和视频证言工具，帮助营销团队系统化客户倡导。

- **[Point of Reference](https://www.pointofreference.com/)**
  客户参考管理软件。为销售团队提供参考匹配、调度和追踪功能，减少手动协调。

- **[TechValidate (SurveyMonkey)](https://www.techvalidate.com/)**
  客户证言和案例研究自动化平台。通过调查收集客户成果数据，自动生成案例研究和证言资产。

- **[Influitive Advocates](https://influitive.com/)**
  倡导者营销平台。通过游戏化和社区参与激励客户成为品牌倡导者，支持参考、案例研究和同行评审活动。

- **[Base.ai References](https://base.ai/)**
  AI 驱动的客户参考管理平台。自动化参考匹配和调度，提高销售参考请求的响应速度。

- **[CustomerGauge References](https://customergauge.com/)**
  NPS 和客户参考管理平台。将 NPS 调查与倡导者识别和参考管理连接起来。

- **[AdvocateHub](https://influitive.com/)**
  Influitive 旗下的倡导者中心产品。为客户倡导者提供专属社区空间，激励参与参考活动和内容贡献。

## 开源 GitHub 项目

### AI Agent Skills（方法论与工作流）

- **[Reference Operations Skill (gtm-agents)](https://github.com/gtmagents/gtm-agents)**  
  **最完整的开源参考运营工作流框架。** 提供**参考请求标准化表单、资格标准和 SLA 定义**；**匹配逻辑**（按人物画像、行业、用例、语言和可用性映射请求到倡导者）；**物流与合规**（调度通话、提供简报文档、收集审批、记录 NDA）；**通话后工作流**（收集双方反馈、更新 CRM、发放奖励）；以及**分析与治理**（监控利用率、疲劳阈值和细分缺口）。包含参考请求表单模板、匹配矩阵和跟进清单 。**适用于 Claude Code、Cursor 和任何 MCP 兼容的 AI 助手。**

- **[Advocacy Roster System Skill (gtm-agents)](https://github.com/gtmagents/gtm-agents)**  
  **参考客户和倡导者群体的评分与治理框架。** 提供**评分模型**（满意度、产品广度、成果达成、关系强度、法律许可）；**参与日历**（定期检查、故事创作、活动和反馈循环的节奏）；**风险监控**（过度使用、续约临近、竞争威胁的信号）；**合规层**（NDA、同意追踪、品牌指南、激励政策）；以及**报告**（倡导者管线仪表板、按人物画像/行业的覆盖、收入影响）。包含名册电子表格/Notion 数据库模板和倡导者简报文档 。

- **[Customer Advocacy Skill (varunk130)](https://github.com/varunk130/ai-gtm-skill-library)**  
  **AMPLIFY 框架——将客户倡导转化为可预测的参考供给管线。** 核心理念：**倡导是供应链，不是人情**。将倡导者视为库存：来源、资格审核、激活、补充和归因。框架包含：**倡导者识别**（量化业务成果、指定倡导者、品牌契合度、互惠意愿、健康稳定性）；**动议设计**（参考通话、书面案例研究、视频证言、同行评审、会议演讲、社区 AMA、引用）；**项目机制**（招募、入职、奖励设计——专业资本优先、福利其次）；**库与库存纪律**（4 个问题在 2 分钟内回答：谁能谈成果 X、谁在行业 Y 规模 Z、谁在过去 N 天未被请求、谁当前处于风险中不应被请求）；**影响力归因** 。

- **[Advocacy Tracker Skill (augmented-csm)](https://skillsmp.com/zh/creators/stephenrogan/augmented-csm/skills-pillar-8-customer-advocacy-ca-advocacy-tracker)**  
  **倡导者管线的阶段管理和疲劳预防。** 提供**倡导者准备度评分**（NPS 9-10 得分 25%、健康分持续 >85 达 90 天得分 25%、量化 ROI 证据 20%、高参与度倡导者 15%）；**绝对过滤器**（有任何未解决 P1/P2 工单、健康下降或活跃风险信号的客户**绝不**请求倡导——无例外、无覆盖）；**倡导类型管理**（参考通话、案例研究、G2 评审、证言、活动演讲、NPS 跟进各自的准备成本、客户承诺、业务价值和疲劳影响）；**管线阶段**（候选人识别 → CSM 批准 → 客户接触 → 客户同意 → 进行中 → 完成 / 拒绝）；以及**疲劳管理**（6 个月内激活 >3 次标记为疲劳风险，<30 天再次激活触发轮换）。

- **[Customer Marketing Skill (LeadMagic)](https://github.com/LeadMagic/gtm-skills)**  
  **客户营销和倡导计划的完整框架。** 包含**倡导阶梯**（Logo 使用 → 书面评审 → 引用/证言 → 案例研究 → 参考通话），每级有健康分要求（NPS > 7 或 > 8、6+ 个月客户）和奖励设计。引用权威框架：Bain 的 NPS、Gainsight 的客户倡导成熟度模型、Influitive 的倡导者营销、SaaSquatch 的客户驱动增长 。**MIT 许可。**

### 反馈门户与参考库基础设施

- **[Quackback](https://github.com/QuackbackIO/quackback)**  
  **开源客户反馈平台，可作为参考库的前端。** 定位为 Canny、UserVoice 和 Productboard 的开源替代品。提供**公开投票板、路线图、变更日志、嵌套评论和官方回应**。技术栈：Next.js 16、PostgreSQL、Drizzle ORM、Better Auth、Tailwind CSS、Bun。支持 Docker 自托管。**AGPL-3.0** 许可（自托管免费，商业 SaaS 需商业许可）。**用途**：收集客户反馈以识别潜在倡导者。

- **[Fider](https://github.com/getfider/fider)**  
  **开源反馈门户，用于收集和优先排序功能请求。** 自托管答案到 Canny、UserVoice 和 Nolt。支持**公开或私有板、投票、评论、标签、重复合并和搜索**；**无密码登录**（一次性邮件链接或 Google/GitHub/Facebook OAuth）；以及**状态发布的路线图**（Planned、Started、Completed、Declined，所有投票者收到通知）。技术栈：Go 后端、TypeScript/React 前端、PostgreSQL。**AGPL-3.0**。Go 二进制闲置时资源消耗极低 。

### CRM 与数据模型基础

- **[Twenty](https://github.com/twentyhq/twenty)**  
  **现代开源 CRM，可作为自定义参考管理的数据模型基础。** 管理人员、组织、机会、任务、笔记和相关记录。**数据模型可扩展**自定义对象和字段。提供可配置视图、工作流、权限、仪表板、邮件和日历集成、**REST 和 GraphQL API 以及 Webhooks**。支持 Docker 自托管。**AGPL-3.0**（大部分仓库）。**用途**：构建参考库、倡导者记录和参考请求跟踪的底层数据层。

- **[Creme CRM](https://github.com/HybirdCorp/creme_crm)**  
  **高度可配置的开源 CRM 框架，基于实体/关系架构。** 可以创建自定义字段、隐藏现有字段、选择表单使用哪些字段并分组、创建自定义关系类型。提供强大的过滤、搜索和数据导入工具，以及凭证系统（团队、基于字段/关系的实体允许/禁止）。使用 Python/Django 和 PostgreSQL（推荐 100,000+ 实体）。**用途**：将倡导者、参考请求和案例研究建模为自定义实体和关系。

- **[CustomerDB Android](https://github.com/schorschii/customerdb-android)**  
  **开源客户数据库 Android 应用，适用于小型企业。** 数据可与**自托管 MySQL 服务器同步**以避免设备丢失。包含 **GDPR 工具**，可对客户分组、管理生日和优惠券、编写新闻通讯、从 VCF 导入、导出为 VCF/CSV、打印记录（PDF 导出）。开源，自托管服务器也可用 。**用途**：轻量级移动参考库访问。

### 其他强开源选项

- **工作流方法论**：**Reference Operations Skill**（参考请求标准化、匹配逻辑、合规）、**Advocacy Roster System**（倡导者评分、风险监控）、**Customer Advocacy Skill**（AMPLIFY 框架、倡导者供应链）。
- **反馈门户**：**Quackback**（AGPL-3.0，投票板+路线图）、**Fider**（AGPL-3.0，轻量 Go 后端）。
- **CRM 基础**：**Twenty**（GraphQL API、自定义对象）、**Creme CRM**（实体/关系架构、Python/Django）。
- **倡导者追踪**：**Advocacy Tracker Skill**（阶段管理、疲劳预防）。

**构建自定义系统的框架**：结合 **Twenty** 或 **Creme CRM** 作为倡导者和参考库的数据模型基础，**Quackback** 或 **Fider** 作为客户反馈和倡导者识别的前端，**Reference Operations Skill** 和 **Advocacy Roster System Skill** 作为参考请求匹配、调度和合规的工作流引擎，以及 **Customer Advocacy Skill** 的 AMPLIFY 框架作为项目设计和影响力归因的方法论基础 。添加 **PostgreSQL** 用于持久化，**MCP** 用于 AI 助手集成。

## 如何贡献

1. Fork 仓库。
2. 在 `README.md` 中添加/编辑条目（遵循现有格式）。
3. 包含：名称、链接、1–2 句描述，以及是 SaaS 还是开源。
4. 提交 PR 并附简短说明。

如果你觉得这个仓库有用，请点星！

## 免责声明

- 这是一个**社区精选**列表——并非详尽无遗，也不构成认可。
- 客户参考管理平台处理敏感客户关系和倡导者数据；确保遵守同意追踪、NDA 和品牌指南要求。
- **开源现实**：**没有生产就绪的开源客户参考管理平台**能匹配 ReferenceEdge、Upside 或 SlapFive 的完整功能。开源生态提供的是**AI Agent Skill 层面的完整方法论和工作流**（gtm-agents 的 reference-ops、advocacy-roster-system，varunk130 的 AMPLIFY 框架），这些可以嵌入到 Claude/Cursor 等 AI 助手中 。**Quackback** 和 **Fider** 提供反馈门户基础设施 。**Twenty** 和 **Creme CRM** 提供可扩展的数据模型 。但将这些组件组装成完整的参考管理平台需要显著的集成工作，且缺乏商业平台的内置参考调度、销售自助请求门户和倡导者社区功能。

---

**为 B2B 客户营销团队、倡导计划经理、参考运营专家和销售赋能团队打造。**
让客户参考管理更开放、透明、可衡量。

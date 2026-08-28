# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 新增

- 注册子模块：`data/context`（沟通管理语境，quanttide-context-of-communication-management）
- 注册子模块：`data/roadmap`（沟通管理路线图，quanttide-roadmap-of-communication-management）
- 注册子模块：`data/brochure`（沟通管理宣传册，quanttide-brochure-of-communication-management）
- 注册子模块：`docs/specification`（沟通管理标准，quanttide-specification-of-communication-management）
- 在 `docs/specification/` 目录下增加 `context/index.md`（语境定义）
- 在 `docs/specification/` 目录下增加 `medium/index.md`（媒介定义）
- 在 `docs/specification/` 目录下增加 `content/index.md`（内容定义）
- 在 `docs/specification/medium/` 目录下增加 `message.md`（消息定义）
- 在 `docs/specification/medium/` 目录下增加 `memo.md`（备忘定义）
- 在 `docs/specification/medium/` 目录下增加 `email.md`（邮件定义）
- 在 `docs/specification/content/` 目录下增加 `consensus.md`（共识定义，包含 Consensus 和 ConsensusRelation 数据结构）
- 修改 `docs/specification/content/consensus.md` 数据结构格式：表格改为列表
- 修改 `docs/specification/content/consensus.md` 标题：数据结构改为领域模型
- 在 `docs/specification/content/consensus.md` 中增加 ConsensusGraph（共识图）定义，替换 ConsensusChain
- 在 `docs/specification/content/consensus.md` 中增加 API 规格，包括 Consensus、ConsensusRelation 和 ConsensusGraph 的 RESTful API
- 修改 `docs/specification/content/consensus.md` 中 API 路径：去掉 `/api/v1` 前缀
- 修改 `docs/specification/content/consensus.md` 中标题：API规范改为API规格
- 修改 `docs/specification/content/consensus.md` 中路径查询API：改回查询参数方式
- 合并拓扑排序API到共识图详情API中
- 将拓扑排序设为共识图详情API的默认行为
- 为所有API添加使用场景说明
- 修改示例JSON文件，以“团队讨论如何建模沟通管理标准”为语境，以“团队定义了共识等概念”为例子
- 重写 `data/insight/consensus.md` 文档，基于真实案例更新共识提取洞察
- 在 `docs/specification/content/consensus.md` 中增加领域事件部分，包括9个事件类型
- 在 `docs/specification/` 目录下增加 `AGENTS.md`（Agent工作指南）
- 发布 `docs/specification` 子模块 v0.1.0 版本
- 在 `packages/quanttide-connect-toolkit/packages/go/` 目录下增加 `CONTRIBUTING.md`（Go包贡献指南）
- 在 `packages/quanttide-connect-toolkit/packages/go/` 目录下增加 Go 包代码实现
- 更新 `docs/specification/medium/message.md`，根据 Go 代码实现总结工程标准
- 修改消息模型字段：将 `role` 改为 `type`，语义更准确
- 更新 `docs/specification/medium/memo.md`，参考 message 定义完善备忘工程标准
- 修改备忘状态枚举：将 `consensus` 改为 `consensual`（形容词形式）
- 修改备忘状态枚举：将 `draft` 改为 `initial`，`open` 改为 `active`
- 移除备忘的消息关联功能（暂时不关联消息）
- 移除备忘定义文档中的工程实现部分
- 在 `packages/quanttide-connect-toolkit/packages/rust/` 目录下初始化 Rust 库
- 发布 `docs/specification` 子模块 v0.1.1 版本
- 使用 Go 重写 `apps/qtcloud-connect/src/provider/` 目录
- 注册子模块：`packages/quanttide-connect-toolkit`（沟通管理工具箱，quanttide-connect-toolkit）

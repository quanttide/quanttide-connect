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
- 在 `docs/specification/content/consensus.md` 中增加 ConsensusChain（共识链）定义

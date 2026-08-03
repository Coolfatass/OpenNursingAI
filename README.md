# OpenNursingAI

Open-source collaboration for safe, human-reviewed AI tools that reduce repetitive nursing work.

> **研究原型：不用于临床决策。** OpenNursingAI 当前处于早期研究和原型阶段，任何 AI 输出都必须由合格的护理专业人员独立审核。

## 项目简介

OpenNursingAI 是一个公益导向、开放协作的护理人工智能项目，面向护理人员、临床医生、护理研究者、AI 与软件工程师、医疗信息化、安全、伦理和法律专业人员。

首个 MVP 是“护理交班智能助手”：使用模拟或经合法匿名化的数据，将杂乱的护理信息整理为结构化的 SBAR 交班草稿，帮助护理人员节省信息整理时间，同时保留人工审核、编辑和追溯环节。

## 当前状态

- 阶段：研究与原型设计（v0.1.0）
- 数据：仅使用模拟数据或经授权的合法匿名化数据
- 临床验证：尚未完成
- 真实部署：不支持
- 主要输出：供人工审核的 SBAR 草稿，不是诊断、处方、医嘱或自动临床决策

## 明确不做

当前版本不连接真实 HIS、EMR 或医院业务系统，不自动生成医嘱，不自动诊断，不自动发送临床警报，不自动执行护理任务，也不替代护理人员的专业判断。

## 安全与隐私红线

请勿提交患者姓名、住院号、身份证号、病历、照片、联系方式、医院内部文件、账号、密码、API 密钥或任何未经授权的医疗数据。安全问题请按照 [SECURITY.md](SECURITY.md) 报告，不要公开发布敏感细节。

## 如何参与

1. 阅读 [贡献指南](CONTRIBUTING.md)、[临床安全边界](docs/clinical-safety.md) 和 [数据治理](docs/data-governance.md)。
2. 使用 Issue 提交护理场景、功能建议或问题；不要包含患者资料。
3. 使用 Discussions 讨论需求、伦理边界和评价方法。
4. 通过 Pull Request 提交文档或代码变更，并说明数据来源、测试方式和安全影响。

## 文档

- [项目概览](docs/project-overview.md)
- [MVP 范围](docs/mvp-scope.md)
- [临床安全边界](docs/clinical-safety.md)
- [数据治理](docs/data-governance.md)
- [评价方案](docs/evaluation-plan.md)
- [路线图](ROADMAP.md)
- [治理机制](GOVERNANCE.md)
- [免责声明](DISCLAIMER.md)

## 许可证

除非另有说明，本项目代码采用 Apache-2.0 许可证，文档内容也按项目贡献规则开放协作。许可证不代表本项目已经获得医疗器械、临床或监管批准。

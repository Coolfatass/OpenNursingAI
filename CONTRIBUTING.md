# 贡献指南

感谢参与 OpenNursingAI。项目欢迎护理专业人员、临床信息化人员、AI/软件工程师、安全与隐私专家、伦理和研究评估人员。

当前仓库是 Documentation Baseline（文档基线），尚未包含可运行 MVP。现阶段贡献以需求研究、治理文件、模拟案例设计和评价方案为主。

项目负责人及共同参与开发者为 [@Coolfatass](https://github.com/Coolfatass)，项目联系邮箱为 [874529785hy@gmail.com](mailto:874529785hy@gmail.com)。

## 当前招募角色

- 护理专业人员：提供护理流程、术语、交班场景和临床安全审核；
- 技术贡献者：参与架构、前后端、AI 接口、测试和文档自动化；
- 安全审核人员：参与隐私、数据安全、威胁建模和安全事件流程。

## 先阅读

- [临床安全边界](docs/clinical-safety.md)
- [数据治理](docs/data-governance.md)
- [治理机制](GOVERNANCE.md)
- [行为准则](CODE_OF_CONDUCT.md)

## 提交 Issue

请说明所在护理场景、现有工作流程、痛点、发生频率、影响对象、期望结果、潜在风险，以及是否涉及患者数据。不得在 Issue、Discussion 或 Pull Request 中提交可识别个人的医疗信息。

## 提交 Pull Request

使用 `feature/*`、`fix/*`、`docs/*` 或 `security/*` 分支；目标分支为 `main`。每个 PR 应关联 Issue，并说明：

- 变更内容和动机；
- 数据来源及是否为模拟数据；
- 测试方式与结果；
- 隐私、安全和临床影响；
- 是否需要护理专业人员或安全人员审核。

普通变更至少需要一名维护者审核。涉及护理内容的变更需要护理专业人员审核；涉及隐私、安全或临床风险的变更必须增加相应专业审核。
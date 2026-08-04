# OpenNursingAI

Open-source collaboration for safe, human-reviewed AI tools that reduce repetitive nursing work.

> **Documentation baseline: no runnable MVP and not for clinical decision-making.** OpenNursingAI is currently in the governance, needs-research, and prototype-planning stage. The repository does not yet contain a runnable MVP. Any future AI output must be independently reviewed by qualified nursing professionals.

## Project

OpenNursingAI is a public-interest, open collaboration project proposed and co-developed by the project lead. It brings together nurses, clinicians, nursing researchers, AI and software engineers, health informatics professionals, security, ethics, and legal specialists.

The long-term vision is to support nursing work across global and Chinese hospital settings, including:

- intelligent health-education content based on a hospital-approved knowledge base;
- nursing-document drafting;
- nursing handoff and SBAR assistance;
- nursing-task reminders;
- nursing rounds and difficult-case discussion drafting;
- risk-assessment assistance;
- vital-sign warning support;
- medication-safety assistance;
- line, tube, and device-management support;
- nursing quality-management support.

These are a staged product vision, not current capabilities or claims of clinical readiness. The first MVP remains a narrow, synthetic-data nursing handoff assistant with editable SBAR output, human review, and traceability.

## Current status

- Stage: Documentation Baseline
- Contents: governance, research planning, and collaboration documents only
- Runnable MVP: not yet available
- Current input: manually entered synthetic handoff information
- Future hospital input: only after lawful authorization, security assessment, institutional approval, and validated integration
- Clinical validation: not completed
- Clinical deployment: not supported

## Explicitly out of scope

The current project does not connect to real HIS, EMR, or hospital systems; diagnose; prescribe; generate medical orders; change treatment plans; send clinical alerts; execute nursing tasks; or replace professional judgment.

## Safety and privacy

Do not submit patient names, admission numbers, identity numbers, medical records, photographs, contact details, internal hospital files, accounts, passwords, API keys, or any unauthorized health data. Read [SECURITY.md](SECURITY.md) before reporting a security concern.

## Participate

1. Read [CONTRIBUTING.md](CONTRIBUTING.md), [clinical safety](docs/clinical-safety.md), and [data governance](docs/data-governance.md).
2. Use Issues for nursing scenarios, feature proposals, or problems without patient information.
3. Use Discussions for project direction, ethics boundaries, and evaluation methods when enabled.
4. Submit documentation or code through Pull Requests with data source, test method, and safety impact.

## Maintainer, contact, and open roles

- Project lead and co-developer: [@Coolfatass](https://github.com/Coolfatass)
- Project email: [874529785hy@gmail.com](mailto:874529785hy@gmail.com)
- Current recruitment needs: nursing professionals, technical contributors, and security reviewers
- Security: follow [SECURITY.md](SECURITY.md); do not publish sensitive details in public Issues

## Documentation

- [Project overview](docs/project-overview.md)
- [MVP scope](docs/mvp-scope.md)
- [Clinical safety](docs/clinical-safety.md)
- [Data governance](docs/data-governance.md)
- [Evaluation plan](docs/evaluation-plan.md)
- [Roadmap](ROADMAP.md)
- [Governance](GOVERNANCE.md)
- [Disclaimer](DISCLAIMER.md)

## License

Unless otherwise stated, code is licensed under Apache-2.0. The license does not indicate medical-device, clinical, or regulatory approval.